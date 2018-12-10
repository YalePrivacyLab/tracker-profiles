# Tracking Mobile Trackers
#### A [Yale Privacy Lab]( https://privacylab.yale.edu) Tech Primer [Guide]

###### Share: [privacylab.yale.edu/tmt](https://privacylab.yale.edu/tmt)

###### [@YalePrivacyLab](https://twitter.com/YalePrivacyLab) | [privacylab@mastodon.social](https://mastodon.social/@privacylab)

###### Presented by Sean O'Brien

----

## Are you worried that your phone is listening to you?

## That it is tracking your movements?

----

### You are being tracked by your phone in some way.  This primer [guide] will help explain and offer some solutions.

----

###  Our phones are full of naughty apps.

----

### At Yale Privacy Lab, we help identify  mobile trackers, code that runs inside  apps without your knowledge or consent.

----

# What Are Trackers?

* We use the term **trackers** broadly, to encompass traditional advertisement surveillance, analytics, behavioral and location tracking, as well as _developer tools_ such as crash reporters.

* We're talking about trackers bundled for app developers as **Software Development Kits** (SDKs) though there are also other ways to track users.

----

# We also focus on proximity and location tracking.

### Trackers that use bluetooth and near-ultrasonic/ultrasonic signals are some of the worst examples.

----

# What About Apple?

We'll be talking about **[Android apps in Google Play](https://www.wired.com/story/android-users-to-avoid-malware-ditch-googles-app-store/)**.

Many of the same companies distributing Google Play apps **also distribute apps via Apple**, and tracker companies openly advertise SDKs compatible with multiple platforms.

Thus, advertising trackers may be concurrently packaged for Android **and iOS**, as well as more obscure mobile platforms.

----

# Digging Deep

* To really understand a specific app and privacy or security concerns, it takes **network analysis**.

* **App permissions** are a big indicator something might be wrong (RECORD_AUDIO etc.)

**Be careful accepting permissions when you install an app!**

----

### **We'll show you an easy way to detect tracker SDKs without needing to know anything about code, via the [εxodus platform](https://reports.exodus-privacy.eu.org).**

----

## reports.exodus-privacy.eu.org

##### εxodus scans Android apps in Google Play.

##### Anyone can scan an app via a slick [fancy] Web UI

----

# Detecting Tracker SDKs

* εxodus scanner does **static analysis** of Android APKs to find  signatures in embedded classes.

* Without εxodus, you can make educated guesses by looking at the **Android manifest** XML and classes* **DEX** files.

* Remember, there are legal restrictions on static analysis of iOS apps, but many of these apps also have trackers (more on that later).

----

[okay to leave this part out]

#### [Cory Doctorow](https://boingboing.net/2017/11/25/la-la-la-cant-hear-you.html) on the subject:

“iOS is DRM-locked and **it's a felony** – punishable by a 5-year prison sentence and a $500,000 fine for a first offense in the USA under DMCA 1201, and similar provisions of Article 6 of the EUCD in France where Exodus is located – to distribute tools that bypass this DRM, even for the essential work of discovering whether billions of people are at risk due to covert spying from the platform.

It's true that the US Copyright Office gave us a soon-to-expire exemption to this rule that started in 2016, but that exemption only allows Exodus to use that tool; **it doesn't allow Exodus to make that tool, or to distribute it so independent researchers can investigate iOS**.”

----

# εxodus Static Analysis

----

## Quick εxodus Stats

* 152 tracker signatures, 28,600 reports (Oct 1, 2018)
* 26,133 apps scanned, 400GB+ APK packages

----

## Tracker Profiles

##### [github.com/YalePrivacyLab/tracker-profiles](https://github.com/YalePrivacyLab/tracker-profiles)

##### Calling crash reporters like HockeyApp, Crashlytics "trackers" has been controversial, though they have advanced analytics features/options.

----

### Adding & Improving Tracker Profiles

* We are  updating profiles, adding new ones.
* We're correlating companies via [OpenCorporates](https://opencorporates.com/).

----

## We're looking for more contributors, and you can help us by contacting [Yale Privacy Lab](https://privacylab.yale.edu/people) directly or [finding us on github](https://github.com/YalePrivacyLab/tracker-profiles).

----

##### Mozilla has been guiding us via the Open Leaders Program and our mentor [Josefina Caro Magaña](https://twitter.com/PepaLisperguer) of [Beyond Activismo](https://beyondactivismo.org).

----

# Real-World Impact:

### Working on tracker profiles with us means you're contributing to software projects that protect privacy such as εxodus, F-Droid, Yalp Store, and our ultrasonic jammer apps.

----

### Our tracker profiles go upstream to these software projects.  Here are some examples.

----

## F-Droid Collaboration

##### [F-Droid Blog Dec 2017](https://f-droid.org/en/2017/12/14/new-collaborations-on-exposing-tracking.html)

----

# F-Droid Package Scanning

* AI/machine learning in the future?

