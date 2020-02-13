# Connect for iOS

## Overview

Connect.framework provides a fast way to embed the Connect flow in your iOS application. For examples of the framework in action, please head over to the examples repository.

## Integration
1. Add Connect.framework to your project, either with CocoaPods or manually
2. Import Connect
3. Instantiate a ConnectViewConfig object, and provide the Connect URL & loaded, done, cancel, and error callback functions.
4. Instantiate a ConnectViewController and provide the ConnectViewConfig when calling its load method.
5. Add & Remove the ConnectViewController's view where desired -- typically in the loaded and done callbacks.
