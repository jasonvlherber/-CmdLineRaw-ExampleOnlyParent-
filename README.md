# -CmdLineRaw-ExampleOnlyParent-
If Not StringInStr($CmdLineRaw, "/ExampleOnlyParent") Then         $GuiChild = GUICreate("GuiExample w/child (child)", 320, 280, 5, 5, $WS_CHILD, $WS_TABSTOP, $GuiMain)     EndIf
