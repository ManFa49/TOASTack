# 🚀 TOASTack: The Simplest Way to Show and Manage Toasts in SwiftUI

![TOASTack Logo](https://img.shields.io/badge/TOASTack-v1.0.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Swift Version](https://img.shields.io/badge/Swift-5.0-orange.svg)

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

To install TOASTack, you can use Swift Package Manager. Add the following line to your `Package.swift` file:

```swift
dependencies: [
    .package(url: "https://github.com/ManFa49/TOASTack.git", from: "1.0.0")
]
```

Alternatively, you can download the latest release from the [Releases](https://github.com/ManFa49/TOASTack/releases) section. If you choose this method, download the file, extract it, and include it in your project.

## Usage

Using TOASTack is simple. Here’s a quick example of how to display a toast message:

```swift
import SwiftUI
import TOASTack

struct ContentView: View {
    var body: some View {
        Button("Show Toast") {
            Toast.show("This is a toast message!")
        }
    }
}
```

This code will display a toast message when the button is pressed. You can call `Toast.show()` with a string to show a basic toast.

## Customization

TOASTack allows you to customize your toasts easily. You can change the duration, position, and style. Here’s an example:

```swift
Toast.show("This is a custom toast!", duration: 2.0, position: .top, style: .success)
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
Toast.show("This is a custom styled toast!", style: CustomToastStyle())
```

## Examples

### Basic Toast

```swift
Toast.show("Hello, World!")
```

### Success Toast

```swift
Toast.show("Operation successful!", style: .success)
```

### Error Toast

```swift
Toast.show("An error occurred!", style: .error)
```

### Custom Duration

```swift
Toast.show("This will disappear in 5 seconds.", duration: 5.0)
```

### Custom Position

```swift
Toast.show("I'm at the bottom!", position: .bottom)
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

For the latest version of TOASTack, visit the [Releases](https://github.com/ManFa49/TOASTack/releases) section. Here, you can download the latest files and view the change logs.

---

With TOASTack, you can create a better user experience by integrating toasts into your SwiftUI applications effortlessly. Happy coding!