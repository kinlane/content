---
layout: post
title: 'Quick Walk Through World of Location &amp; Places APIs'
---
<table align="right">
<tbody>
<tr>
<td><a href="http://www.designdelux.com/" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/local-search-map-pin.png" alt="" width="150" align="right" /></a></td>
</tr>
<tr>
<td align="center"><a href="http://www.designdelux.com/"><strong>Photo Credits</strong></a></td>
</tr>
</tbody>
</table>
I took a walk through what I am calling the locations and places API landscape today. Most of these APIs I'm familiar with, but as the CityGrid API Evangelist, I'm getting an opportunity to immerse myself into this new local, social mobile world.<p></p>
As I immerse myself in this semi-new world I want to share my findings with everyone else. If you have any suggestions make sure and let me know in comments below.<p></p>
First I started with <strong><a title="CityGrid APIs" href="http://developer.citygridmedia.com/">CityGrid APIs</a></strong>, which provide several key location and places APIs:
<a href="http://developer.citygridmedia.com/"><img src="http://kinlane-productions.s3.amazonaws.com/citygrid/citygrid_logo_200.png" alt="" width="150" align="right" /></a>
<ul class="mainlist">
	<li><strong>The Places API</strong> - Provides functionality for information on local businesses, including search, detail, user content submission, and predictive text</li>
	<li><strong>The Offers API</strong> - Provides coupons and special offers from businesses based on geography and category</li>
	<li><strong>The Reviews API</strong> - Provides access to customer reviews for businesses selected by id or by geography or category</li>
</ul>
Then I wanted to see what Google was doing, and of course started with the <strong><a title="Google Maps API" href="http://code.google.com/apis/maps/index.html">Google Maps APIs</a>:</strong>
<a href="http://code.google.com/apis/maps/"><img src="http://kinlane-productions.s3.amazonaws.com/google/Google-Maps-Logo.jpg" alt="" width="100" align="right" /></a>
<ul class="mainlist">
	<li><strong>Maps JavaScript API</strong> - The Google Maps Javascript API lets you embed Google Maps in your own web pages</li>
	<li><strong>Maps Image API</strong> - The Google Maps Image APIs make it easy to embed a static Google Maps image or Street View panorama into your web page, with no need for JavaScript</li>
</ul>
Along with Google Maps they offer a set of <strong><a title="Geo Web Services" href="http://code.google.com/apis/maps/documentation/geocoding/">Geo Web Services</a></strong> that contain several location and places based APIs:
<ul class="mainlist">
	<li><strong>Directions API</strong> - The Google Directions API is a service that calculates directions between locations</li>
	<li><strong>Distance Matrix API</strong> - The Google Distance Matrix API is a service that provides travel distance and time for a matrix of origins and destinations.</li>
	<li><strong>Elevation API</strong> - The Google Elevation API provides you an interface to query locations on the earth for elevation data.</li>
	<li><strong>Geocoding API</strong> - Geocoding is the process of converting addresses into geographic coordinates</li>
	<li><strong>Places API</strong> - The Google Places API is a service that returns information about places, defined as establishments, geographic locations, or prominent points of interest</li>
</ul>
Already with <strong><a title="CityGrid" href="http://www.citygrid.com">CityGrid</a></strong> and Google I'm seeing that the type of location and places services, really start to get complicated and diverse. With <strong><a href="http://code.google.com/apis/latitude/" target="_blank">Google Latitude</a></strong> I start separating the location from the place, with what are two location specific APIs:<a href="http://code.google.com/apis/latitude/"><img src="http://kinlane-productions.s3.amazonaws.com/google/google_latitude_icon.jpeg" alt="" width="100" align="right" /></a>
<ul class="mainlist">
	<li><strong>Curent locations</strong> - Represents the user's most recent known location</li>
	<li><strong>Location history</strong> - Represents the list of all recorded user locations</li>
</ul>
After Google I have to look at another big player, <strong><a title="Yahoo" href="http://developer.yahoo.com/everything.html?category=location&amp;view=detail">Yahoo</a></strong>. Yahoo has several location based services:<a href="http://developer.yahoo.com/everything.html?category=location&amp;view=detail"><img src="http://kinlane-productions.s3.amazonaws.com/yahoo/yahoo_geo_logo_med.png" alt="" width="150" align="right" /></a>
<ul class="mainlist">
	<li><strong>Fire Eagle</strong> - Fire Eagle is a service designed to build and use location-aware applications and services</li>
	<li><strong>GeoPlanet</strong> - Yahoo! GeoPlanet is a resource for managing all geo-permanent named places on Earth</li>
	<li><strong>Local</strong><strong>API</strong> - Provides a database of information including business address and phone, category, rating, distance, URL, and traffic alerts</li>
	<li><strong>Maps</strong> - Provides interactive maps with driving directions and traffic information</li>
	<li><strong>PlaceFinder</strong> - Converts street addresses or place names into geographic coordinates (and vice versa)</li>
	<li><strong>Placemaker</strong> - Identifies places mentioned in text, disambiguating them and returning unique identifiers</li>
