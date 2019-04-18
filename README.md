# LogTextWebview
let LogText = document.createElement('div');
		LogText.id = "logtext";
		LogText.setAttribute("style", "position: fixed; color: red; pointer-events: none; z-index: 9999; display: block; top: 0px; left: 0px; text-align: left;");
		LogText.innerHTML = window.game_igp_code
		document.body.appendChild(LogText);
