# SafeGraph

## Primary Location
United States (San Francisco) [Crunchbase, 01](https://www.crunchbase.com/organization/safegraph)

## Website
[https://www.safegraph.com](https://www.safegraph.com)

## About
SafeGraph specializes in the collection of physical location data for data mining and analytics.

## Ownership
SafeGraph

## Detection Rules
* `api\.safegraph\.com`

## Documentation
[https://github.com/OpenLocate/openlocate-android](https://github.com/OpenLocate/openlocate-android)

## Products and Services
SafeGraph is a data company which aims to build a robust and detailed location-based tracking service for advertisers, industry, government and researchers. Products and services include:

* _SafeGraph Movement Panel:_ SafeGraph's "database of ultra-accurate GPS-location data that comes from anonymized mobile devices." The Movement panel offers:
* * _Sink detection:_ Detection of inaccurate location data based on " specific coordinates occurring at impossibly high rates".
* * _Teleporting detection:_ Detection of inaccurate location data when "devices appear to move at impossibly fast speeds, ostensibly traveling large distances between data points that occur next to each other" in data streams like bid streams.
* * _Jumpiness detection:_ Detection of innacurate location data when "we see two consecutive points in time that are fairly close but still implausibly spaced" (eg, "the GPS receiver in your phone lags or if a nearby skyscraper interferes with the location signal") [SafeGraph, 01](https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475)
* _SafeGraph Places API:_ This "to easily find the places of interest that are near a given lat/long, ordered by distance or relevance" [SafeGraph, 03](https://developers.safegraph.com/docs/places.html).
* _OpenLocate:_ The OpenLocate SDK will "collect location data (like GPS) from phones" [SafeGraph, 04](https://github.com/OpenLocate). This includes an Android and iOS SDK.  The service is built to provide developers complete control over their location data.  Developers can build location-enabled features into their apps and "maintain complete control over how end-user data is collected, where it is stored, and which APIs it will be sent to". This includes sending to storage services (like Amazon S3) or APIs (such as Google Places API or SafeGraph's Places API) [SafeGraph, 05](https://blog.safegraph.com/introducing-openlocate-the-open-source-location-sdk-f5c5d2739a48).

Other services include:
* "Detailed polygon maps on 50+ million U.S. places of interest
* Understanding of each business's popularity, taxonomy, hours, etc.
* Core investments in benchmarking via truth sets"
* * This includes Explicit Truth Sets (Check-ins, Daily diaries, Web surveys) and Implicit Truth Sets (Credit card data, Receipt data, First-party transactions) 

Data from visits may include:

* _Core truth set for matching:_
* * High-res GPS data
* * Deterministic data
* * Explicit and implicit truth
* * Data collected in background from large population
* _Deep places map:_
* * Best polygons
* * Footprint geometries
* * Metadata
* * Categories
* * Hours of operation
* Machine learning technology
* * Cross-validated against multiple independent 3rd party truth sets about where people go
* _Truth and accuracy_
* * High Precision // Low false positive rate; High recall // Low false negative rate" [SafeGraph, 06](https://www.safegraph.com/truth)

## Privacy Policy
_Data collection (method and use):_ SafeGraph collects data from "trusted third-party data partners such as mobile application developers, through APIs and other delivery methods". The data collection and use is "governed by the privacy policy and legal terms of the data collector and the website using the data; it is not governed by SafeGraph." SafeGraph "aggregates data collected from our data partners, and allows third party customers to access the Data for a variety of purposes such as ad targeting, traffic analysis, and market research." SafeGraph may also use data for their own "internal and operational purposes", and share data in response to requests from law enforcement or a governmental agency, "to protect or enforce our rights or those of others, or to investigate potential wrongdoing."  Data can also be transferred to a successor entity in the event of a merger or acquisition.

_Information collected:_ Information collected includes "data regarding a device’s precise geographic location, as well as other mobile identifiers such as Apple IDFAs and Google Android IDs, and other information about users and their devices."  

_Jurisdictions:_ "SafeGraph stores and processes information on servers in many countries around the world. We therefore may process your information on a server located outside the country where you live... Our customers (or companies that help us process the Data) may be located in other countries, so the Data we provide may be processed or used in a variety of countries, other than those our users reside in."  Customers of SafeGraph may create cross-device capabilities "to enable marketers to target users across various channels and devices."

_Opt-out:_ SafeGraph informs users of opt-out procedures for interest-based advertising and location tracking.  To opt out of interest-based advertising, they state, users can adjust settings in their Android or iOS devices.  This procedure, which they note may change, is mentioned in the SafeGraph privacy policy "purely for informational purposes."  SafeGraph further notes that "You also can remove your consent to having your location data collected by changing the settings on your device. (Certain services may lose functionality as a result.)"  SafeGraph's Privacy Policy provides links to the Network Advertising Initiative and the Digital Advertising Alliance, as well as www.youronlinechoices.com.  It informs users that these websites may provide additional opt-out options.

_Retention:_ Information SafeGraph collects is "retained indefinitely unless there has been a direct opt-out with us as directed above."

_Security:_ SafeGraph has security policies and procedures to " ensure compliance with industry best practices."  They state, "no physical or technological safeguards are 100 percent secure, we do not guarantee the security of any particular elements of Data that we hold" [SafeGraph, 07](https://www.safegraph.com/privacy-policy).

## Relationships
_Clients and partners:_ Statiq / AirSage / Stanford University / GroundTruth (formerly xAd) / UCLA / Baylor University / Weborama / Tufts University / The University of Chicago / Alphonzo / Freckle IoT / Georgia Tech / Esri / Appnext / 4Info / Research Now / Tapfwd / Arrivalist / Placecast / ThinkNear by Telenav / Pitney Bowes / Columbia University / Purdue University / UC San Diego / Sidewalk Labs / Temple University / Citilabs / PlaceIQ / Moovit / Skyhook / Postie / PicsArt / Oklahoma State University / Santa Clara University / OpenLocate

## Details
_Financial details:_ SafeGraph was founded in 2016, and has raised $16 million from funders [Crunchbase, 01](https://www.crunchbase.com/organization/safegraph); [SafeGraph, 02](https://blog.safegraph.com/safegraph-raises-16-million-series-a-e8e88eeb7beb)  

_Scope:_ SafeGraph "has access to super-accurate, anonymized location data on over 5% of all mobile phones in the U.S. (as of August 2017)" and is "increasing that percentage every day" [SafeGraph, 01](https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475).

_Slogans:_

* "SafeGraph maintains the ground truth dataset for human movement across the globe"
* "We provide high-quality location data products to help organizations make better decisions and improve lives"

## References
_Crunchbase, 01._ [https://www.crunchbase.com/organization/safegraph](https://www.crunchbase.com/organization/safegraph)  

_SafeGraph, 01._ [https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475](https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475)  
_SafeGraph, 02._ [https://blog.safegraph.com/safegraph-raises-16-million-series-a-e8e88eeb7beb](https://blog.safegraph.com/safegraph-raises-16-million-series-a-e8e88eeb7beb)  
_SafeGraph, 03._ [https://developers.safegraph.com/docs/places.html](https://developers.safegraph.com/docs/places.html)  
_SafeGraph, 04._ [https://github.com/OpenLocate](https://github.com/OpenLocate)  
_SafeGraph, 05._ [https://blog.safegraph.com/introducing-openlocate-the-open-source-location-sdk-f5c5d2739a48](https://blog.safegraph.com/introducing-openlocate-the-open-source-location-sdk-f5c5d2739a48)  
_SafeGraph, 06._ [https://www.safegraph.com/truth](https://www.safegraph.com/truth)  
_SafeGraph, 07._ [https://www.safegraph.com/privacy-policy](https://www.safegraph.com/privacy-policy)

## External Links
_Crunchbase (SafeGraph):_ [https://www.crunchbase.com/organization/safegraph](https://www.crunchbase.com/organization/safegraph)  
_Gigya:_ [https://www.gigya.com/blog/exploring-future-identity](https://www.gigya.com/blog/exploring-future-identity)  
_Even:_ [https://evenfinancial.com/press/mit-brings-together-fintech-financial-services-first-ever-hackathon](https://evenfinancial.com/press/mit-brings-together-fintech-financial-services-first-ever-hackathon)  
_SafeGraph:_ [https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475](https://blog.safegraph.com/less-than-10-of-bid-stream-location-data-is-high-quality-and-we-know-how-to-find-it-3a2c0df35475)  
_Stanford Economics:_ [https://web.archive.org/web/20171116110210if_/https://economics.stanford.edu/sites/default/files/sharable_fulldraft.pdf](https://web.archive.org/web/20171116110210if_/https://economics.stanford.edu/sites/default/files/sharable_fulldraft.pdf)  
_Washington Post:_ [https://www.washingtonpost.com/news/wonk/wp/2017/11/15/politics-really-is-ruining-thanksgiving-according-to-data-from-10-million-cellphones](https://www.washingtonpost.com/news/wonk/wp/2017/11/15/politics-really-is-ruining-thanksgiving-according-to-data-from-10-million-cellphones)  
_The Outline:_ [https://theoutline.com/post/2490/why-is-this-company-tracking-where-you-are-on-thanksgiving](https://theoutline.com/post/2490/why-is-this-company-tracking-where-you-are-on-thanksgiving)

