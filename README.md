# GuidePoint Security CTF - Solution for "Blocky"

Visit webpage [on gh pages](https://fbarda.github.io/gpsctf-blocky-solution)

To use it:
1. extract all files in the zip to a folder, and drag **all** of them to the file input.

Then,
- the page will convert each file to a 244*244 png file,
- send it to an online qrcode reader api, (thanks, [goqr](https://goqr.me)),
- parse the result hex string,
- and finally, print it on the document.

2. After that, find one with the curly braces and voila, there is your flag!
