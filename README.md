# Xcode-Snippets


## Error Message
#error("<#Message#>")


## Warning Message
#warning("<#Message#>")


## If Error Message
#if <#Statment#>
#error("<#Message#>")
#endif


## Mark
// MARK: - <#Section Heading#>


## TODO
// TODO:-  <#Section Heading#>


## FIXME
// FIXME:- <#Section Heading#>



## Using SwiftUI Preview With UIKIT
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
