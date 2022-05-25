# SwiftLintPlugin

SwiftPM build tool plugin for SwiftLint

## Usage

### Package.swift

```swift
dependencies: [
    .package(url: "https://github.com/luupsc/SwiftPackage-Plugins", branch: "main"),
],
targets: [
    .target(
        name: "App",
        plugins: [
            .plugin(name: "SwiftLintPlugin", package: "SwiftLintPlugin"),
        ]
    )
]
```
