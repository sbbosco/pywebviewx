### Required DLL files

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
**Browser download** https://www.nuget.org/api/v2/package/Microsoft.Web.WebView2/0.9.579-prerelease save as .zip file.

The latest versions of the Webview2 SDK (88.0.674.0) will not work with the current *WebView2 Runtime* (86.0.622.63) and *Edge Beta* (87.0.664.24).
The .Net DLLs are only included in the prelease versions.
**Webview2 SDK Release Notes** https://docs.microsoft.com/en-us/microsoft-edge/webview2/releasenotes

