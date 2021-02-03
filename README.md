# MyFirstApp&nbsp;
## To build MyFirstApp using ios.&nbsp;
### First App - Hello World&nbsp;

#### Installing XCode from app store:&nbsp;

*You a install XCode from app store as shown below.<br />

![1](https://user-images.githubusercontent.com/74371450/106769101-9ce4ca80-6662-11eb-97f8-0e1b31071110.jpg)

 ![2](https://user-images.githubusercontent.com/74371450/106769611-27c5c500-6663-11eb-833c-11c7bf80fc11.png)
  
#### Another way&nbsp;
 
 ![3](https://user-images.githubusercontent.com/74371450/106769814-63608f00-6663-11eb-8cd7-417d33e61c37.jpg)


 
 
#### Creating MyFirstApp&nbsp;

Start Xcode<br />
You should get a welcome screen with a choice to create a new project.<br />
Or menu: File | New | Project<br />
 
 
iOS Application: Single View Application<br />
Product name: MyFirstApp<br />
Organization name: Your organization name (e.g., user)<br />
• This will be used in a copyright notice that Xcode automatically creates.<br />
Organization identifier: It preloads this with “reverse DNS” string, such as “com.cegepgim”<br />
• xCode will combine the product name and organization identifier to create a unique bundle<br />
identifier for your app.<br />
Leave defaults:<br />
• Language: Swift<br />
• Device: iPhone<br />
• Use Core Data: unchecked.<br />
 
Next<br />
Leave create local git repository unchecked.<br />
Create.<br />
xCode automatically creates the projects and files needed for MyFirstApp.<br />
 
If needed to publish your project in the app store, one has to sign-in compulsory.<br />
Below is the splash screen that is displayed first.<br />
 
Below you can see the AppDelegate.swift screen<br />


 
Now let’s make it interactive so our app does something<br />
Drag and drop the Label on to the screen.<br />
 
 
Click on the button and then hold down the control key.<br />
Then click and drag from the button over to screen.<br />
 
 
 
Import UIKit imports the UIKit framework which is the foundation of all iOS UI<br />
class ViewController: UIViewController defines our class called ViewController.<br />
UIViewController is the superclass (which is in UIKit, which is why we imported that)<br />
 
Below is the myfirstapp<br />
 
 
Initially “Hello CEGEP” is displayed.<br />
Once is click on the button “Change the text”, it will change to “Hello Gaspe” as shown below.<br />
 

