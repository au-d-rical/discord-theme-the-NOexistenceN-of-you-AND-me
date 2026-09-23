1.) Copy the link address of the font file posted in my github (right click on the file, then click copy link address)

2.) go to raw.githack.com

3.) the very top bar where you can paste in a url, paste the link address there

4.) now you should have the smaller 2 bars below the top bar, one for production and one for development; we are going to copy the one for development

5.) with vencord or any discord cilent modifier, go to settings and find where you can edit your cilent with CSS

6.) paste the code below:

@font-face {

	font-family: 'MyCustomDaFont';
	
	src: url('INSERT GITHACK DEVELOPMENT LINK HERE') format('woff2');
	
}

*, ::placeholder, body, button, input, select, textarea {

	font-family:'MyCustomDaFont', sans-serif;
	
}

:root {

	--font: 				"MyCustomDaFont", "Noto Sans", sans-serif;
	
}

7.) see where it says " INSERT ... HERE "?, replace that whole section of text with the development link BUT DO NOT REMOVE THESE SYMBOLS: (''), THIS IS THE SYNTAX FOR CSS AND IT WILL CAUSE A SYNTAX ERROR MEANING THE CODE WILL NOT WORK

8.) should work now! :D

CREDITS TO https://www.youtube.com/watch?v=w4_I_ux1HM8&pp=ygUvaG93IHRvIGdldCBjdXN0b20gZm9udHMgb24gZGlzY29yZCB3aXRoIHZlbmNvcmQ%3D
