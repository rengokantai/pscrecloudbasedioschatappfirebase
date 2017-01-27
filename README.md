# pscrecloudbasedioschatappfirebase
##3. Connecting Your App to Firebase
###1 Connecting Your App to Firebase
```
pod init
```
add
```
pod 'Firebase/Core'
```
then
```
pod install
```
then AppDelegate.swift
```
import Firebase
FIRAPP.configure()
```

###2 Installing CocoaPods

##9. Remote Config Updating Your App on the Fly
###2 Preparing for Remote Config
```
pod 'Firebase/RemoteConfig'
```

RemoteConfigManager.swift
```
import FirebaseRemoteConfig
class RemoteConfigManager: NSObject{
  
}
```

###3 Settings Defaults
####03:20
```
RemoteConfigManager.remoteConfigValues["loginButton"]=remote["loginButton"]
```
