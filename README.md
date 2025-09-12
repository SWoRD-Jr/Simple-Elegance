# Simple-Elegance
A [YASB](https://github.com/amnweb/yasb) theme that looks clean and is easy to configure.

![Simple-Elegance](https://i.imgur.com/0gM1SZR.png "Theme Screenshot")

To customize colors & font simply edit the first section of the CSS file and it will apply to the rest of theme without running through all the code. You may need to adjust font sizes depending on the font used and your screen resolution to make everything fit.

##### Latest Changes:
- *Added Config & CSS for missing wallpapers widget and ai-chat*
- *Changed the bar layout to floating style*

I recommend this theme be used with [Windhawk](https://github.com/ramensoftware/windhawk) Taskbar Styler mod.
In the Advanced tab of Taskbar Styler paste the following code:
```
{
"theme":"DockLike",
"resourceVariables[0].variableKey":"",
"resourceVariables[0].value":"",
"styleConstants[0]":"",
"controlStyles[0].target":"Taskbar.TaskListLabeledButtonPanel@RunningIndicatorStates > Rectangle#RunningIndicator",
"controlStyles[0].styles[0]":"Height=2",
"controlStyles[0].styles[1]":"Fill@ActiveRunningIndicator=#FDFF3B",
"controlStyles[0].styles[2]":"Width@ActiveRunningIndicator=26",
"controlStyles[0].styles[3]":"Width=12",
"controlStyles[0].styles[4]":"Fill=white",
"controlStyles[1].target":"Grid#RootGrid",
"controlStyles[1].styles[0]":"Background=#960B0B0B",
"controlStyles[2].target":"Grid#SystemTrayFrameGrid",
"controlStyles[2].styles[0]":"Background=#960B0B0B",
"controlStyles[2].styles[1]":"Margin=-4,-8,-4,-8",
"controlStyles[2].styles[2]":"BorderThickness=12,18,8,10",
"controlStyles[2].styles[3]":"CornerRadius=10,10,10,10",
"controlStyles[2].styles[4]":"BackgroundSizing=InnerBorderEdge",
"controlStyles[3].target":"Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Border#BackgroundElement",
"controlStyles[3].styles[0]":"Background:=<ImageBrush Stretch=\"Uniform\" ImageSource=\"https://i.imgur.com/5Sv2f5n.png\" />",
"controlStyles[4].target":"Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
"controlStyles[4].styles[0]":"Visibility=Collapsed",
"controlStyles[5].target":"Taskbar.TaskListButtonPanel@CommonStates > Border#BackgroundElement",
"controlStyles[5].styles[0]":"CornerRadius=4",
"controlStyles[6].target":"Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
"controlStyles[6].styles[0]":"Margin=0,0,0,2",
"controlStyles[6].styles[1]":"CornerRadius=4,4,4,4",
"controlStyles[6].styles[2]":"Padding=4,0,4,0",
"controlStyles[7].target":"Taskbar.TaskbarFrame",
"controlStyles[7].styles[0]":"Width=Auto",
"controlStyles[7].styles[1]":"HorizontalAlignment=Right",
"controlStyles[7].styles[2]":"Margin=0,0,0,0",
"controlStyles[7].styles[3]":"Transform3D:=<CompositeTransform3D TranslateX=\\\"-860\\\"/>",
"controlStyles[8].target":"Taskbar.TaskbarFrame > Grid#RootGrid > Taskbar.TaskbarBackground > Grid > Rectangle#BackgroundFill",
"controlStyles[8].styles[0]":"Visibility=Collapsed",
"controlStyles[9].target":"Rectangle#BackgroundStroke",
"controlStyles[9].styles[0]":"Visibility=Collapsed",
"controlStyles[10].target":"Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
"controlStyles[10].styles[0]":"Margin=0",
"controlStyles[11].target":"SystemTray.ChevronIconView",
"controlStyles[11].styles[0]":"Padding=0",
"controlStyles[12].target":"SystemTray.NotifyIconView#NotifyItemIcon",
"controlStyles[12].styles[0]":"Padding=0",
"controlStyles[13].target":"SystemTray.OmniButton",
"controlStyles[13].styles[0]":"Padding=0",
"controlStyles[14].target":"SystemTray.CopilotIcon",
"controlStyles[14].styles[0]":"Padding=0",
"controlStyles[15].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid",
"controlStyles[15].styles[0]":"Padding=4,0,4,0",
"controlStyles[16].target":"SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
"controlStyles[16].styles[0]":"Padding=0",
"controlStyles[17].target":"SystemTray.StackListView#IconStack > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon",
"controlStyles[17].styles[0]":"Padding=0",
"controlStyles[18].target":"Taskbar.Gripper#GripperControl",
"controlStyles[18].styles[0]":"Width=Auto",
"controlStyles[18].styles[1]":"MinWidth=24",
"controlStyles[19].target":"SystemTray.SystemTrayFrame",
"controlStyles[19].styles[0]":"HorizontalAlignment=Right",
"controlStyles[19].styles[1]":"Width=Auto",
"controlStyles[19].styles[2]":"/*Margin=-3,-4,0,-4*/",
"controlStyles[0].styles[5]":"Margin= 0,0,0,0"
}
```
![Screenshot](https://i.imgur.com/jb1wV8r.png "Screenshot")


Hope you enjoy!
