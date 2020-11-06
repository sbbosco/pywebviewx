## PyWebview
  
Includes modified files to add Edge Webview2 support to the **pywebview** python package.  https://github.com/r0x0r/pywebview
  
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
**Browser download**
https://www.nuget.org/api/v2/package/Microsoft.Web.WebView2/0.9.579-prerelease

https://docs.microsoft.com/en-us/microsoft-edge/webview2/releasenotes




  
