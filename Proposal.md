# Animation-Transistions
## Define objective or goal
Create custom Core Animation layers to use for IOS in a test application.
		
## Problem statement
	
Core Animation handles all graphic renderings and is the infrastructure that is used by Developers to create or manipulate visual objects. By default, Core Animation has preset layers that Developers can use to create an interactive application with little knowledge on how to transpose, rotate, or manipulate any graphical object to some degree. What I am going to achieve is creating a custom layer that can be called upon to be used in any IOS application. This Layer or layers will display certain characteristics that will enhance the user experience by improving upon or adding to the core layer functionality. Core Animation sits beneath AppKit and UIKit which is integrated tightly into the view workflows of Cocoa and Cocoa Touch. Core Animation has interfaces that extend the capabilities of layer views and give finer control over animations. Core Animation is a graphics rendering and animation infrastructure available on both iOS and OS X that you can use to animate the views and other visual elements of your application. Core Animation is used exclusively by IOS and OSX Developers, although most will not need to interface with Core Animation, the option to have a finer grain of control over your applications animations is welcomed. 

			 
## Detailed goals
* create custom layers using Core Animation		
* Create a test application to utilize these animations
							
## Specification/ functions
### Requirements
* Must be able to switch views with a gesture.
* Must be able to switch views by pressing a button.
* Swiping left or right on a photo will transition to next one

			
### Non functional requirements
  To be determined
		
## System Architecture
* Code editor | **Xcode 9.2**
* Programming Language | **Swift**
* Mobile OS | **IOS 11**
* OS | **OSX High Sierra**
		
## UI sketch

![test app](/Assets/test%20app.png)

![view transistions](/Assets/View%20Transisitions.png)
	
## Design structure/ architecture
We will be using the default architecture model as a basis for our application
![GitHub Logo](/Assets/Architecture.png)		 
### Detailed design
(Specify the layers and details) 
What do the layers do, they transform create automated animations to use in the app.
You can use Core Animations api to get more detail about it.
Switching views,  in general swiping is usually quick and linear in nature, I want to achieve a classic animation technique of “fast out slow in”  this usually conveys a soft cushion effect that is.
By default Core Animation implements its behavior in layers using action objects.
An action object is  one that conforms to the CAAction protocol, this protocol defines some relevant behavior to perform on a  layer. Action objects can be triggered by many ways; such as, changing the value of a layers property, a layer has become visible, a layer has been removed, or the layer is involved in a transition animation. We’ll be using CAAnimation objects to manipulate layer properties to get the desired effect needed. 
Action Objects must be installed on a layer first before we can use them. Once installed when an event occurs it will actionForKey: method and search for the action associated with the key, and key is usually named according to the action being performed. 
Name of layers that will be used for this project are Flip, fade, and bounce. 

1. Algorithim 
			NA
2. Data structure
  Normally UIdocument is used to handle external data that needs to be processed and used in the UIviewController.
			For our purposes we will not need to use as we focused entirely on user input.
3. DB

## Implementation
### Testing

For testing of the application an iphone simulator will be used as well as an Iphone 5s and 7. This is handled all within Xcode. 		
		
## Conclusion
It is still unknown how far this project will go in terms of depth and scope, but the basic Idea is to create and learn more about how the user view is generated and how to improve upon the experience of it. 
		
## Reference
1. https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreAnimation_guide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40004514-CH1-SW1
2. https://developer.apple.com/library/content/documentation/General/Conceptual/DevPedia-CocoaCore/Cocoa.html
3. https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/index.html#//apple_ref/doc/uid/TP40007457
4. https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/PresentingaViewController.html#//apple_ref/doc/uid/TP40007457-CH14-SW1
5. https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/CustomizingtheTransitionAnimations.html#//apple_ref/doc/uid/TP40007457-CH16-SW1
6. https://developer.apple.com/library/content/samplecode/ViewTransitions/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007411Animation
8. https://www.amazon.com/Illusion-Life-Disney-Animation/dp/0786860707
9. https://developer.apple.com/ios/human-interface-guidelines/visual-design/animation/
10. https://developer.apple.com/ios/human-interface-guidelines/overview/themes/
11. https://www.raywenderlich.com/170144/custom-uiviewcontroller-transitions-getting-started

## Appendix
