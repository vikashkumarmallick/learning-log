DATE: 13 Nov 2026, "ffmpeg and qrencode".
ffmpeg is a universal media converter,it can read a wide veraity of inputs.
qrencode, encode input data in a QR code and save as a PNG or EPS image.
1.qrencode -o bbb.jpg "https://github.com/vikashkumarmallick/line_counter_script.git"
2.ffmpeg -i lbcc.mov -vf "fps=15,scale=480:480" abc.gif
BREAK: 1. I changed the file extension to xyz and it showed "Unable to choose output format for MSN.xyz"
2. I removed the flag -o and it showed "no output filename is given"
