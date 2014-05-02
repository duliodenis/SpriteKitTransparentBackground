SpriteKit Transparent Background
================================

This is the sample project provided to Apple to illustrate the issue reported in Radar 16153326: SKView does not support a clearColor backgroundColor property.

Reported Issue:
The SpriteKit framework does not allow you to create a scene with a transparent background that can be placed on top of the UIKit view hierarchy. This limits using Particle Effects to SpriteKit only based apps.  Current UIKit apps that would like to add Particle Effects need to continue to use the Core Animation CAEmitterLayer class. This limits SpriteKit adoption for UIKit based apps.

### Support or Contact
Visit [ddApps.co](http://ddapps.co) to see more.
