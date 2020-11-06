## PyWebview
  
Includes modified files to add Edge Webview2 support to the **pywebview** python package.  https://github.com/r0x0r/pywebview
#### **New option**
gui='chromium'

### Requirements
A Webview2 Runtime needs to be installed. Installing one of the the following will provide the runtime.

* The **WebView2 Runtime**. https://developer.microsoft.com/en-us/microsoft-edge/webview2/
* Any Insider (non-stable) Microsoft Edge (Chromium) browser channel such as Beta, Dev or Canary.

The following DLL files need to be in the webview/lib folder.
* Microsoft.Web.WebView2.Core.dll
* Microsoft.Web.WebView2.WinForms.dll
* WebView2Loader.dll (x86 or x64)

The SDK DLL files are avaiable from here: https://www.nuget.org/packages/Microsoft.Web.WebView2/0.9.579-prerelease

**Package manager download**
```
# package manager
Install-Package Microsoft.Web.WebView2 -Version 0.9.579-prerelease
# .net cli
dotnet add package Microsoft.Web.WebView2 --version 0.9.579-prerelease
```
**Browser download** https://www.nuget.org/api/v2/package/Microsoft.Web.WebView2/0.9.579-prerelease save as **.zip** file.

The latest versions of the Webview2 SDK (88.0.674.0) will not work with the current *WebView2 Runtime* (86.0.622.63) or *Edge Beta* (87.0.664.24).
The .Net DLLs are only included in the prelease versions.

**Update:** The latest Webview2 SDK version 1.0.674-prerelease appears to work with the Runtime and Edge Beta, even though the release notes state that the minimum browser version needs to be at least 88.0.674.0.

**Webview2 SDK Release Notes** https://docs.microsoft.com/en-us/microsoft-edge/webview2/releasenotes

**Known Issues**
* New window is not supported


  
