# WinWaitActive
Send("{ENTER}") WinWait("TestRun","") If Not WinActive("TestRun","") Then WinActivate("TestRun","") WinWaitActive("TestRun","") Send("{ENTER}") WinWait("TestRun","") If Not WinActive("TestRun","") Then WinActivate("TestRun","") WinWaitActive("TestRun","") Send($ProgramFiles &amp; "TestRun{ENTER}") WinWait("TestRun ","")
