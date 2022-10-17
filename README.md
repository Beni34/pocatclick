# Készítette: Beni34
Ez a kód lehetővé teszi a korlátlan popcat clicket!

Kód:

var event = new KeyboardEvent('keydown', {
	key: 'g',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
