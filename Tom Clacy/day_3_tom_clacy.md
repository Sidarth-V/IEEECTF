Link: https://ctfquestionday3.vercel.app/
Category: Web

On first sight nothing particulary interesting about the website.

so curl:
some empty space is seen better E and ach of the first word which is not copying. So pushed the output to a txt file and opened on cyberchef  

on converting to hex "e2 80 8b" seems to be repeated with other bytes in between

checking unicode list, it stands for zero width space

found this stego tool from another CTF's writeup: https://offdev.net/demos/zwsp-steg-js


on decoding

FLAG: IEEECTF{0_WIDTH_J@CK_R@Y@N_3N0UGH?}
