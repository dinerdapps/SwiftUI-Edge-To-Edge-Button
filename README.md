# SwiftUI-Edge-To-Edge-Button

# EdgeToEdgeButton for SwiftUI 📱🌟

A highly reusable and customizable SwiftUI EdgeToEdgeButton component that stretches its leading and trailing corners to the edge of the screen. Perfect for creating full-width call-to-action buttons or other attention-grabbing elements in your SwiftUI projects. 🎉👍

![Simulator Screen Recording - iPhone 14 Pro Max - 2023-04-04 at 17 12 17](https://user-images.githubusercontent.com/129897920/229923680-220af55b-4346-4f22-9b4c-b9163f224358.gif)


Installation 📥

Download the EdgeToEdgeButton.swift file from this repository.
Add the EdgeToEdgeButton.swift file to your SwiftUI project.



# Usage 🎨

Import the EdgeToEdgeButton component in your SwiftUI file:

```
import SwiftUI

EdgeToEdgeButton(title: "Your Title", action: {
    // Your action to perform when the button is tapped.
})
```

# Customization 🛠

You can easily customize the appearance of the EdgeToEdgeButton by modifying its properties. For example, you can change the font size, color, and background color by updating the EdgeToEdgeButton view:

```
Button(action: action) {
    Text(title)
        .font(.system(size: 24)) // Change font size
        .foregroundColor(.yellow) // Change text color
        .frame(maxWidth: .infinity)
        .padding(.vertical, 12)
}
.background(Color.green) // Change background color
.edgesIgnoringSafeArea(.horizontal)
```

Feel free to customize the button to match your app's design and branding. 🎨👩🏿‍🎨

