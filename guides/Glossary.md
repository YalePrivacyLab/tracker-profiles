# Glossary of Terms

## Identifiers

**AAID (Google Advertising ID for Android Devices)** AAID is "A user-specific, unique, resettable ID for advertising, provided by Google Play services. It gives users better controls and provides developers with a simple, standard system to continue to monetize your apps. It is an anonymous identifier for advertising purposes and enables users to reset their identifier or opt out of interest-based ads within Google Play apps." [Google, 1](https://help.tune.com/marketing-console/googles-advertising-identifier)

It "provides the same type of device-specific, unique, resettable ID for advertising as the IDFA. The ID for tablet devices with multiple users may also be unique per user. All of the features, encryption and technical details for IDFA also apply to the advertising ID." [Google,2](https://support.google.com/adxbuyer/answer/3221407)

**IDFA (Identifier for Advertising):** "a random device identifier assigned by Apple to a user’s device" for personalized ads, "used for tracking and identifying a user, which then allows advertisers to access aggregated data which can be used to discover information – such as which in-app events they trigger."  Moreover, "It may be used by advertisers to run remarketing campaigns and record purchasing or downloading conversions."

The IDFA can also identify users when they interact with a mobile advertising campaign, provided the channel offers IDFA tracking and that the advertiser tracks users who interact with adverts successfully. If this occurs the IDFA can pickup whether specific users click an advert for payment and attribution purposes." Users can opt out through "limit ad tracking (LAD)" and 205 of iOS users use LAD.  Companies like Adjust can analyze iOS users to identify how many users opt-out through LAD.

IDFA "can be reset by the user at any time" and "users can opt out using LAD" [Adjust,3](https://www.adjust.com/glossary/idfa]; [Google,2](https://support.google.com/adxbuyer/answer/3221407)


## Trackers

**DoubleClick Ad Exchange:** "Ad Exchange passes the identifier values in the mobile.encrypted_advertising_id field in the bid request. This field will contain either an IDFA or AAID value.  The value of AAID is always clear (unhashed), but IDFA can either be clear or hashed. If the bid request has a clear value, you can use the platform field to determine if it’s iOS or Android. Hashed IDFA values use the mobile.encrypted_hashed_idfa field, instead." [Google, 2](https://support.google.com/adxbuyer/answer/3221407)

**Fidzup:** 

**Salesforce DMP (formerly Krux):** Huge SanFran-based cloud-computing company for Customer Relationship Management (CRM).  Salesforce (the overarching company) is one of the largest software companies in the world, and the world's #1 CRM company [SF, 8](http://investor.salesforce.com/about-us/investor/overview/default.aspx)

**Teemo (formerly Databerries):** 


## Networks

**Google Search Network:** "featuring the standard Google Search, Google Shopping, Maps and its various search partners" [Econsultancy, 2013](https://econsultancy.com/blog/63783-what-is-paid-search-ppc-and-why-do-you-need-it)    

**Google Display Network:** "any website that partners with Google, and other Google sites such as Gmail, YouTube and Blogger" [Econsultancy, 2013](https://econsultancy.com/blog/63783-what-is-paid-search-ppc-and-why-do-you-need-it)    

**Yahoo Bing Network:** "claims to be a ‘combined advertising marketplace’ made up of Yahoo, Bing and many syndicated partners such as Facebook, Amazon and Monster" [Econsultancy, 2013](https://econsultancy.com/blog/63783-what-is-paid-search-ppc-and-why-do-you-need-it) 


## Terms

**Ad Exchange:** "An ad exchange is a digital marketplace that enables advertisers and publishers to buy and sell advertising space, often through real-time auctions. They’re most often used to sell display, video and mobile ad inventory...Virtually anyone can buy from an ad exchange provided the ad exchange allows it. Advertisers and agencies typically use demand-side platforms or their own bidding technologies to do so, but ad networks and other entities also buy ads from exchanges. Basically, an ad exchange is just a big pool of ad impressions. Publishers tip their ad impressions into the pool hoping someone will buy them. Buyers then pick which impressions they wish to purchase using technologies like demand-side platforms. Those decisions are often made in real time based on information such as the previous behavior of the user an ad is being served to, time of day, device type, ad position and more." [Digiday](https://digiday.com/media/what-is-an-ad-exchange)

"A marketplace that auctions ad impressions in real-time, among multiple bidding advertisers and/or networks and sells the impression to the highest bidder. You can think of them as digital stock exchanges where impressions are shares. The auction takes place and the winning ad is served within the milliseconds it takes for your browser to load and serve you an ad impression...they offer considerable increase in transparency, control, and targeting capabilities. They allow advertisers to serve ads to the right viewer, (based on behavioral targeting), at the right time of day, on the right publisher. Budgets can be kept in check and tracking where your ads are served is simplified. They allow advertisers to know which ad space is best to repurchase on and how best to optimize" [WhatRunsWhere](http://blog.whatrunswhere.com/media-buying-101-ad-networks-ad-exchanges)

A "digital marketplace where selling, bidding and purchasing happens. Publishers designate available inventory in Ad Exchanges as if saying, “User X is visiting my website right now, who wants to advertise here?” Advertisers through DSPs assess this inventory, evaluate the user and decide whether this impression is relevant. If yes, DSP would bid automatically on this ad slot in order to place the advertisement on that website in front of that user.  Therefore, Ad Exchange is just a COMPONENT of real-time bidding. To make it short, RTB is a process; Ad Exchange is a software-based platform. RTB is a real-time auction, whereas Ad Exchange is a PLACE where that auction happens." Put another way: "At a high level, one key difference is that an Ad Exchange is a type of business or platform in digital advertising where RTB is a protocol for two digital advertising companies to transact." [Quora](https://www.quora.com/What-is-the-Difference-between-an-Ad-Exchange-and-RTB)  Examples include "DoubleClick (Google), Microsoft Media Network, OpenX, and AppNexus" [WhatRunsWhere](http://blog.whatrunswhere.com/media-buying-101-ad-networks-ad-exchanges)

**Ad Network:** "online ad networks is that online ad networks use a central ad server to deliver advertisements to consumers, which enables targeting, tracking and reporting of impressions in ways not possible with analog media alternatives...The advertising network serves advertisements from its central ad server, which responds to a site once a page is called. A snippet of code is called from the ad server, that represents the advertising banner..." [Wikipedia](https://en.wikipedia.org/wiki/Advertising_network).  

**Ad Server:** "The technology responsible for delivering the creative to the user. Ad servers report which and how many ads were run, where they were run, and who saw them." [Smart AdServer](http://smartadserver.com/glossary)

**Ad types:** Banners, native ads, videos, audio fragments, text, pop clicks, etc.

**Ads.txt:** "a tool that can help ad buyers avoid illegitimate sellers who arbitrage inventory and spoof domains; an IAB-approved text file that aims to prevent unauthorized inventory sales".  With Ads.txt, "Publishers drop a text file on their web servers that lists all of the companies that are authorized to sell the publishers’ inventory. Similarly, programmatic platforms also integrate ads.txt files to confirm which publishers’ inventory they are authorized to sell. This allows buyers to check the validity of the inventory they purchase." Using Ads.txt is a way to "verify that the exchange and publisher have a legitimate connection to each other" and prevents the unauthorized inclusion of publisher's inventory from being sold to buyers [Digiday](https://digiday.com/marketing/wtf-ads-txt).

**Advertising Inventory:** "The number of advertisements, or amount of ad space, a publisher has available to sell to an advertiser. Ad inventory is often calculated by the month." [Chron](http://smallbusiness.chron.com/advertising-inventory-mean-35920.html) "Networks include Google AdSense, Media.Net, BuySellAds and Conversant." [WhatRunsWhere](http://blog.whatrunswhere.com/media-buying-101-ad-networks-ad-exchanges)

**Buyer side:** The advertiser is the "buyer side"

**Conversion:** "A click-through conversion occurs when an ad click leads directly to a valuable user-action such as a purchase, sign-up, registration, lead, or view of a key page. Conversion rate measures the effectiveness of unique clicks. The formula is Conversion Rate = Conversions ÷ Unique Clicks." [AdSpeed](https://www.adspeed.com/Knowledges/776/Conversion/conversion-transaction.html)

**Data Activation:** "Data Activation is the concept of unlocking value in data through development of insights and turning those insights into action."  3 steps: 1) bring data in across different locations (websites, mobile, etc); 2) run analytics; 3) Data Out, potentially in partnership across the ecosystem (eg, using shared segments) [Oracle, 1](https://www.oracle.com/marketingcloud/resources/data-activation.html)

**Data on-boarding (aka data on-ramping):** "the transfer of data gathered offline to the digital realm" [Ad Age, 1](http://adage.com/article/glossary-data-defined/data-boarding/293651)

**Demand-side platform:** A system that allows buyers of digital advertising inventory to manage multiple ad exchange and data exchange accounts through one interface.  "Basically, the DSP automates the online advertising purchase process for advertisers who use DSPs to monitor their campaigns" [WhatRunswhere](http://blog.whatrunswhere.com/media-buying-101-programmatic-buying).   Put another way, a DSP is "a platform, which allows advertisers to buy ads from different publishers and SSPs (Supply/Sell Side Platforms). That’s a user interface to run and manage campaigns on several websites from one place." [Igor Pavlov](https://medium.com/admachine/what-is-white-label-dsp-demand-side-platform-de601f106771)

"A technology system that enables buyers purchasing auction-based digital ad inventory, managing multiple ad exchanges and data exchanges through a single user interface. DSP assures more efficient buying and selling by reduced costs and increased transparency. DSP introduces advanced targeting tools, providing options to target contextually, behaviorally, geographically, and even option to retarget later. The biggest advantage of DSPs is their ability to make automated decisions on how much to bid on each specific ad impression in real time, based on the targeting requirement of the advertiser. Therefore, advertisers can generate the most value and increase return on investments (ROI)... Where do I get this “DSP”? DSPs are could be managed by in-house marketing departments or alternatively, by programmatic companies that specialize in real-time advertising. Key DSP players guarantee buyers reaching billions daily impressions, worth to mention: DoubleClick Bid Manager, BrightRoll DSP, Mediamath etc... all companies provide “DSP platforms” but not all of them share exact the same features, so choose smart!"   

DSPs represent the interests of buyers (advertisers) so they get "better optimization, much lower bids and higher ROI".  They provide advertisers with access to multiple supply partners, and help them cut off from bad traffic that brings less or no conversions.  However, they add an expense for usage, as a sign up fee, monthly fee, or percent of your ad spendings. [Quora](https://www.quora.com/What-is-a-Demand-Side-Platform-DSP).

**Direct Campaigns (direct marketing):** Advertisers communicate directly to customers through media (eg, text messages, emails, websites, online adverts, etc) [Wikipedia](https://en.wikipedia.org/wiki/Direct_marketing)

**Direct deals:** Buyers get First Look at fixed-price unreserved inventory that is specific to a particular audience. [Smart AdServer](http://smartadserver.com/publisher-platform/premium-programmatic).  The pro's are that "Advertisers want the guarantee of being placed next to premium content, above the fold, in front of a guaranteed set of eyeballs, for a specific period of time, at a set rate. Further, media buyers are tasked with spending 100% of their budgets for fear they are reduced next quarter because they didn’t spend enough. Without a guarantee in place with publishers, their media spend is at risk of (a) not being spent or (b) being spent in less than ideal context at the end of a fiscal period. Programmatic buying technology like real-time bidding (RTB) provides advertisers/media buyers no guarantee on price, contextual placement, or impression volume".  Examples are "skin" website takeovers, which must be catered to an individual page, and take on a premium price [Sovrn](https://www.sovrn.com/blog/direct-sales-vs-programmatic-sales)  

**Dwell time:** "The duration of an interaction with a proximity technology" [Unacast](https://www.unacast.com/privacy-statement)

**Dynamic Creative:** personalized content; "built in real time when an ad request is sent to the server, and will pull different creative elements based on the environment, the user and other factors", based on user history (web searches, page visits, etc). [The Balance](https://www.thebalance.com/what-is-dynamic-creative-in-advertising-38508) [Smart AdServer](http://smartadserver.com/glossary)

**Dynamic Floor Pricing:** "In an RTB auction, a minimum bid price that is constantly set and reset in real time. Prices are selected in response to previous transactions and changes in demand. This pricing method allows publishers to boost revenue with an optimization system that fits with buyers’ bidding strategies." 

**Floor Price:** "In an RTB auction, the minimum bid price (CPM) set by a publisher or SSP on ad inventory. Any potential buyers who bid below this price are automatically rejected." [Smart AdServer](http://smartadserver.com/glossary)

**Forecast:** "A tool that allows clients to discover how much space they have sold and how much is left to sell. Forecasts also predict how much a publisher or ad network will earn based on the number of users and the amount of inventory sold." [Smart AdServer](http://smartadserver.com/glossary)

**Geofencing**: "a feature in a software program that uses the global positioning system (GPS) or radio frequency identification (RFID) to define geographical boundaries... Geofence virtual barriers can be active or passive. Active geofences require an end user to opt-in to location services and a mobile app to be open. Passive geofences are always on; they rely on Wi-Fi and cellular data instead of GPS or RFID and work in the background." For one use case in marketing, "A small business can text an opt-in customer a coupon code when the customer's smartphone enters a defined geographical area." [Whatis.com TechTarget](http://whatis.techtarget.com/definition/geofencing)

**Google Insights Engine Project:** "an ongoing initiative to bring Google’s cloud computing and machine learning expertise to DoubleClick’s reporting and forecasting systems" [DoubleClick blog](https://doubleclick-publishers.googleblog.com/2017/10/building-for-beyond-with-insights.html)

**Guaranteed deals:** Buyers purchase your inventory with the same options (priorities, volume, date) that they use for direct campaigns. [Smart AdServer](http://smartadserver.com/publisher-platform/premium-programmatic)

**Header bidding:** "Header bidding, also known as advance bidding or pre-bidding, is an advanced programmatic technique wherein publishers offer inventory to multiple ad exchanges simultaneously before making calls to their ad servers (mostly DoubleClick for Publishers). The idea is that by letting multiple demand sources bid on the same inventory at the same time, publishers increase their yield and make more money." [Digiday](https://digiday.com/media/wtf-header-bidding)

**Holistic Yield Management:** "HYM aims to merge all demand sources and inventory types (guaranteed, performance, networks, RTB, and programmatic direct) and assess their value simultaneously. The programmatic segment is merged based on internal forecast data. HYM integrates programmatic buying into ad delivery logic while taking into account all monetization types (direct, guaranteed, performance, and programmatic), allowing synchronization of the two buying methods." [Smart AdServer](http://smartadserver.com/glossary)

**iBeacon:** Apple bluetooth devices that send data to iPhones; can be used for in-store advertising; can only send data to devices (cannot receive) [Fast Company](https://www.fastcompany.com/3035729/apples-ibeacons-are-going-to-transform-much-more-than-advertising)

**Interstitial:** A full-screen ad that covers the entire interface of the host app.

**Managed Tag:** "A way for advertisers to get a first look at a publisher’s inventory by plugging a tag into the publisher’s ad server. After they’re connected, the advertiser can see the inventory and, if desired, place a bid. If the advertiser buys, it’s at a fixed price and CPM. This process benefits publishers because it cuts out the middleman and helps them manage their campaign spending better. (Note: this has nothing to do with 'tag management'.)" [Smart AdServer](http://smartadserver.com/glossary)

**Marketing Funnel:** "a visualization for understanding the process of turning leads into customers, as understood from a marketing (and sales) perspective. The idea is that, like a funnel, marketers cast a broad net to capture as many leads as possible, and then slowly nurture prospective customers through the purchasing decision, narrowing down these candidates in each stage of the funnel." [TrackMaven](https://trackmaven.com/blog/marketing-funnel-2)

**Open Auction:** All buyers have the opportunity to bid on your unreserved inventory.

**Paid search marketing:** "Paid search marketing means you advertise within the sponsored listings of a search engine or a partner site by paying either each time your ad is clicked (pay-per-click - PPC) or less commonly, when your ad is displayed (cost-per-impression - CPM)" [econsultancy](https://econsultancy.com/blog/63783-what-is-paid-search-ppc-and-why-do-you-need-it)

**Passbacks:** "When an ad server calls various SSPs until it finds one that accepts. Passbacks are part of the “waterfall” prioritization model." [Smart AdServer](http://smartadserver.com/glossary)

**Premium Inventory:** Characteristics: "professional content, high-reach sites (i.e., not long tail), brand-safe and reputable publishers." This could depend on the client and their objectives. [Digiday](https://digiday.com/marketing/what-does-premium-inventory-actually-mean) "Quality, “brand safe” inventory offered by reputable publishers whose users have chosen to frequent their sites because of a true interest in the high-value content provided. The ad environment aids in properly targeting the user, and the surrounding content adds value to an ad impression. This inventory is also primed to display innovative formats which boost ad performance. True premium inventory goes through a strict scanning process that includes proof of a direct relationship with publishers or insertion orders. Often, new inventory information is provided to buyers for approval. This enables fluent communication and knowledge-sharing of any suspicious activities, which helps improve the entire ecosystem." [Smart AdServer](http://smartadserver.com/glossary)

**Private auctions:** Buyers access privileged information about inventory in order to increase their chances of winning an auction. [Smart AdServer](http://smartadserver.com/publisher-platform/premium-programmatic); "An auction within an auction for select, whitelisted buyers who are given first-look at the inventory before it’s made available to the open marketplace. Inventory is not sold at a fixed price." [Smart AdServer](http://smartadserver.com/glossary)

**Private Marketplace / Deals:** "An invitation-only RTB exchange that uses programmatic buying channels to auction premium inventory to a selected set of  pre-approved buyers.  Publishers may set minimum bids (a floor price) to maintain the desired sale price. The tagging, testing, and validation are all automated and the sale is made through the use of deal IDs, private auctions or preferred deals. However, all parties are in contact with each other to negotiate the terms of the auction in advance. However, vendors are in contact with each other and decide on the details of the sale in advance." [Smart AdServer](http://smartadserver.com/glossary)

**Programmatic Advertising:** "Programmatic advertising is not a new form of digital ads, but new approach to targeting, where machines decide if the user is worth seeing that specific ad. You’ve probably heard something about machine learning. Well, that’s what we’re talking about... Programmatic buying is finally the way to buy audience, not a place on a website. That may seem like robots control too much, but they don’t. They still can’t find your customers without you setting proper targeting... What is RTB then? Is it programmatic? At most it is. Real-time bidding is a mechanism of programmatic buying. Since you’re paying for every view or click, advertising platform launches a fast auction for every that single view. 

Should I use programmatic?

If you’re an advertiser you may use programmatic advertising to better reach your potential clients. This way you don’t spray your budget all over the place, but get at least relevant audience.

If you are a publisher, you can still sell oldschool display banners, but you can also install SSP code and get at least some more money for the traffic you couldn’t sell as usual. When talking about “as usual” we should also mention that more and more publishers start selling their traffic only through SSPs. Why? Because it is much easier just to install the code and let it do the thing, than to find clients and place every single banner by hands. Programmatic may sometimes bring less income, but you save time and become more cost-effective." [Igor Pavlov](https://medium.com/admachine/what-is-programmatic-advertising-cfa56544c48)

**Programmatic Media Buying:** "generally refers to the automation of all online advertising as a whole, Programmatic Direct and Programmatic RTB are subsets of the umbrella term." [WhatRunswhere](http://blog.whatrunswhere.com/media-buying-101-programmatic-buying).  Programmatic sales do not require teams of humans to broker deals, and it "allows publishers and advertisers alike to benefit from audience data, as programmatic uses cookies... As of late, programmatic has been rapidly gaining traction in mobile and video. As the industry as a whole shifts towards mobile, SSPs are seeing an increasing amount of programmatic transactions served on mobile devices." [Sovrn](https://www.sovrn.com/blog/direct-sales-vs-programmatic-sales)

**Proximity Signals with Beacon technology:** "Proximity-based mobile advertising is one trend in advertising isn’t completely new, but it’s been given some more gusto recently due to the development and inclusion of beacon technology. Proximity signals fire when a user is close to a sensor, and can be used to send promotions or ads to users when they are close to the sensor. This can be seen as an alternative to GPS geolocation targeting in closer spaces, such as shopping malls." [Sovrn](https://www.sovrn.com/blog/7-mobile-advertising-trends)

**Pure Player:** "a company that focuses only on a particular product or activity. Investing in a pure play company can be considered as investing in a particular commodity or product of a company." [Wikipedia](https://en.wikipedia.org/wiki/Pure_play)

**Remnant inventory:** "Any ad units that have not been purchased by an advertiser, and this must be accounted for using another strategy... Ideally, a site will sell every one of its available ad impressions directly to advertisers at premium CPMs" [MonetizePros](https://monetizepros.com/encyclopedia/remnant)

**Retargeting** Retargeting uses tracking technologies like cookies and web pixels to follow users around the web. This allows marketers to serve ads to people who did not convert a sale at a particular website. This "focuses your advertising spend on people who are already familiar with your brand and have recently demonstrated interest" [Retargeter](https://retargeter.com/what-is-retargeting-and-how-does-it-work).

**Seller side:** The publisher is the "seller side"

**Slot:** Digital spaces (area for banner ads, native ads, pop clicks, etc) that publishers sell to advertisers.

**Supply-side platform:** "Advertisers set their bids, the SSP choses the highest one and sells publishers slot. That is RTB, real time bidding and that is how it works. So we may say, that the purpose of SSP is to deliver best price for the publisher." [Igor Pavlov](https://medium.com/admachine/is-dsp-better-than-ssp-9118238f3afd) "One can say the main purpose of SSP is to sell view or click for a highest bid, since it works on RTB basis."

**UTM Parameters:** "UTM parameter is term coined by Google Analytics to describe the URL elements that capture information like the source, medium, and campaign name from that activity."  See [SF, 55](https://konsole.zendesk.com/hc/en-us/articles/115002018607-UTM-Parameters-FAQ)

**Viewability:** "how likely an ad is to be seen on a page... The Media Rating Council decided that a desktop display ad is viewed when 50% of its pixels are in view for 1 continuous second. For video it is the same 50% of pixels in view but for 2 seconds instead of 1... " [Sovrn](https://www.sovrn.com/blog/intro-viewability) "**Viewability:** " an online advertising metric that aims to track only impressions that can actually be seen by users. For example, if an ad is loaded at the bottom of a webpage but a user doesn’t scroll down far enough to see it, that impression would not be deemed viewable. Viewability is designed to let advertisers pay only for the ads that users could possibly see... Depending on whom you believe — and everyone has a dog in this fight — up to 54 percent of ads aren’t viewable." See [Digiday](https://digiday.com/media/wtf-viewability) 

**Waterfall (sales strategy for publishers):** "Publishers offer impressions in one sales channel, and if buyers don’t bite, they push them down to other, less valuable channels until someone makes a bid. The system works, but it’s highly fractured and inherently inefficient. Publishers say the system leaves money on the table." [Digiday](https://digiday.com/media/wtf-header-bidding)

**Web Beacon:** "Web Beacons are used to help web publishers understand how visitors interact with their websites. Pixel tags are transparent images, iFrames, or JavaScript that are placed on a site. The use of a pixel tag allows a website to measure the actions of the visitor opening the page that contains the tag." [Smart AdServer](http://smartadserver.com/company/privacy-policy)

**"White Label" DSP:** The tool you can sell to operate a DSP or SSP, usually after buying software and reselling it to your customers, as "a franchise with no brand included".  Profit comes from a percentage of advertisers' payments; you charge to buy or use the product. AdMachine is an example. [Igor Pavlov](https://medium.com/admachine/what-is-white-label-dsp-demand-side-platform-de601f106771)


## More Resources

Great definitions of cookies, web beacons, IP logging, Social Media Features, and Do Not Track [SF,6](https://www.salesforce.com/company/privacy/full_privacy.jsp)

