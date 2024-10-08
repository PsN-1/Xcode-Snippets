# Xcode-Snippets


### Error Message
```swift
#error("<#Message#>")
```


### Warning Message
```swift
#warning("<#Message#>")
```

### If Error Message
```swift
#if <#Statment#>
#error("<#Message#>")
#endif
```

## Marks
### Mark
```swift
// MARK: - <#Section Heading#>
```

### TODO
```swift
// TODO:-  <#Section Heading#>
```


### FIXME
```swift
// FIXME:- <#Section Heading#>
```


## SwiftUI
### Using SwiftUI Preview With UIKIT
```swift
import SwiftUI
struct ViewControllerRepresentable: UIViewControllerRepresentable {
    func updateUIViewController(_ uiViewController: UIViewControllerType, context: Context) { }
    func makeUIViewController(context: Context) -> some UIViewController {
        UINavigationController(rootViewController: <#T##UIViewController#>())
    }
}

struct <#ViewController#>_Previews: PreviewProvider {
    static var previews: some SwiftUI.View {
        ViewControllerRepresentable()
            .edgesIgnoringSafeArea(.vertical)
    }
}
```
