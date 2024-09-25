# Capture Vision
This package is a compound of [DocumentScannerSDK](https://www.nuget.org/packages/DocumentScannerSDK) and [MrzScannerSDK](https://www.nuget.org/packages/MrzScannerSDK).


## License Activation
Click [here](https://www.dynamsoft.com/customer/license/trialLicense/?product=dcv&package=cross-platform) to get a valid license key.

## Supported Platforms
- Windows (x64)
- Linux (x64)
- Android
- iOS
    
## Building NuGet Package from Source Code

```bash
# build dll for desktop
cd desktop
dotnet build --configuration Release

# build dll for android
cd android
dotnet build --configuration Release

# build dll for ios
cd ios
dotnet build --configuration Release

# build nuget package
nuget pack .\CaptureVision.nuspec
```
