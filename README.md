# MyFirstApp\
## To build MyFirstApp using ios.\
### First App - Hello World\

#### Installing XCode from app store:\

*You a install XCode from app store as shown below.\

![1](https://user-images.githubusercontent.com/74371450/106769101-9ce4ca80-6662-11eb-97f8-0e1b31071110.jpg)

 ![2](https://user-images.githubusercontent.com/74371450/106769611-27c5c500-6663-11eb-833c-11c7bf80fc11.png)
  
#### Another way\
 
 ![3](https://user-images.githubusercontent.com/74371450/106769814-63608f00-6663-11eb-8cd7-417d33e61c37.jpg)


 
 
#### Creating MyFirstApp
* Start Xcode
*You should get a welcome screen with a choice to create a new project.
*Or menu: File | New | Project
 
 
iOS Application: Single View Application
Product name: MyFirstApp
Organization name: Your organization name (e.g., user)
• This will be used in a copyright notice that Xcode automatically creates.
Organization identifier: It preloads this with “reverse DNS” string, such as “com.cegepgim”
• xCode will combine the product name and organization identifier to create a unique bundle
identifier for your app.
Leave defaults:
• Language: Swift
• Device: iPhone
• Use Core Data: unchecked.
 
Next
Leave create local git repository unchecked.
Create.
xCode automatically creates the projects and files needed for MyFirstApp.
 
If needed to publish your project in the app store, one has to sign-in compulsory.
Below is the splash screen that is displayed first.
 
Below you can see the AppDelegate.swift screen


 
Now let’s make it interactive so our app does something
Drag and drop the Label on to the screen.
 
 
Click on the button and then hold down the control key.
Then click and drag from the button over to screen.
 
 
 
Import UIKit imports the UIKit framework which is the foundation of all iOS UI
class ViewController: UIViewController defines our class called ViewController.
UIViewController is the superclass (which is in UIKit, which is why we imported that)
 
Below is the myfirstapp
 
 
Initially “Hello CEGEP” is displayed.
Once is click on the button “Change the text”, it will change to “Hello Gaspe” as shown below.
 

