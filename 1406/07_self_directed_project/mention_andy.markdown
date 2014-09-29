### ShredSkiBrah (or something else)

#### Pitch

Map backcountry skiing areas to share them with the comunity

#### Description

This would be a map-based backcountry skiing guidebook.  This type of guidebook does not really exist right now, and skiers end up eithe skiing the same old areas or wasting time trying to find new terrain that is both safe and skiable.
* Unauthenticated users could view areas and filter for things like aspect, elevation, and slope angle. They could then get directions, links to the local avalanche forecast, etc.
* Authenticated users could create new areas for skiing and include a series of mandatory (i.e. location and description) details.

This app would have layers for property ownership, slope angle (a common proxy for avalanche stability), and ski recommendations. Each ski recommendation would have elevation, a link to the relevant avalanche forecast, and  contact information for local emergency and managing authorities. these data would be calculated based on the location of the recommendation.


#### Target Audience

Backcountry skiers. [They're](http://www.cbc.ca/news/canada/popularity-of-backcountry-skiing-worries-some-in-industry-1.1313223) [a thing.](http://skiingbusiness.com/15408/features/industry-talks-backcountry-skiing-trend/)

#### Integrations

* This project lends itself to using google as an OAuth provider because google
* This project would use state and national geometries to cover what land is public vs. private
* Probably Mapquest for the routing
* CAIC and their various backcountry zones in order to serve up the latest avalanche forecast