</ul>
Naturally after taking a look at Yahoo I have to go see what <strong><a title="Microsoft" href="http://msdn.microsoft.com/en-us/library/ff701715.aspx">Microsoft</a></strong> is up to in the space:<a href="http://msdn.microsoft.com/en-us/library/ff701715.aspx"><img src="http://kinlane-productions.s3.amazonaws.com/bing/Bing_Maps_blue_200.jpg" alt="" width="150" align="right" /></a>
<ul class="mainlist">
	<li><strong>Bing Maps API</strong>- The API that power Bing Maps, an online mapping service that enables users to search, discover, explore, plan, and share information about specific locations</li>
	<li><strong>Bings Maps Location API</strong>- Use the Locations API to get location information (<em>I love this description!</em>)</li>
</ul>
After looking at what local and mobile offerings the big players Google, Yahoo and Microsoft had I started looking at less search and mapping based services to more carrier based location and place services. I started with <strong><a title="Verizon" href="http://developer.verizon.com/content/vdc/en/verizon-tools-apis/verizon_apis.html">Verizon</a></strong>, who has a single location API:<a href="http://developer.verizon.com/content/vdc/en/verizon-tools-apis/verizon_apis.html" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/verizon/verizon-logo.jpg" alt="" width="150" align="right" /></a>
<ul class="mainlist">
	<li><strong>LBS Network API</strong> - The Verizon LBS API allows you to use the user's location to deliver specific services</li>
</ul>
<strong><a title="Sprint" href="http://developer.sprint.com/site/global/home/p_home.jsp">Sprint</a></strong> brings three location APIs to the table:
<ul class="mainlist">
	<li><strong>Geofence</strong> - Provides virtual perimeter services</li>
	<li><strong>Location</strong> - Determines the location of a Sprint CDMA Device</li>
	<li><strong>Presence</strong> - Determines if a device is present on the Sprint CDMAnetwork</li>
</ul>
<strong><a title="AT&amp;T" href="http://kinlane-productions.s3.amazonaws.com/telcos/att-logo.jpg">AT&amp;T</a></strong> has a LBS API:
<ul class="mainlist">
	<li><strong>Terminal Location</strong> - Set of Location-based Services (LBS)</li>
</ul>
<strong><a title="Deutsche Telekom" href="http://www.developergarden.com/startseite">Deutsche Telekom</a></strong> has one location API:
<ul class="mainlist">
	<li><strong>IP Location API</strong> - Locate Internet users with their IP addresses</li>
</ul>
<strong><a title="Ericsson Labs" href="https://labs.ericsson.com/apis/">Ericsson Labs</a></strong> provides a developer community around a full suite of APIS:
<ul class="mainlist">
	<li><strong>3D Landscape API</strong> - 3D Landscape API for integration o realistic 3D MAPS</li>
	<li><strong>Mobile Location API</strong> - Allows the use a mobile phone user's current CELL-ID to obtain their geographical location</li>
	<li><strong>Network Probe API</strong> - Provides services measure certain characteristics of network IP connectivity, firewalls and Network Address Translators</li>
	<li><strong>Web Location API</strong> - Provides location data from a mobile phone using the positioning systems of mobile operators</li>
	<li><strong>Web Maps API</strong> - Provides dynamic maps for application integration</li>
</ul>
<strong><a title="France Telecom" href="http://www.orangepartner.com/">France Telecom</a></strong> also has a location API:
<ul class="mainlist">
	<li><strong>Location API</strong> - Allows applications to get geographic coordinates of a given Orange France mobile phone or a fleet</li>
</ul>
Makes sense for every carrier to also provide developers with a set of location services, as they don't want to just be dumb pipes. They want to be an integrated player in their own customers handset usage.<p></p>
Next I start looking to put the social in local, mobile, social. Where else to you start but Facebook, which has two location based objects as part of the <strong><a href="http://developers.facebook.com/docs/reference/api/" target="_blank">Graph API</a>:</strong><a href="http://developers.facebook.com/docs/reference/api/" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/facebook/facebook_logo-icon.png" alt="" width="80" align="right" /></a>
<ul class="mainlist">
	<li><strong>Checkin</strong> - A checkin represents a single visit by a user to a location</li>
	<li><strong>Places</strong> - A search option before initiating a checkin, returning name and location information from Graph API</li>
