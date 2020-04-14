SendMode Input

1::Reload

;mage switch
~d::
	Send {F1}
	MouseGetPos, x ,y

	;-----------------CHECK CLOTHES---------------------
	PixelSearch, colourx, coloury, 985, 674, 1050, 730, 0xAA9E9E, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourx%, %coloury% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, coloura, colours, 1061, 735, 1132, 798, 0xAA9E9E, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %coloura%, %colours% Left, 1 	; Click on it.						
	sleep, 22
	}

	PixelSearch, colourc, colourv, 1060, 657, 1141, 728, 0xAA9E9E, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourc%, %colourv% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colourb, colourn, 985, 740, 1045, 806, 0xAA9E9E, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourb%, %colourn% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	;----------------------CHECK WEAPON1--------------------------
	
	PixelSearch, colourxx, colouryy, 984, 657, 1054, 728, 0x1E1126, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourxx%, %colouryy% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colouraa, colourss, 1061, 735, 1132, 798, 0x1E1126, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colouraa%, %colourss% Left, 1 	; Click on it.						
	sleep, 22
	}

	PixelSearch, colourcc, colourvv, 1060, 657, 1141, 728, 0x1E1126, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourcc%, %colourvv% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colourbbb, colournnn, 985, 740, 1045, 806, 0x1E1126, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourbbb%, %colournnn% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	Send {F2}
	Sleep, 40
	
	;augury
	PixelSearch, colourng, colourmg, 1164, 749, 1226, 799, 0xB9A56D, 0, Fast RGB 

	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Click, 1195, 778
	}
	IF ErrorLevel = 0 	; IF Found.	
	{					
	}
	Send {F3}
	Sleep, 25
	Click, 1003, 806
	Sleep, 15
	MouseMove, x, y
	Sleep, 40
	Click, x, y
	Send {F1}
return

;range switch
~s::
	Send {F1}
	MouseGetPos, x ,y
	;-----------------CHECK CLOTHES---------------------
	PixelSearch, colourxxx, colouryyy, 985, 674, 1050, 730, 0x181414, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourxxx%, %colouryyy% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colouraaa, coloursss, 1061, 735, 1132, 798, 0x181414, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colouraaa%, %coloursss% Left, 1 	; Click on it.						
	sleep, 22
	}

	PixelSearch, colourccc, colourvvv, 1060, 657, 1141, 728, 0x181414, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourccc%, %colourvvv% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colourbbb, colournnn, 985, 740, 1045, 806, 0x181414, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourbbb%, %colournnn% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	
	;----------------------CHECK WEAPON1--------------------------
	
	PixelSearch, colourxj, colouryj, 984, 657, 1054, 728, 0x33444B, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourxj%, %colouryj% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colouraj, coloursj, 1061, 735, 1132, 798, 0x33444B, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colouraj%, %coloursj% Left, 1 	; Click on it.						
	sleep, 22
	}

	PixelSearch, colourcj, colourvj, 1060, 657, 1141, 728, 0x33444B, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourcj%, %colourvj% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	PixelSearch, colourbjj, colournjj, 985, 740, 1045, 806, 0x33444B, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourbjj%, %colournjj% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	Send {F2}
	Sleep, 40
	;rigour
	PixelSearch, colournjjj, colourmjjj, 1104, 745, 1157, 798, 0xB9A56D, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Click, 1131, 775
	}
	IF ErrorLevel = 0 	; IF Found.	
	{					
	}
	Send {F1}
	MouseMove, x , y
	Sleep, 120
	Click, x, y
return


~a::
   
	Send {F1}
	MouseGetPos, x ,y
	
	
	;----------------------CHECK WEAPON1--------------------------
	
	Click, 1017, 455
	sleep, 5
	PixelSearch, colourxxxx, colouryyyy, 984, 659, 1140, 806, 0x4C4646, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Send {b}
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	Click, %colourxxxx%, %colouryyyy% Left, 1 	; Click on it.						
	sleep, 22
	}
	
	Send {F2}
	Sleep, 65
	;piety
	PixelSearch, colournnnn, colourmmmm, 1035, 752, 1093, 797, 0xB9A56D, 0, Fast RGB 
	IF ErrorLevel = 1 	; IF NOTFound.	
	{
	Click, 1065, 775
	}
	IF ErrorLevel = 0 	; IF Found.	
	{
	}
	;Spec
	Send {F4}
	Sleep, 60
	Loop {
	
		;looking for green
		PixelSearch, colourkkkk, colourllll, 1007, 777, 1036, 792, 0x397D3B, 0, Fast RGB 
		IF ErrorLevel = 1 	; IF NOTFound.	
		{
		Sleep, 5
		}
		IF ErrorLevel = 0 	; IF Found.	
		{
		Click, %colourkkkk%, %colourllll% Left, 1 	; Click on it.						
		sleep, 22
		Send {F1}
		MouseMove, x, y
		return
		}
		
		;looking for red
		PixelSearch, colouryyyy, colournnnnn, 1007, 777, 1036, 792, 0x730606, 0, Fast RGB 
		IF ErrorLevel = 1 	; IF NOTFound.	
		{
		Sleep, 5
		}
		IF ErrorLevel = 0 	; IF Found.	
		{
		Send {F1}
		MouseMove, x, y
		return
		}	
	}
		

e::
	MouseGetPos, x, y
	Send {F2}
	Sleep, 28
	Click, 1063, 643
	Sleep, 28
	MouseMove, x , y
	Send {F1}
	return
	
w::
	MouseGetPos, x, y
	Send {F2}
	Sleep, 28
	Click, 1130, 643
	Sleep, 28
	MouseMove, x , y
	Send {F1}
	return

q::
	MouseGetPos, x, y
	Send {F2}
	Sleep, 28
	Click, 1193, 643
	Sleep, 28
	MouseMove, x , y
	Send {F1}
	return
	
tab::
	while getKeyState("tab", "p") {
		Send {F2}
	}
	Send {F1}
	return



