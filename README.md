
1.0.1) Copy the link address of the font file posted in my github (right click on the .gif file, then click copy link address)

1.0.2) Copy the link address of the font file posted in my github (right click on the .woff2 file, then click copy link address)

2.) go to raw.githack.com

3.) the very top bar where you can paste in a url, paste the link address there --- YOU SHOULD PASTE ONE LINK AT A TIME; IN ANY ORDER THAT YOU LIKE (GIF->WOFF2 OR VICE VERSA)

4.) now you should have the smaller 2 bars below the top bar, one for production and one for development; we are going to copy the one for development --- YOU SHOULD HAVE TWO COPIED LINKS (GIF & WOFF2)

5.) with vencord or any discord cilent modifier, go to settings and find where you can edit your cilent with CSS

6.) paste the code below:


--- FOR THE FONT ---



2.) go to raw.githack.com

3.) the very top bar where you can paste in a url, paste the link address there

4.) now you should have the smaller 2 bars below the top bar, one for production and one for development; we are going to copy the one for development

5.) with vencord or any discord cilent modifier, go to settings and find where you can edit your cilent with CSS

6.) paste the code below:

@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/BasicBackground/BasicBackground.css);

@import url(https://s4.ezgif.com/tmp/ezgif-4ba5667acc9196ec.gif);

@font-face {

	font-family: 'MyCustomDaFont';
	
	src: url('INSERT .WOFF2 FILE LINK FOR DEVELOPMENT HERE') format('woff2');
}

*, ::placeholder, body, button, input, select, textarea {

	font-family:'MyCustomDaFont', sans-serif;
	
}

:root {

	--transparencycolor:		0, 0, 0;			/* default: 0, 0, 0															*/
	
	--transparencyalpha:		0;				/* default: 0.15				(general darkness of the app)								*/
	
	--bordercolor:				0, 0, 0;			/* default: 0, 0, 0				(color of most borders/dividers)							*/
	
	--messagetransparency:		0.275;				/* default: 0.5					(additional shadows behind messages, set to 0 to remove boxes)				*/
	
	--guildchanneltransparency:	0.15;				/* default: 0.15				(additional darkness for guild/channel list)						*/
	
	--chatinputtransparency:	0.0;				/* default: 0.0					(additional darkness for chat input container)						*/
	
	--memberlisttransparency:	0.3;				/* default: 0.0					(additional darkness for member list)							*/
	
	--accentcolor:				193, 46, 55;			/* default: 190, 78, 180			(RGB-format - blurple: 88, 101, 242 bd-blue: 58, 113, 193)				*/
	
	
	--settingsicons:			1;				/* Use Settings Icons in User Settings: 1 = yes, 0 = no											*/
	
	--font: 					"MyCustomDaFont", "Noto Sans", sans-serif;						/* Allows for every text to be your font */
	
	--textshadow:				transparent;			/* default: transparent				(textshadow for text ontop of accentcolor nodes, ONLY accepts a color, no px)		*/
	
	
	--background:				url(INSERT .GIF FILE LINK FOR DEVELOPMENT HERE);	/* general background image					*/
	
	--backgroundposition:		center;				/* default: center				(position of background - values: [center/top/right/bottom/left])			*/
	
	--backgroundsize:			cover;				/* default: cover				(sizefit of background - values: [cover/contain/auto])					*/
	
	--backgroundblur:			0;				/* default: 0					(blur in px, only works when --background is set to an image)				*/

	
	--popout:					var(--background);		/* default: var(--background)			(change to use another background/color for modals/popouts)				*/
	
	--popoutposition:			var(--backgroundposition);	/* default: center				(position of popout - values: [center/top/right/bottom/left])				*/
	
	--popoutsize:				var(--backgroundsize);		/* default: cover				(sizefit of popout - values: [cover/contain/auto])					*/
	
	--popoutblur:				var(--backgroundblur);		/* default: 0					(blur in px, only works when --popout is set to an image)				*/
	
	
	--backdrop:				  rgba(0, 0, 0, 0.85);		/* default: rgba(0, 0, 0, 0.85)			(change to use another background/color for backdrops)					*/
	
	--backdropposition:		    center;				/* default: center				(position of backdrop - values: [center/top/right/bottom/left])				*/
	
	--backdropsize:				cover;				/* default: cover				(sizefit of backdrop - values: [cover/contain/auto])					*/
	
	--backdropblur:				0;				/* default: 0					(blur in px, only works when --backdrop is set to an image)				*/
	

	
	--textbrightest: 			255, 255, 255;			/* default: 255, 255, 255			(text color for the brightest texts)							*/
	
	--textbrighter: 			222, 222, 222;			/* default: 222, 222, 222			(text color for brighter texts)								*/
	
	--textbright: 				200, 200, 200;			/* default: 200, 200, 200			(text color for bright texts)								*/
	
	--textdark: 				160, 160, 160;			/* default: 160, 160, 160			(text color for dark texts)								*/
	
	--textdarker: 				125, 125, 125;			/* default: 125, 125, 125			(text color for darker texts)								*/
	
	--textdarkest: 				90, 90, 90;			/* default: 90, 90, 90				(text color for the darkest texts)							*/
	
	
	--version1_0_5:				none;				/* DO NOT CHANGE THIS VARIABLE , USED TO HIDE UPDATE NOTICE										*/
	
}

7.) see where it says " INSERT ... HERE " on lines 39 and 74?, replace that whole section of text with the development link BUT DO NOT REMOVE THESE SYMBOLS: (''), THIS IS THE SYNTAX FOR CSS AND IT WILL CAUSE A SYNTAX ERROR MEANING THE CODE WILL NOT WORK

8.) should work now! :D | sorry if its confusing but would you disappoint lilith

CREDITS TO https://www.youtube.com/watch?v=w4_I_ux1HM8&pp=ygUvaG93IHRvIGdldCBjdXN0b20gZm9udHMgb24gZGlzY29yZCB3aXRoIHZlbmNvcmQ%3D
