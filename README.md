# Swift-Factory-Design-Pattern
An Xcode 9 project, written in Swift 4, demonstrating how to implement the factory method design pattern.

In this repo and [accompanying tutorial](), I explain the _factory method_ design pattern, with which you can create very useful objects without directly calling class constructors and without knowing anything about the class(es) or class hierarchy that your factory method is instantiating. You get a lot of bang for cheap. You get functionality and UI (if applicable) with a minimal amount of code.

Here's an example of the app from this repo working:

![alt text][logo1]

[logo1]: http://iosbrain.com/wp-content/uploads/2018/07/Factory_Method.gif "Factory Method"

## Xcode 9 project settings
**To get this project running on the Simulator or a physical device (iPhone, iPad)**, go to the following locations in Xcode and make the suggested changes:

1. Project Navigator -> [Project Name] -> Targets List -> TARGETS -> [Target Name] -> General -> Signing
- [ ] Tick the "Automatically manage signing" box
- [ ] Select a valid name from the "Team" dropdown
  
2. Project Navigator -> [Project Name] -> Targets List -> TARGETS -> [Target Name] -> General -> Identity
- [ ] Change the "com.yourDomainNameHere" portion of the value in the "Bundle Identifier" text field to your real reverse domain name (i.e., "com.yourRealDomainName.Project-Name").

