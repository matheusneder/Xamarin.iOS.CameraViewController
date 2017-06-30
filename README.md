# Xamarin.iOS.CameraViewController

[ALCameraViewController](https://github.com/matheusneder/ALCameraViewController) bindings for Xamarin.iOS.

Xamarin.iOS.CameraViewController is a Xamarin.iOS binding to ALCameraViewController:
> A camera view controller with custom image picker and image cropping. Written in Swift.
>
> ![camera](https://cloud.githubusercontent.com/assets/932822/8455694/c61de812-2006-11e5-85c0-a57e3d980561.jpg)
> ![cropper](https://cloud.githubusercontent.com/assets/932822/8455697/c627ac44-2006-11e5-82be-7f96e73d9b1f.jpg)
> ![library](https://cloud.githubusercontent.com/assets/932822/8455695/c620ebb6-2006-11e5-9c61-75a81870c9de.jpg)
> ![permissions](https://cloud.githubusercontent.com/assets/932822/8455696/c62157fe-2006-11e5-958f-849cabf541ca.jpg)
>
> ### Features
> 
> - Front facing and rear facing camera support
> - Simple and clean look
> - Custom image picker with permission checking
> - Image cropping (square only)
> - Flash light support
>
> @AlexLittlejohn

## Installation

Just install [Xamarin.iOS.CameraViewController](https://www.nuget.org/packages/Xamarin.iOS.CameraViewController/) NuGet package.

## Contribute

### Build

First step is to build ALCameraViewController: On a mac with regular development tools for iOS plus Xamarin development (Xcode 8.3 and VS for Mac 7), just run `make` at the project's directory. It'll clone ALCameraViewController from github (from a fork of mine at https://github.com/matheusneder/ALCameraViewController) and build the framework.

Second step is to build the solution on Visual Studio. I built from VS 15.2 (2017).

To create a NuGet package: build the solution in Release mode and then, at project's directory, execute: `NuGet pack Xamarin.iOS.CameraViewController.csproj -Prop Configuration=Release`.
