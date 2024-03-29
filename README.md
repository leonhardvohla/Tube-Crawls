# Tube Crawls
An interactive app showing the nearest cheapest pint to each tube station inspired by this [blog post](https://store.storekit.com/advice/map-of-london-underground-by-the-cheapest-pint/) by Adam Stead. Easily upgradeable when the tube network changes, as it's built on top of the official TfL tube map svg available on their [website](https://tfl.gov.uk/Modules/TubeMap?nightMode=false).

The GitHub Pages hosted site is only the static front-end, all server functions with JavaScript promises were handled with node.js which can't be executed on GitHub Pages. See demo video below to get an impression of the full functionality.

## Demo Video
https://user-images.githubusercontent.com/5860469/153896308-5ab4e4e2-310f-4086-8cc0-4aa1ad1b0e89.mov

<!--## Features
- [ ] User can calculate different pub crawl routes with different options
    - [ ] Choose starting point
    - [ ] Duration
    - [ ] Price (cheap, medium, expensive) (max price input)
    - [ ] Allow skipping stations or not
    - [ ] Allow changing to different line
    - [ ] Toggle to include only night tube
    - [ ] Save crawl to database
    - [ ] Remember last crawls through sessions
- [ ] Click on station shows more information about pub and pint
    - [ ] fetched from Wikipedia, OpenStreetMap
    - [ ] Name of Pub
    - [ ] Name (?) and price of beer
    - [ ] Option for users to add another pub/another beer
- [ ] Simulate pub crawl because of closed pubs
    - [ ] Figure travels along the route in real time, gets on and off at stations
    - [ ] Notification, when next pint is due
    - [ ] Allow multiple users to share session over the internet
    - [ ] Dial to speed up simulation
    - [ ] Information about how much money saved, which option to donate
    - [ ] Figure in the corner gets progressively more drunk
    - [ ] Generate shopping list with link to online supermarket for each beer en route
- [ ] Name Ideas
    - [ ] tubecrawler (.com not available)
    - [ ] thetubecrawler
    - [ ] tubepubcrawl
    - [ ] pintcrawler
    - [ ] tubepints
    - [ ] undergroundcrawler
    - [ ] tflcrawler
- [ ] Include other maps
    - [ ] Rent
    - [ ] Most used hashtags

## Todo
- [ ] Set boundaries for map panning
- [ ] Reset zoom button
- [ ] Make regex more concise
- [ ] Set cursor to pointer when hovering over station
- [ ] Edgware Road id with testcase, Shepard's Bush
- [ ] Make station points clickable (not just names)
- [ ] Rewrite station selector to get rid of undefined replace
- [ ] Change server.js, handler.js to work with promise instead
- [ ] Add different handlers depending on if just asking for one station or a cawl
- [ ] Zoom option
- [ ] Limit panning
- [ ] Expand panning limit to allow selection in top left corner

## Progress
- Defined brief and wrote README
- Set up all the initial configuration, based on Freddie's server


## Debugging
- scale 1, border 110/162,
- scale 2, border 733/613, 623/450
- scale 3, border 1355/1063, 622/450
- scale 4, border 1980/1521, 625/458-->
