# SwiftUIShakeGesture

Simply detect **shake gestures in SwiftUI**.

![Preview](https://github.com/globulus/swiftui-shake-gesture/blob/main/Images/preview.gif?raw=true)

## Installation

This component is distributed as a **Swift package**.

## Sample usage

```swift
struct ShakeTest: View {
  @State private var text = "Shake me!"
    
  var body: some View {
    Text(text)
      .onShake { // ADD THIS
        text = "Shaken at \(Date())"
      }
  }
}
```

## Recipe

Check out [this recipe](https://swiftuirecipes.com/blog/shake-gesture-in-swiftui) for in-depth description of the component and its code. Check out [SwiftUIRecipes.com](https://swiftuirecipes.com) for more **SwiftUI recipes**!
