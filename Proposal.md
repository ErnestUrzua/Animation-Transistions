# Animation-Transistions
## Define objective or goal
Create custom Core Animation layers to use for IOS or OSX in a test application.
		
## Problem statement
	
Whether we consciously know it or not, animation plays a big role in how we interface with the application. How something feels when we interact with it visually or physically evokes a response that can be pleasant  or off-putting when designed to do so. 
Core Animation is a graphics rendering and animation infrastructure available on both iOS and OS X that you use to animate the views and other visual elements of your app. Core Animation is used exclusively by IOS and OSX Developers, Although most will not need to interface with Core Animation, the option to have a finer grain of control over your applications animations is welcomed. 
			 
## Detailed goals
* create custom layers using Core Animation		
* Create a test application to utilize these animations
							
## Specification/ functions
### Requirements
* Must be able to switch views with a gesture.
* Must be able to switch views by pressing a button.
* Must minimize all windows by shaking
* Swiping left or right on a photo will transition to next one
* Swiping down will close current view and return to home
			
### Non functional requirements
  To be determined
		
## System Architecture
* Code editor | **Xcode 9.2**
* Programming Language | **Swift**
* Mobile OS | **IOS 11**
* OS | **OSX High Sierra**
		
## UI sketch
![GitHub Logo](/Assets/User Interface.png)

![GitHub Logo](/Assets/test app.png)

![GitHub Logo](/Assets/View Transisitions.png)
	
## Design structure/ architecture
We will be using the default architecture model as a basis for our application
![GitHub Logo](/Assets/Architecture.png)		 
### Detailed design
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
