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

44 real venues, grouped by sport:

- Football: Wembley, Spotify Camp Nou, Santiago Bernabéu, Signal Iduna Park, Allianz Arena, San Siro, Maracanã, Estadio Azteca, Old Trafford, La Bombonera
- American football: AT&T Stadium, SoFi Stadium, Lambeau Field, Arrowhead Stadium, Caesars Superdome, Mercedes-Benz Stadium, Allegiant Stadium, MetLife Stadium, Lumen Field, U.S. Bank Stadium
- Cricket: Narendra Modi Stadium, Melbourne Cricket Ground, Lord's, Eden Gardens, The Oval, Adelaide Oval, Wankhede Stadium, M. Chinnaswamy Stadium, Optus Stadium, Dubai International Cricket Stadium
- Ice hockey: Bell Centre, SKA Arena, Madison Square Garden, United Center, Little Caesars Arena, Scotiabank Arena, Rogers Place, Lanxess Arena, T-Mobile Arena, Climate Pledge Arena
- Other: Jawaharlal Nehru Stadium (Delhi), Birsa Munda Hockey Stadium, Arthur Ashe Stadium, Madison Square Garden (basketball)

Each model is generated from a short spec: published capacity, sport, bowl shape, tiers present on each side, open ends, and roof type. Seat counts land within a few percent of the published capacity. The geometry is not a survey of the building, block and seat numbering is not the venue's own, and tier splits and seat colours are estimates. The setup panel says so for each venue. Indoor arenas and domes are drawn with an open roof frame so the bowl stays visible.

## Demo only

Prices, availability and fixtures are invented. Nothing is booked and no payment is taken. This project has no link to any venue, club, league or ticket seller.

## Run it

Open `index.html` in a current browser. three.js loads from cdnjs, so you need a connection the first time. No build step.

## Credits

Built by Sharun Kanan, with Claude (Anthropic) writing the code. The seat-picker concept follows Omnya Lab's free stadium blueprint. This version is a real-time build and shares no code or assets with it.
