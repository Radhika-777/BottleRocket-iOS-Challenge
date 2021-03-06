# BOOTLE ROCKET iOS CODE CHALLENGE

This project is an app developed according to _Bottle Rocket iOS Engineering Test_ Document. It does not contains any third party library and was built using vanilla Swift with UIKit.

<img src="/img/iPhone-1.png" alt="iPhone-1.png" width="250">
<img src="/img/iPhone-2.png" alt="iPhone-2.png" width="250">
<img src="/img/iPhone-3.png" alt="iPhone-3.png" width="250">

<img src="/img/iPad-1.png" alt="iPad-1.png" width="250">
<img src="/img/iPad-2.png" alt="iPad-2.png" width="250">
<img src="/img/iPad-3.png" alt="iPad-3.png" width="250">

## Environment

- Xcode 10.2.1 or higher
- Macos Mojave 10.14.6 or higher
- iOS 12.2 or higher
- Built for iPhone and iPad

## Structure

The project is organized in the following structure:

- Models: Contains all the structs and classes for data modeling
- UI: Contains UI resources such as the storyboard file, the assets catalog and LaunchScreen
- Extensions: Contains extensions for UILabel, ViewController, UIImageView
- Cells: Contains one Cell for UICollectionViews
- Controllers: Contains Base and Custom controllers
- Utils: Contains the _Service_ singleton class for networking and the Font and Color structs for UICustomization

The project uses the storyboard in order to use _AutoLayout_ as requested via the Interface Builder, however the entry point of the app is UITabBarViewController and not the _Main.storyboard_

```Swift
    let tabBar = TabBarViewController()
    window = UIWindow(frame: UIScreen.main.bounds)
    window?.rootViewController = tabBar
    window?.makeKeyAndVisible()
```
