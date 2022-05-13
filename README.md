# the-pop-up-Send
EndFunc Func _Next()     $iBlittingMethod += 1     If $iBlittingMethod = 4 Then $iBlittingMethod = 1 EndFunc Func _Exit()     _SDL_Quit()     Exit EndFunc $iMaxDelay = 10000 ; 10 secs $iActDelay = 0 WinWaitActive("File Upload") // enter the title of the pop up Send("Path of the file to enter")   // enter the path of the file to upload Send("{ENTER}") / press enter
