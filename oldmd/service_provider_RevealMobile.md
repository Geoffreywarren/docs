
## Reveal Mobile

Reveal Mobile helps mobile app publishers use location data, derived from both lat/long and Bluetooth beacons, to generate more advertising revenue and build better products. 

### Supported Features

* Bluetooth Beacon Proximity Data and Latitude/Longitude Data to Support Geotargeting and Geofencing

### Prerequisites

In order to configure Reveal Mobile in the mParticle platform, you will need to perform the following setup steps:

1.  Include the Reveal Mobile Kit with the mParticle SDK in your app
2.  Setup an account with Reveal Mobile at <https://www.revealmobile.com> in order to obtain your API Key which can be found in the Dashboard.

### Reveal Mobile Kit Integration

mParticle's Reveal Mobile integration requires that you add the Reveal Mobile kit to your iOS or Android app, and the mParticle SDK will initialize and automatically map mParticle method calls directly onto Reveal Mobile method calls. This approach means that *every feature* of the Reveal Mobile SDKs are supported, as if the app had integrated Reveal Mobile directly. The source code for each kit is available if you would like to learn exactly how the method mapping occurs:

* [iOS](https://github.com/mparticle-integrations/mparticle-apple-integration-revealmobile)
* [Android](https://github.com/mparticle-integrations/mparticle-android-integration-revealmobile)

Add the Reveal Mobile Kit to your iOS or Android app. See the Cocoapods and Gradle examples to the right, and reference the [Apple SDK](https://github.com/mParticle/mparticle-apple-sdk) and [Android SDK](https://github.com/mParticle/mparticle-android-sdk) GitHub pages to read more about kits.

~~~objc
//Sample Podfile
target '<Your Target>' do
    pod 'mParticle-RevealMobile', '~> 6'
end
~~~

~~~java
//Sample build.gradle
dependencies {
    compile ('com.mparticle:android-revealmobile-kit:4.+')
}
~~~   