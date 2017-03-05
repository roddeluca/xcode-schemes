#Xcode Schemes Example

Many times we have differents urls based on the environment that we are working on. So in this case, we can define differents `schemes` to run the app with the correct environment.

###Important: This works with AppDelegate that contains `@UIApplicationMain` annotation
![](images/app-delegate.png "App Delegate")


## Define Schemes

####1.	Go to Schemes
![](images/scheme.png "Schemes")

####2. Create a new one
![](images/new-scheme.png "New Scheme")

####3. Share it
![](images/share-scheme.png "Share Scheme")

####4. Create a new build configuration duplicating an existing one
![](images/new-configuration.png "New Build Configuration")

####5. Associate the new configuration with our new scheme
![](images/define-conf.png "Define Configuration")

####6. Define flags that you will use to determine the environmet in `Target -> Build Setting -> Swift Flags`
![](images/build-settings.png "Flags")