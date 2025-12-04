# MyTestApp - Simple iOS Counter App

A minimal SwiftUI iOS application demonstrating basic concepts.

## Features
- Simple counter with increment/decrement buttons
- Reset functionality
- Clean, modern SwiftUI interface

## Requirements
- macOS with Xcode 14+ installed
- iOS 17.0+ deployment target

## Getting Started

### Option 1: Create Xcode Project (Recommended)
1. Open Xcode on macOS
2. Create new project: **File → New → Project**
3. Select **iOS → App**
4. Configure:
   - Product Name: `MyTestApp`
   - Interface: `SwiftUI`
   - Language: `Swift`
5. Replace generated files with files from `MyTestApp/` folder

### Option 2: Use Swift Package
Create the Xcode project structure using the provided source files.

## Project Structure
```
MyTestApp/
├── MyTestAppApp.swift    # App entry point
├── ContentView.swift     # Main UI view
└── Assets.xcassets/      # App assets (icons, colors)
```

## Key Concepts Demonstrated
- **@main** - App entry point attribute
- **@State** - SwiftUI state management
- **VStack/HStack** - Layout containers
- **Button** - User interaction
- **SF Symbols** - System icons (plus.circle.fill, minus.circle.fill)
