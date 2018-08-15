# Pet store search

tails.com has conquered the online pet food market, and now we're bringing the world of tailor made food to physical pet stores using our revolutionary new on-site blending technology. To help customers know where our stores are located we need to build a store search feature on the website. This is where you come in.

## The task

1. Render the list of stores from the stores.json file in alphabetical order using a server-side rendered web framework (Flask, Laravel, etc.)
2. Use [postcodes.io](http://postcodes.io) from the server side to get the latitude and longitude for each postcode, and add a Google Static Maps thumbnail image for each store location in the rendered HTML. Clicking the image should take you to the Google Maps page for that result.
3. Implement a "find nearest store" search feature allowing users to enter their postcode and then using the "Nearest outward code for outward code" postcodes.io API to filter stores to those in nearby outward codes and sort them by decreasing distance
4. (BONUS POINTS) Implement #3 as a progressively-enhanced in-page search feature

You should spend no more than 90 minutes on this test. It's not critical you get all the way through the above tasks; just submit whatever you have at the 90 minute mark along with a few notes on how you'd have implemented the remainder.

## Relevant APIs

### Postcodes.io API
* Docs: http://postcodes.io/ (no API key required)

### Google Static Maps API
* Docs: https://developers.google.com/maps/documentation/static-maps/intro
* Key: [register here to generate an API key](https://developers.google.com/maps/documentation/static-maps/get-api-key)

## Store data JSON

Store data is available in the [stores.json](stores.json) file in this repo.

## Submitting
Once you're happy with your code, zip it up and email it back to us along with answers to the following questions:

1. What command do we run to start your server?
2. If you had more time, what improvements would you make if any?
3. What bits did you find the toughest? What bit are you most proud of? In both cases, why?
4. What one thing could we do to improve this test?
