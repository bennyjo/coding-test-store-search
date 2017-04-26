# Pet store search

We've decided to roll tails.com out to physical stores using revolutionary new on-site blending technology, and we need to build a store search feature on the website.

## The task

1. Render the list of stores from the stores.json file in alphabetical order using a server-side rendered web framework (Flask, Laravel, etc.)
2. Use postcodes.io to get lat/lon for each postcode and add a Google Static Maps thumbnail image for each store location. Clicking the image should take you to the Google Maps page for that result.
3. Implement a "find nearest store" search feature allowing users to enter their postcode and then using the "Nearest outward code for outward code" postcodes.io API to filter stores to those in nearby outward codes and sort them by decreasing distance
4. (BONUS POINTS) Implement #3 as a progressively-enhanced in-page search feature

## Relevant APIs

Postcodes.io API
Docs: http://postcodes.io/

Google Static Maps API
Docs: https://developers.google.com/maps/documentation/static-maps/intro
Key: AIzaSyDon4-e-bpiSpcNYQX7UmgQlHikkyWa2qE


## Store data JSON

https://pastebin.com/ZG0fSJd4
