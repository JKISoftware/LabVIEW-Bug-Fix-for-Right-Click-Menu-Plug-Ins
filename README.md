# LabVIEW-Bug-Fix-for-Right-Click-Menu-Plug-Ins
This package resolves an intermittent (race condition) issue where right-click operations implemented in G sometimes do not work (but when they try to reproduce the issue, everything works fine).

[![Install](https://user-images.githubusercontent.com/381432/99444221-c4808e00-28d0-11eb-9d30-704b41255e24.png)](https://www.vipm.io/package/ni_patch_labview_right_click_plugin_bugfix/)

This package replaces the file located here (and backs up the original by adding a ".orig" suffix to the orginal filename):

<LabVIEW>\resource\plugins\PopupMenus\support\Call Popup PlugIn Execution VI.vi

Note: the original source of this file was posted by NI here:

https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/Bug-Fix-for-ALL-Right-Click-Menu-Plug-Ins-LV2015-to-2019/ta-p/4016064

Uninstalling the package will restore the original file.

Note: This issue will be officially fixed in LabVIEW 2020 (which is why this package is only compatible with LabVIEW 2015-2019).   NI may officially patch older versions, making this package unnessesary. Until then, this package should be used to apply the fix.
