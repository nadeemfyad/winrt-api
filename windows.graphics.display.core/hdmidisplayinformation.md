---
-api-id: T:Windows.Graphics.Display.Core.HdmiDisplayInformation
-api-type: winrt class
---

<!-- Class syntax.
public class HdmiDisplayInformation 
-->

# Windows.Graphics.Display.Core.HdmiDisplayInformation
// Get the HdmiDisplayInformation instance
var dataHDMI = HdmiDisplayInformation.GetForCurrentView();
if (dataHDMI != null)
{
   // Get current display mode
   var currentMode = dataHDMI.GetCurrentDisplayMode();
   // Get the supported display modes as a List of HdmiDisplayModes
   var supportedModesList = dataHDMI.GetSupportedDisplayModes().ToList();
}
else
{
   // The app can't find any HDMI output
}