</ul>
I thought I'd consider Twitter next. They have <a title="Places &amp; Geo" href="https://dev.twitter.com/docs/api#places-geo">Places and Geo</a> methods, but it really doesn't seem like its going anywhere, and a really small portion of tweets have geo info recorded. I will consider in the future if I see action around it.<p></p>
In the category of location based social network I was investigating <strong><a href="https://developer.foursquare.com" target="_blank">Foursquare</a></strong>and <strong><a title="Gowalla" href="http://gowalla.com/">Gowalla</a></strong>, but with the recent Facebook acquisition of Gowalla I think I will only look at <strong><a href="https://developer.foursquare.com" target="_blank">Foursquare</a></strong>. Foursquare offers access to four different APIs:<p></p>
<a href="https://developer.foursquare.com/" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/foursquare/foursquare_logo_200.png" alt="" width="200" align="right" /></a>
<ul class="mainlist">
	<li><strong>Core API</strong> - Users, Venues, Venue Groups, Checkins, Tips, Lists, Photos, Specials, Campaigns, Events</li>
	<li><strong>Real-time API</strong> - Notifies venue managers when users check in to their venues, and our user push API notifies developers when their users check in anywhere</li>
	<li><strong>Merchant Platform</strong> - The Merchant Platform allows developers to write applications that help registered venue owners manage their foursquare presence and specials</li>
	<li><strong>Venues Platform</strong> - The Venues Platform allows developers to search for places and access a wealth of information about them, including addresses, popularity, tips, and photos</li>
</ul>
After Foursquare you leave social, getting into the places data world, with popular player <strong><a href="https://simplegeo.com/" target="_blank">SimpleGeo</a></strong>. Similar to Gowalla I was going to overlook SimpleGeo, with their recent <a title="acquisition by Urban Airship" href="http://blog.simplegeo.com/2011/10/31/taking-our-relationship-with-urban-airship-to-a-cruising-altitude/">acquisition by Urban Airship</a>, but I think SimpleGeo is still an important enough of a player, that we should still consider them in the game. SimpleGeo has four distinct web services for location and places:<a href="https://simplegeo.com/" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/simplegeo/simplegeo_logo_200.jpg" alt="" width="200" align="right" /></a>
<ul class="mainlist">
	<li><strong>SimpleGeo Storage</strong> - Storage of data in SimpleGeo system</li>
	<li><strong>SimpleGeo Features</strong> - Features in SimpleGeo represent real-world places such as businesses, regions, or US states</li>
	<li><strong>SimpleGeo Context</strong> - Provides relevant contextual information such as weather, demographics, or neighborhood data for a specific location</li>
	<li><strong>SimpleGeo Places</strong> - Businesses and points of interest</li>
</ul>
In the pure places data game I'd put <strong><a href="ttps://www.factual.com" target="_blank">Factual</a></strong> in the same category as SimpleGeo. Factual has seven location and places APIs:<a href="ttps://www.factual.com" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/factual/factual-logo.png" alt="" width="125" align="right" /></a>
<ul class="mainlist">
	<li><strong>Places Category API</strong>- Taxonomy to classify entities in the various Factual point-of-interest (POI) datasets</li>
	<li><strong>Places CrossrefAPI</strong>- URLs for pages that mention a specific business or point of interest or vice versa</li>
	<li><strong>Places CrosswalkAPI</strong>- Maps third-party (Yelp, Foursquare, etc.) identifiers for businesses or points of interest to each other where each ID represents the same place</li>
	<li><strong>Places Global DatabaseAPI</strong>- 55 million entities in 47 countries</li>
	<li><strong>Places Global Place AttributesAPI</strong>- The latest schema for the global places dataset</li>
	<li><strong>Places ResolveAPI</strong>- Makes partial records complete, matches one entity against another, and assists in de-duping and normalizing datasets</li>
	<li><strong>Places RestaurantsAPI</strong>- Core places attributes in addition to 43 extended attributes on 800,000+ restaurants, bars, and casual eateries including datatypes such as cuisine, ratings, hours of operations, and price</li>
