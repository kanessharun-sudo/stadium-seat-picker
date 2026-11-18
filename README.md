# Stadium Seat Picker

A real-time 3D stadium where you pick a stand, a block and a seat, fly down to it, and get a ticket showing the view from that exact seat. One HTML file, built on three.js.

## What it does

- Draws every seat in a single instanced mesh, up to about 132,000 seats, each with its own stand, block, row and number.
- Three-step pick: stand, block, seat. Prices and seats left show on hover. Sold seats turn grey.
- The camera flies to the seat you click. The ticket image is rendered live from that seat.
- Skybox upgrade moves you into the VIP box above the lower tier.
- Six sports: football, cricket, hockey, athletics, tennis, basketball.
- Five generic stadium types, plus an "add your own stadium" field saved in the browser.

## Real stadiums

Eight real venues are included: Wembley Stadium, Spotify Camp Nou, Narendra Modi Stadium, M. Chinnaswamy Stadium, Jawaharlal Nehru Stadium (Delhi), Birsa Munda Hockey Stadium, Arthur Ashe Stadium and Madison Square Garden.

Each model matches the venue's published capacity (within about 2%), sport, tier count and stand or end names. The geometry is generated to fit those facts. It is not a survey of the building, and block and seat numbering is not the venue's own. Tier splits are estimated where no published split exists. The setup panel states what was estimated for each venue.

## Demo only

Prices, availability and fixtures are invented. Nothing is booked and no payment is taken. This project has no link to any venue, club, league or ticket seller.

## Run it

Open `index.html` in a current browser. three.js loads from cdnjs, so you need a connection the first time. No build step.

## Credits

Built by Sharun Kanan, with Claude (Anthropic) writing the code. The seat-picker concept follows Omnya Lab's free stadium blueprint. This version is a real-time build and shares no code or assets with it.
