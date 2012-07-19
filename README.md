qrcode-npm
==========

This is an npm module for qrcode JavaScript library (http://www.d-project.com/qrcode)

Notice that I am not the author of the code, I am just the creator of an npm module out of the great library from Kazuhiko Arase
Notice also that there is another module (node-qrcode, see: https://github.com/soldair/node-qrcode), which is more sophisticated,
but that uses [canvas](https://github.com/LearnBoost/node-canvas) module. If your target system can run the canvas module then I
recommend using node-qrcode, otherwise use qrcode-npm

examples
--------
	var qrCode = require('qrcode')

	var qr = qrCode.qrcode(4, 'M');
	qr.addData(text);
	qr.make();

	qr.createImgTag(4);    // creates an <img> tag as text
	qr.createTableTag(4);  // creates a <table> tag as text

install
-------
	npm install qrcode-npm
	
The word "QR Code" is registered trademark of DENSO WAVE INCORPORATED
