A SwiftUI and Metal package for bautiful animated blob gradients.

## Preview

<video src="https://github.com/user-attachments/assets/cb401e0c-29ba-41df-926d-8d02283726c3" width="250"></video>

## Usage

Install the BlobGradient package using Swift Package Manager:
```
https://github.com/tedsomething/blob-gradient
```

Place `BlobGradientView` in your app: 

```swiftui
import SwiftUI
import BlogGradient

struct ContentView: View {
    var body: some View {
        BlobGradientView(
            colors: [.blue, .pink, .yellow, .green],
            highlights: [.blue, .pink, .yellow, .green]
        )
        .background(.green)
    }
}

```

## Why?

Who doesn't love a gradient? I use these in my projects. I got the original idea from [FluidGradient](https://github.com/Cindori/FluidGradient/), but it was made in CoreAnimaiton while this is Metal.

## Credit

- [FluidGradient](https://github.com/Cindori/FluidGradient/)
