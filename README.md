# NC Midterm Election 2018

This project is intended to help people in North Carolina learn about the election this November 6th by presenting the districts according to which the positions up for election are elected as an interactive map and by displaying the name of the district, the candidates up for election for the office or offices pertaining to that district as well as those candidates' party affiliations on the ballot, and other important information in a popup balloon when a user clicks or taps a district.

By presenting this information in an interactive visual manner, I hope that people can become more engaged with politics, as they will be able to observe the boundaries of the districts and determine which districts they live in, which electoral precinct they live in, and even their polling place without having to go out of their way to ask each question.  You don't have to ask "Which Superior Court district do I live in?" or "Is my least favorite barbershop inside the same state senate district as my home?" (not that anyone would ever think to ask that sort thing), and instead you can simply explore the district maps and learn whatever information interests you.

The interactive map can be found here: https://fiveham.github.io/NC-elections/all-districts

## About the Map

The map includes layers for

* State House
* State Senate
* Statewide offices/issues
* Prosecutorial districts (as in "district attorney")
* Congressional districts (US House)
* Counties (local offices not available countywide are included)
* Superior Court districts
* District Court districts
* Precincts
* Polling Places

Choose a layer from the dropdown menu labeled "Choose Map" on the left.

### Features

* Maps for every\* district type
    * Learn of offices you didn't know existed!
    * \*Except Soil and Water Conservation districts, whose supervisors are elected per county
* Address search bar
    * Jump to an address and check who's running for what offices around there
* URL parameters
    * Link someone to a specific location and zoom level on the map and even choose which layer!
    * Details below
* Geolocator button
    * Jump to your location and explore the districts around you

### URL Parameters

Four parameters are supported:
* layer
* lat
* lng
* zoom
 
#### layer

`layer` can `=` any of 

* `house`
* `senate`
* `statewide`
* `prosecutorial`
* `congress`
* `county`
* `superior`
* `district`
* `precinct`
* `pollingplace`

This parameter determines the map layer that is displayed when the page loads.

#### lat, lng

`lat` and `lng` can `=` any latitude and longitude, respectively and determine the initial latitude and longitude where the map is centered when the page loads.

#### zoom

`zoom` can `=` any integer number from 0 to 22 and determines the initial zoom level when the page loads.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Warning

This project should not be trusted as the final word on any of the election information that it presents.  Before taking any action based on that information, you should verify it independently from official sources.

To officially determine which districts you are able to vote in, if you are already registered to vote, [look up your voter registration information](https://vt.ncsbe.gov/RegLkup/) with the state board of elections.  The "Jurisdictions" section lists all the districts that pertain to you, and the "Sample Ballots" section lists any sample ballots that pertain to you, once they become available.

If you are not registered to vote, you can officially determine which precinct and polling place pertain to you by [looking up your Precinct and Polling Place](https://vt.ncsbe.gov/PPLkup) according to your address.  Polling place lookup results include sample ballots once those are available, which can officially tell you who's running for what.

If you are not registered to vote but you want to be registered, you just need to fill out a [voter registration form (PDF)](https://www.ncsbe.gov/Portals/0/Forms/NCVoterRegForm06W.pdf), physically sign it, and mail it (or deliver it in person) to [your county board of elections.](https://vt.ncsbe.gov/BOEInfo/)

To determine which candidates are running for which offices, sample ballots, once they are available, are naturally an official source for that information.
