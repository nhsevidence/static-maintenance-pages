# Static Maintenance Pages

> Static HTML Pages used for planned maintenance and system outages

## What is it?

This is to be used on any site that NICE has when planned maintenance is taking place and that particular site needs to be off line.  Ops will point to this page when they take the site down so that users have information about why they can't access the service.

CSS styles, images and mark up are all embedded in the html files. There is only one external dependency which is google fonts.

## Usage

There are 2 files that have different wording depending on the requirement.

### maintenance.html

This is to be used on any site that NICE has when planned maintenance is taking place and that particular site needs to be off line.  Ops will point to this page when they take the site down so that users have information about why they can't access the service. 

*This service is currently unavailable due to maintenance work.
We carry out maintenance work on our services on the last Sunday of each month. Thank you for your understanding and patience.*

### unavailable.html

This is to be used on any site that NICE has when a malicious attack takes place and the site needs to be taken off line to regain control or to take off content that has been put there maliciously.  Ops will point to this page when they take the site down so that users have information about why they can't access the service.

*This service is currently unavailable.*

*We’re working to resolve the issue and hope to have the service up and running again soon. Thank you for your understanding and patience, and apologies for any inconvenience this may cause.*

## Extra Information

Ideally these should be served with HTTP 503 Result code to avoid issues with Google's web crawler.

[https://webmasters.googleblog.com/2011/01/how-to-deal-with-planned-site-downtime.html]()
