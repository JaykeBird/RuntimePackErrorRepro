Minimum code reproduction of an error I've been encountering in Visual Studio, to go along with my submitted bug report [dotnet/sdk#29913](https://github.com/dotnet/sdk/issues/29913).

### Error I've been getting

```
Severity	Code	Description	Project	File	Line	Suppression State
Error	NETSDK1082	There was no runtime pack for Microsoft.WindowsDesktop.App.WPF available for the specified RuntimeIdentifier 'win10-arm-aot'.	ReferencerLibrary	C:\Program Files\dotnet\sdk\7.0.102\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.FrameworkReferenceResolution.targets	448	
Error	NETSDK1082	There was no runtime pack for Microsoft.WindowsDesktop.App.WPF available for the specified RuntimeIdentifier 'win10-arm'.	ReferencerLibrary	C:\Program Files\dotnet\sdk\7.0.102\Sdks\Microsoft.NET.Sdk\targets\Microsoft.NET.Sdk.FrameworkReferenceResolution.targets	448	
```