</ul>
Tied with SimpleGeo and Factual is <strong><a href="http://www.infochimps.com/apis/geo" target="_blank">InfoChimps</a></strong>. InfoChimps is a data marketplace player with some very strong location and places services:<a href="http://www.infochimps.com/apis/geo" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/infochimps/infochimps-logo.jpg" alt="" width="175" align="right" /></a>
<ul class="mainlist">
	<li><strong>Wikipedia Articles</strong> - Correlate Wikipedia articles with geographic locations</li>
	<li><strong>Business Places by Locationary</strong> - The Business Places by Locationary API delivers quality business information based on your geographically defined query</li>
	<li><strong>Foursquare Places</strong> - The Foursquare Places API delivers uniquely rich information about venues, worldwide.</li>
	<li><strong>Geonames Places</strong> - The Geonames Places API locates all places within a specified area. Places are any geographic points that can be named</li>
	<li><strong>NCDC Weather</strong> - The NCDC Weather API provides detailed weather data based on your geographically defined query. Weather data points for your query may include dew point, precipitation, snow depth, temperature, visibility, and wind speed details</li>
	<li><strong>American Community Survey (Topline)</strong> - The 2009 American Community Survey (ACS) Topline API provides basic demographic data based on your geographically defined query</li>
	<li><strong>American Community Survey (Drilldown)</strong>- The 2009 American Community Survey (ACS) Drilldown API provides detailed demographic data based on your geographically defined query</li>
	<li><strong>Core Geographic Regions</strong> - The Core Geographic Regions API delivers detailed geodata for any geographically defined query, worldwide</li>
	<li><strong>Zillow Neighborhoods</strong> - Zillow Neighborhoods retrieves geo data pertaining to neighborhoods within defined geometric parameters</li>
	<li><strong>Digital Element IP Intelligence Demographics</strong> - A geolocation API for all your demographics needs. Search by IP address to return data about a geographical area, including number of households, gender, age groups and language</li>
	<li><strong>Digital Element IP Intelligence Domains</strong> - A reverse IP lookup API with 5 fields of search results, all customized to your IP query. Search by IP address to return data about the domain, company, ISP, NAICS industry code and proxy type for an IP</li>
	<li><strong>Digital Element IP Intelligence Geolocation</strong> - A geolocation API with 20 fields of search results, all customized to your IP query. Search by IP address to return data about a geographical area, including country, region, city, internet connection speed</li>
	<li><strong>Geocoding API</strong> - The Geocoding API is a powerful and useful tool that provides location information for any given address in the United States. Geocoding is a process that assigns geographic data (ie, latitude and longitude) to an address</li>
	<li><strong>Latitude Longitude and Zip Code Conversions -</strong> This API returns approximated latitude/longitude centroids for a given zip code, along with the relative city, state, and county</li>
</ul>
Then moving out of pure data players <strong><a href="http://www.yelp.com/developers/documentation/v2/overview" target="_blank">Yelp</a></strong> has always been centered around reviews, and more recently, with version 2.0 of their API moved to be centered around the businesses. Yelp has two places APIs:<a href="http://www.yelp.com/developers/documentation/v2/overview" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/yelp/Yelp_Logo_200.jpg" alt="" width="150" align="right" /></a>
<ul class="mainlist">
	<li><strong>Search API</strong> - Searches for Businesses</li>
	<li><strong>Business API</strong> - Returns full details of businesses</li>
</ul>
Another player in the space is <strong><a href="http://fwix.com/" target="_blank">Fwix</a></strong>. Fwix has a different approach to places, trying to geotag the web. Fwix offers six places and location APIs:<a href="http://fwix.com/" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/fwix/fwix_logo_300.jpg" alt="" width="200" align="right" /></a>
<ul class="mainlist">
	<li><strong>Geotagger API</strong> - Returns places geotagged to a given web page</li>
	<li><strong>Content API</strong> - Returns geotagged content in or near a location</li>
	<li><strong>Categories API</strong> - Returns the list of canonical place categories</li>
	<li><strong>Location API</strong> - Returns geographic data for a latitude/longitude point</li>
	<li><strong>Places API</strong> - Return, Submit and Delete a list of businesses for a given location</li>
</ul>
After Fwix I found a couple of other mapping, location and places data services:
<ul class="mainlist">
	<li><strong><a title="PushPin" href="http://www.pushpin.com/api/1.3/docs/rest/latlng.html">PushPin</a></strong>- The Pushpin Identify Service is a REST service that takes geographic coordinates (latitude and longitude) and resolves them to named locations on the earth</li>
	<li><strong><a title="43 Places" href="http://www.43places.com/about/view/web_service_api">43 Places</a> -</strong>Allows users build 43 Places by adding places, asking questions, giving travel advice, uploading pictures of their favorite places and writing stories about the places they've been and want to go.</li>
	<li><strong><a title="MaxMind" href="http://www.maxmind.com/app/city">MaxMind GeoIP® City Database</a></strong>-Determine country, state/region, city, US postal code, US area code, metro code, latitude, and longitude information for IP addresses worldwide.</li>
	<li><strong><a title="Compass" href="http://compass.webservius.com/documentation.htm">Compass</a> -</strong>Allows access to a database of 16 million business establishments in the USA.</li>
</ul>
These providers either didn't have clear market share or started deviating into other parallel universes of content and services to location and places, so I'm going to stop here.<p></p>
These 17 places and location API providers are a lot to process. I want to spend some time getting a handle on the types of services they offer, before I dive into the peripheral services as well as the players that have less market share. But in my style, I'll keep posting my findings as I pull them together.