* [LibScout](https://github.com/reddr/LibScout)

https://gitlab.com/fdroid/rfp/issues?label_name[]=trackers

----

## Free Software Projects

* Utilize εxodus API:
  - [εxodus CLI](https://github.com/Exodus-Privacy/exodus-standalone)
  - [εxodus Android app](https://github.com/Exodus-Privacy/exodus-android-app)
  - [εxodify browser addons](https://github.com/FacettsOpen/exodify)

* [PilferShush Android app](https://github.com/YalePrivacyLab/PilferShush_prod)
* [PiRanhaLysis](https://github.com/U039b/PiRogue) network interception/analysis (PiRogue, PiPrecious, Phorcys)

----

### Now that we understand static analysis and tracker SDKs, let's talk about physical methods that companies use to track us.

----

# Proximity Targeting

* Retailers are using **bluetooth** alongside **sonic** (near-ultrasonic/ultrasonic, 18kHz to 22kHz range) technology to track precise physical movements via **beacons**.

* The _de facto_ bluetooth beacon standard is **Apple iBeacon**, one of the first to market.

----

##### Signatures of sonic tracker SDKs [SilverPush](https://reports.exodus-privacy.eu.org/trackers/80/), [Alphonso](https://reports.exodus-privacy.eu.org/trackers/82/), [Lisnr](https://reports.exodus-privacy.eu.org/trackers/79/), [Shopkick](https://reports.exodus-privacy.eu.org/trackers/81/), [Fidzup](https://reports.exodus-privacy.eu.org/trackers/2/), and [Signal360](https://reports.exodus-privacy.eu.org/trackers/86/) can be detected by εxodus.  Their profiles are in our [github repository](https://github.com/YalePrivacyLab/tracker-profiles).

##### We're detecting new trackers that utilize these creepy methods often.  The latest is [CopSonic](https://www.copsonic.com/).

----

# Example Beacon Devices

##### Source: [https://en.wikipedia.org/wiki/IBeacon](https://en.wikipedia.org/wiki/IBeacon#/media/File:An_assortment_of_iBeacon_from_different_vendors.jpg)

----

## Important Caveats

* Beacons use a _combination_ of technologies and **may not require an SDK** on a target person's phone.

* Special beacon devices are not required. Sonic tracking can occur via **stadium/arena** (Lisnr, Signal360), **retail** (Shopkick, Fidzup), **TV** (Alphonso, SilverPush) speakers.

----

#### Example Sonic Tracking Signals

----

#### Sonic Tracking Signal: Closer Look

###### [Audio Sample, Macy's](https://soundcloud.com/city-frequencies/beacon-pitched-time-shifted)

###### [Much More Info from Cityfreqs](http://www.cityfreqs.com.au/pilfer.php)

----

# Sonic Tracking Is Not Sci-Fi

* [Frequency Shift Keying](https://www.sec.cs.tu-bs.de/pubs/2016-batmobile.pdf) is the primary method.

* Some sonic trackers are very basic ([Fidzup](https://patents.google.com/patent/FR3010821A1/fr)), others are complex ([Shopkick](https://soundcloud.com/city-frequencies/beacon-pitched-time-shifted)).

* [FTC warnings](https://www.ftc.gov/news-events/press-releases/2016/03/ftc-issues-warning-letters-app-developers-using-silverpush-code) were issued for app devs who were using SilverPush in 2016.

* Many Alphonso apps were pulled in December 2017 after a [_NYTimes_ story](https://www.nytimes.com/2017/12/28/business/media/alphonso-app-tracking.html).

----

#####  Researchers and journalists have shared their app lists/checksums with us. We've got lists of sonic tracking apps still in the wild.

##### If you are interested in learning more, we can share these and other details (copies of ultrasonic recordings etc.)

----

## Check out the following example of sonic tracking, via a demo video offered by a tracking company.

----

# Sonic Proximity Targeting

* Demo w/ smartphone: https://frama.link/fidvid01
* Video w/ signals:  https://frama.link/fidvid-tmt

----

## GDPR Warnings for Fidzup, Teemo

----

## With the help of our [PilferShush app](https://github.com/YalePrivacyLab/PilferShush_prod), developed by [Cityfreqs](http://www.cityfreqs.com.au/pilfer.php), we can successfully block these ultrasonic signals.

----

## **PilferShush**
#### Detects & Blocks Sonic Tracking Signals

https://github.com/YalePrivacyLab/PilferShush_prod

* Android app by Cityfreqs.

* Two versions. PilferShush Jammer is the friendlier one for blocking signals.

----

## Grab the **PilferShush**  Jammer

* Available in [F-Droid](https://fossdroid.com/a/pilfershush-jammer.html) & [Google Play](https://play.google.com/store/apps/details?id=cityfreqs.com.pilfershushjammer&hl=en_US)

----

### Beacons are a pervasive adversary to privacy in our physical world.

#### We can hunt for beacons that may be sending sonic and bluetooth signals.

----
# Beacon Hunting

On Android - [Beacon Locator](https://f-droid.org/en/packages/com.samebits.beacon.locator/), [iBeacon Detector](https://play.google.com/store/apps/details?id=youten.redo.ble.ibeacondetector&hl=en)

On iOS - [Locate Beacon](https://itunes.apple.com/us/app/locate-beacon/id738709014), [DIY method](http://www.beekn.net/2015/02/tutorial-making-smarter-ibeacon-detector-ios/)

* Sonic tracking is useful in some cases, but bluetooth is more dynamic and widespread.

----

## iBeacon Detected!

----

### Remember, you should turn off bluetooth on your devices by default, and  be careful about **both** microphone and bluetooth settings, as well as app permissions.

----

# "PiRogue" Raspberry Pi

## [Network Analysis via MITMproxy](https://www.youtube.com/watch?v=oIcrsuJcTPo)

----

#### Visualizing Network Data in Real-Time

## [PiRanhaLysis](https://piranhalysis.github.io/)
#### Mobile/IoT analysis suite

----

# Thank You!

* Mozilla Open Leaders and Josefina Caro Magaña
* Scott Shapiro, Laurin Weissinger, Jon Oronzo
* Rebecca Crootof, Jack Balkin, Mike Kwet, Yale ISP
* PiRanhaLysis and Exodus Privacy team
* City Frequencies
* Hans-Christoph Steiner and F-Droid team
* Eben Moglen and Danny Haidar, Freedombox Fndn
* Nathan Freitas, Guardian Project