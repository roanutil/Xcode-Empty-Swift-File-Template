# Xcode Empty Swift File Template

A file template for Xcode that doesn't include `import Foundation`

## Why?

I don't want Foundation imported by default. If there's a better way to accomplish that, I'm not aware of it.

## Installation

Place `SwiftEmpty File.xctemplate` in the `~/Library/Developer/Xcode/Templates/File Templates/Custom/iOS/Source/` directory.

> You can probably use any platform directory inside `~/Library/Developer/Xcode/Templates/File Templates/Custom/` but I used `iOS` and the template is available for all platforms.

For me, the template has survived Xcode upgrades so far but would need to be re-applied in a fresh install of macOS.

## Customization

### Sort Order

The `SortOrder` xml key in `TemplateInfo.plist` can be changed to control how it's sorted relative to other templates.

### Name

Change the `.xctemplate` folder name should change the name shown in the Xcode UI.