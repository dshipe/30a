# 30A Blog & Video Series — Master Content Prompt

This file contains the full prompt for generating all blog posts and HTML pages
in this series. Use it with an AI coding agent (Codex, Claude Code, etc.) to
create or update posts in bulk.

---

```
You are helping create a complete blog and YouTube series about 
Scenic Highway 30A in Florida — the 26-mile stretch of coastal road 
running through South Walton between Panama City Beach and Destin.

═══════════════════════════════════════════════════════════
## GLOBAL RULES (apply to every post)
═══════════════════════════════════════════════════════════

### Research
- Search the web for current information on every place mentioned
- Find the official URL for every restaurant, attraction, and business
- Cross-reference opening status (places close and reopen on 30A)
- Note any facts that need verification before publishing

### Tone & Style
- Warm, first-person travel writing — like advice from a friend who 
  knows the area well
- Include personal observations and tips, not just facts
- Audience: adults planning a 30A vacation (not first-time Florida 
  visitors — they already know what Florida is)
- Each bullet point = one paragraph of 150–200 words

### Linking Rules
- Every restaurant, shop, hotel, and attraction → external link to 
  official website or Google Maps
- Every reference to another 30A beach town → internal link to that 
  post (e.g., `/posts/seaside/` not an external URL)
- External links open in new tab: target="_blank" rel="noopener"

### Output for Each Post
Create THREE files per post in the GitHub repo 
https://github.com/dshipe/30a:

  posts/{town-slug}/index.md      ← Markdown source
  posts/{town-slug}/index.html    ← Standalone HTML (viewable when 
                                     repo is cloned, no build step)
  posts/{town-slug}/README.md     ← Sources, addresses, fact-check 
                                     checklist, YouTube video notes

The HTML files must be self-contained: inline a minimal CSS stylesheet 
(clean, readable, mobile-friendly) so they render beautifully when 
opened directly from a file system. Include navigation links to other 
posts at the top and bottom.

### Front Matter (Markdown)
---
title: ""
date: YYYY-MM-DD
slug: town-slug
tags: [30a, florida, beach, town-name]
description: ""
---

### SEO
Naturally include these phrases in every post:
"30A Florida", "Scenic Highway 30A", "South Walton"
Plus town-specific variants (e.g., "Rosemary Beach 30A restaurants")

═══════════════════════════════════════════════════════════
## REPO STRUCTURE
═══════════════════════════════════════════════════════════

posts/
  index.md                  ← Overview post (section 1a below)
  index.html                ← HTML version of overview
  rosemary-beach/
  inlet-beach/
  alys-beach/
  seacrest-beach/
  watersound/
  seagrove-beach/
  seaside/
  watercolor/
  grayton-beach/
  blue-mountain-beach/
  dune-allen-beach/
  sandestin/
  destin/
  the-beach/                ← "Why come here" posts
  vacation-styles/
  fishing/
  private-beaches/          ← "Things to know" posts
  traffic/
  crowds-and-curfews/

═══════════════════════════════════════════════════════════
## SECTION 1 — BEACH TOWN POSTS
═══════════════════════════════════════════════════════════

---
### 1a. OVERVIEW: Scenic Highway 30A and the Timpoochee Trail
**File:** posts/index.md + posts/index.html

- Introduce the 26-mile road (Scenic Highway 30A) and the 
  Timpoochee Trail that runs alongside it
- List all beach towns west to east with a one-line description 
  and internal link to each detailed post
- Accommodation: very few hotels on 30A — most visitors book 
  vacation rentals through VRBO, Airbnb, or local rental companies. 
  Mention this sets the tone for the experience
- Getting around: parking is limited. Plan on walking, cycling, or 
  renting a golf cart. Note that Rosemary Beach and Alys Beach do 
  not permit golf carts
- Rosemary Beach and Seaside are the most popular towns and the 
  best starting points for first-timers
- The primary reason people come to 30A is the beach — the rest is 
  context for why it's so special

---
### 1b. INLET BEACH
**File:** posts/inlet-beach/

- Located right next to Rosemary Beach but typically offers more 
  affordable rental properties — many are on the north side of 
  Highway 98 rather than directly on the Gulf
- A pedestrian and cycling tunnel runs under Highway 98, connecting 
  the north-side properties to the beach — a small but practical detail
- Excellent area for late afternoon and evening dining. Restaurants to 
  cover with links:
  - [Amigos](find link) — describe cuisine/vibe
  - [Cuvée 30A](find link) — describe cuisine/vibe  
  - [The Donut Hole](find link) — known for breakfast and key lime pie; 
    a 30A institution worth the wait
- Kids' playground at 
  [19 Windward Lane, Inlet Beach](https://maps.google.com/?q=19+Windward+Ln,+Inlet+Beach,+FL+32461) — 
  well-equipped and popular with families staying nearby

---
### 1c. ROSEMARY BEACH
**File:** posts/rosemary-beach/
*(A draft already exists in the repo — update and enhance it rather 
than rewriting from scratch)*

- European character: cobblestone pedestrian lane to the beach, 
  wrought-iron balconies, whitewashed architecture — unlike anywhere 
  else on 30A
- Barrett Square: the social heart of the village; boutique shops, 
  restaurants, and a genuinely walkable atmosphere. Research and 
  link to current notable shops
- Dining (link all):
  - [Restaurant Paradis](https://rosemarybeach.com/restaurants-in-rosemary-beach/restaurant-paradis-in-rosemary-beach/) — fine dining, Southern-influenced, evenings only
  - [Pescado Seafood Grill & Rooftop Bar](https://rooftop30a.com/) — rooftop with Gulf views, eclectic menu; arrive early for sunset seating
  - [La Crema Tapas & Chocolate](https://lacrematapas.com/) — tapas and chocolate, good for a light meal; popular and often crowded, tip on best times to visit
  - [Playa Bowls](https://www.playabowls.com/) — casual açaí bowls, popular with families and cyclists
- No golf carts permitted — the town runs on bicycles. Mention 
  [Bamboo Bicycle Company](https://rosemarybeach.com/explore-rosemary-beach/things-to-do/bicycles/) for rentals
- [The Pearl Hotel](https://www.thepearlrb.com/) — one of the very 
  few true hotels on 30A; Forbes Four-Star, AAA Four-Diamond, adult-oriented
- [The Hidden Lantern Bookstore](http://thehiddenlantern.com) — 
  independent bookshop on Barrett Square; books, games, gifts

---
### 1d. ALYS BEACH
**File:** posts/alys-beach/

- The newest and most expensive community on 30A; all-white 
  Moorish-influenced architecture that gives it an almost surreal, 
  otherworldly quality
- [Caliza Restaurant & Pool](https://www.alysbeach.com/caliza/) — 
  the centrepiece of Alys Beach; stunning courtyard pool and restaurant; 
  describe the atmosphere and menu style
- Long-time dining favourites (link all):
  - [Fonville Press](find link) — describe cuisine and atmosphere
  - [George's at Alys Beach](find link) — describe
- A nature trail winds through the community; describe the experience 
  and what to look for
- Like Rosemary Beach, no golf carts permitted — bicycles are the 
  way to get around

---
### 1e. SEACREST BEACH
**File:** posts/seacrest-beach/

- Seacrest Beach spans two areas: the main section sits between 
  [Rosemary Beach](internal link) and [Alys Beach](internal link); 
  a larger secondary section lies between Alys Beach and 
  [WaterColor](internal link)
- The main section includes the best free public parking for 
  Rosemary Beach: behind Peddler's Pavilion — note that it involves 
  a walk, so factor that in
- The secondary section (between Alys and WaterColor) may offer more 
  affordable rental properties as it's further from the primary hubs
- Dining:
  - [Crabby Steve's](find link) — hidden gem accessible only from 
    the beach; describe how to find it and what to expect
  - Several dining options inside [Peddler's Pavilion](find link) — 
    list the current ones with links

---
### 1f. WATERSOUND
**File:** posts/watersound/

- Watersound Beach is a private gated community but still offers 
  vacation rental properties with beach access — explain the 
  experience of staying there
- Watersound Origins is a newer development by [St. Joe Company](find link) 
  on the north side of Highway 98; may offer more affordable rental 
  prices with access to community amenities
- The primary food and activity hub is 
  [The Hub at 30A](find link) — formerly known as The Big Chill:
  - Multiple food options (research and list current vendors)
  - Nightly family activities and entertainment
  - Shopping
  - Usually has parking available — a genuine convenience on 30A

---
### 1g. SEAGROVE BEACH
**File:** posts/seagrove-beach/

- A personal favourite for accommodation on 30A: close enough to 
  walk, cycle, or golf-cart to [Seaside](internal link), but with 
  noticeably more affordable rental prices
- Has the largest public beach accesses on 30A — the main ones from 
  Highway 395 and east along 30A; describe what to expect
- Dining (link all):
  - [Surfing Deer](find link) — describe
  - [Café 30A](find link) — describe
  - [The Perfect Pig](find link) — the original location; describe 
    what makes it the favourite among the several Perfect Pig spots
- [The Lodge at Greenway Station](find link) — one of the few hotels 
  on 30A; describe the property briefly

---
### 1h. SEASIDE
**File:** posts/seaside/

- The cultural heart of 30A; [Smolian Circle](find link) is the 
  central gathering place surrounded by shops, restaurants, and open 
  green space
- Parking: as of 2018, parking on Smolian Circle is no longer 
  permitted. Park at Quincy Circle (paid, approx. $10) — note the 
  no in-and-out policy, so plan to stay once you've parked. 
  Alternatively, use the Grayton Beach shuttle
- Dining (link all):
  - **Airstream Row** — a line of converted Airstream trailers 
    serving BBQ, grilled cheese, hot dogs, and crepes. An absolute 
    must-visit. Highlight [Crêpes de Soleil](find link) for the 
    FFrose crêpe — a signature item and crowd favourite
  - [Pickles](find link) — the go-to burger spot in Seaside
  - [Great Southern Café](find link) — legendary vanilla pancakes; 
    the kind of breakfast you talk about for years
  - [Bud & Alley's](find link) — rooftop bar with Gulf of Mexico 
    views; the best place to watch a 30A sunset with a drink in hand
- [Amavida Coffee](find link) — the 30A coffee institution; 
  great for a morning cup before hitting the beach
- [Sundog Books](find link) — independently spirited bookshop with 
  books, vinyl records, and curiosities; a genuine 30A landmark
- [Duckies](find link) — kids' toy store famous for LED helicopters; 
  children can be seen flying them in the central grassy area — 
  a charming and memorable Seaside sight

---
### 1i. WATERCOLOR
**File:** posts/watercolor/

- [WaterColor Boathouse](find link) — the place to rent kayaks and 
  paddleboards for exploring Western Lake; describe the experience
- Walking trails worth highlighting:
  - Cerulean Park trails
  - The bridge across Western Lake — describe the views and the walk
- [WaterColor Inn](find link) — one of the few hotels on 30A; 
  describe the property and who it suits
- Staying in WaterColor grants access to the Beach Club on the Gulf 
  and to Camp WaterColor (pools, lazy river) — a significant benefit 
  over standard vacation rentals in the area
- Dining (link all):
  - [Wine World](find link) — excellent outdoor seating in a relaxed 
    setting (note: not beachfront, but charming)
  - [Fish Out of Water](find link) — long-time favourite; describe
- **Truman Show connection:** Watercolor and the adjacent Seaside were 
  used as the fictional town of Seahaven in the 1998 film *The Truman Show*. 
  The Truman Show house is at 
  [31 Natchez Street, Santa Rosa Beach, FL 32459](https://maps.google.com/?q=31+Natchez+St,+Santa+Rosa+Beach,+FL+32459) — 
  a fun stop for film fans

---
### 1j. GRAYTON BEACH
**File:** posts/grayton-beach/

- The soul of 30A — the oldest community on the highway. Motto: 
  *"Strange people, nice dogs."* Describe the character of the place
- Grayton Beach offers parking and a shuttle service into both 
  Grayton and [Seaside](internal link) — useful to know during busy 
  periods
- Dining (link all):
  - [The Red Bar](find link) — a 30A institution that burned down 
    and was rebuilt, returning with exactly the same beloved vibe; 
    describe what makes it special
  - [Chiringo](find link) — describe
- You can drive on the beach with a permit — one of the few places 
  on 30A where this is possible; explain the permit process
- The beach is adjacent to Western Lake. Occasionally the lake 
  outflows to the Gulf, creating an unusual passage where people 
  swim, kayak, and paddleboard between the lake and the sea
- [Grayton Beach State Park](find link):
  - Famous for its ancient, gnarly coastal dune lake vegetation 
    and iconic old-growth trees
  - Offers both cabin rentals and camping
  - One of the best public beach options on 30A

---
### 1k. BLUE MOUNTAIN BEACH
**File:** posts/blue-mountain-beach/

- Named for the blue lupine wildflowers that once blanketed the 
  dunes here — one of the highest natural points on the Gulf Coast
- Dining (link all):
  - [Red Fish Taco](find link) — a solid, casual option usually 
    without a significant wait; describe the menu
  - [Blue Mountain Creamery](find link) — a long-time local 
    favourite for ice cream; describe what makes it worth the stop

---
### 1l. DUNE ALLEN BEACH
**File:** posts/dune-allen-beach/

- Gulf Place has undergone significant change in recent years. 
  The formerly quiet, arts-focused area — home to an Artist's Market 
  and small independent businesses — was acquired by the owners of 
  Alvin's Island and transformed into a livelier, beach-bar-oriented 
  destination. Not universally beloved by long-timers, but worth 
  understanding before you visit
- Dining (link all):
  - [The Perfect Pig at Gulf Place](find link) — one of several 
    locations; considered by many to be the best, particularly for 
    breakfast. Describe what to order
  - [Skunk Gulley](find link) — excellent Gulf of Mexico views from 
    the deck overlooking the Ed Walline beach access; describe the vibe

---
### 1m. SANDESTIN
**File:** posts/sandestin/

- Named because it sits geographically between Santa Rosa Beach 
  and Destin — a large resort community rather than a small town
- Key areas and attractions (link all):
  - [Village of Baytowne Wharf](https://www.baytownewharf.com/) — 
    dining, shopping, entertainment, nightly events
  - [Grand Boulevard](https://grandboulevard.com/) — upscale outdoor 
    shopping and dining complex
  - [Silver Sands Premium Outlets](https://www.premiumoutlets.com/outlet/silver-sands) — 
    one of the largest outlet malls in the Southeast
  - The Whale's Tail Bar — beach bar with a Gulf webcam available 
    live at [this YouTube feed](https://www.youtube.com/watch?v=TyX02EtQcYI)
- Dining: [Pompano Joe's](find link) — the original beachfront 
  location; a Florida Panhandle institution

---
### 1n. DESTIN
**File:** posts/destin/

- [HarborWalk Village](https://www.harborwalkvillage.com/):
  - Jet ski, kayak, and paddleboard rentals
  - Dolphin tours and sunset cruises
  - [Tailfins](https://tailfinsdestin.com/) — waterfront dining
  - [Dewey Destin's](https://www.destinseafood.com/) — will cook 
    your fresh catch from a fishing charter; describe how it works
- [Big Kahuna's Water & Adventure Park](https://bigkahunas.com/destin/) — 
  waterslides and amusement rides; popular with families
- [The Track](https://www.destinfwb.com/listing/the-track/71/) — 
  go-karts and family entertainment
- Henderson Beach State Park — describe the park, beach access, 
  and why it's worth a visit
- Crab Island — the famous submerged sandbar in Destin Harbor; 
  describe how to get there (water taxi/boat) and what to expect

═══════════════════════════════════════════════════════════
## SECTION 2 — WHY COME HERE
═══════════════════════════════════════════════════════════

---
### 2a. THE BEACH
**File:** posts/the-beach/

- The sand: almost pure white quartz, washed down from the 
  Appalachian Mountains over millennia. No rocks. No shells to 
  injure bare feet (though this also means poor shell-hunting). 
  Often no seaweed — just clean, clear water and brilliant white sand
- Why the water is emerald: the white sand reflects sunlight upward 
  through the shallow water, creating the distinctive emerald-green 
  colour. You genuinely have to see it to believe it. On a calm day 
  it looks like a Caribbean lagoon
- This is known as the Emerald Coast for a reason — the water clarity 
  rivals anything in Florida

---
### 2b. A VACATION FOR EVERY STYLE
**File:** posts/vacation-styles/

- Panama City Beach is the party destination and Spring Break 
  epicentre. MTV filmed Spring Break there throughout the 1990s. 
  Loud, fun, and unapologetically commercial
- Destin is the family-friendly option: water parks, go-karts, 
  amusement attractions, a massive fishing fleet
- 30A is the adult oasis between the two — quieter, more design-
  conscious, focused on food, nature, and the beach. It closes at 
  10pm and it's not trying to be anything else

---
### 2c. FISHING
**File:** posts/fishing/

- Destin has historically been called "the world's luckiest fishing 
  village" because the continental shelf narrows sharply just offshore, 
  bringing deep water — and large fish — unusually close to land
- Destin is home to the largest recreational sport fishing fleet in 
  the United States
- The [Destin Fishing Rodeo](find link) runs every October — one of 
  the largest fishing tournaments in the country; describe it and how 
  to participate or spectate

═══════════════════════════════════════════════════════════
## SECTION 3 — THINGS TO KNOW BEFORE YOU GO
═══════════════════════════════════════════════════════════

---
### 3a. PRIVATE BEACHES — What Happened and What to Do About It
**File:** posts/private-beaches/

This is important enough to warrant a clear, balanced explanation.

- Historical context: Rosemary Beach and Seaside have always had 
  private beach areas for residents and their guests. In Seaside, 
  visitors can rent chairs and umbrellas for the day to gain access, 
  but cannot bring a cooler
- The larger issue began when the county allowed commercial vendors 
  to set up beach chair rentals in front of private properties. 
  Homeowners objected — former Arkansas Governor Mike Huckabee was 
  among those who pushed for restricted access
- Today, much of the beach along 30A has been designated private. 
  This includes areas that were previously public: Seagrove, 
  Seacrest, and even the Watercolor Natchez Beach Access
- Practical impact on renters: properties not on the beachfront may 
  advertise "beach access" which sometimes means only physical access 
  to the water — not the right to set up chairs and umbrellas. 
  Verify before you book
- Authoritative sources for the ongoing situation:
  - [SoWal forum thread on private beaches](https://sowal.com/forum/threads/private-beaches-in-south-walton-customary-use-updates-sb1622.113172/)
  - [SoWal article on beach chair rentals](https://sowal.com/story/the-latest-on-beach-chair-umbrella-rentals-in-south-walton)
- Solutions:
  - Check the county's publicly available beach access map before 
    booking (link to current Walton County resource)
  - Visit [Deer Lake State Park](find link) or 
    [Grayton Beach State Park](find link) — entrance fee is under $10, 
    you can enter and exit freely, and you'll have genuine space on 
    a beautiful public beach

---
### 3b. TRAFFIC
**File:** posts/traffic/

- 30A was never designed for the volume of traffic it now carries. 
  For anything more than a short hop, take US Highway 98 which runs 
  parallel to 30A — it's faster and less congested
- Parking in Seaside is its own challenge:
  - Since 2018, parking around Smolian Circle is no longer free — 
    Quincy Circle behind it charges approximately $10
  - No in-and-out policy: once you pay, you're committed to staying
  - Even with paid parking, availability is tight in summer
- The free parking lot near the Natchez Beach Access in WaterColor 
  fills quickly given its short walk to the beach
- Pedestrian safety note: until recently there was an informal 
  understanding that cars would stop for pedestrians crossing 30A. 
  That norm has eroded. Exercise caution at crosswalks, even 
  marked and illuminated ones
- Solutions:
  - Use the Seaside parking and shuttle from Grayton Beach
  - Park behind Peddler's Pavilion for Rosemary Beach (free but 
    involves a walk)
  - Rent a golf cart (not usable in Rosemary Beach or Alys Beach)
  - Rent bicycles — the 18.6-mile Timpoochee Trail connects most 
    communities
  - Walk where possible — 30A rewards slow travel

---
### 3c. CROWDS AND CURFEWS
**File:** posts/crowds-and-curfews/

- After pandemic-related closures lifted in May 2020, Florida 
  became effectively the only major travel destination open in the 
  US. Tourism to 30A, Destin, and Panama City Beach surged 
  dramatically and has never fully retreated to pre-2020 levels
- A simultaneous housing boom — driven by remote work, low mortgage 
  rates, and urban flight — brought significant construction and a 
  new wave of tourism to the area
- Spring break crowds became a genuine problem: 30A businesses 
  close at approximately 10pm (often winding down by 9:30pm). The 
  area is not designed for nightlife. Large groups of spring 
  breakers with nowhere to go resulted in well-documented scenes of 
  crowds milling around a closed Seaside after midnight
- As a result, several 30A communities implemented spring break 
  curfews for minors
- Practical advice:
  - Spring breakers will have a better time in Panama City Beach 
    or Destin — both stay open later and have the infrastructure 
    for that kind of trip
  - For the best 30A experience, avoid peak spring break (typically 
    mid-March through early April) and major summer holiday weekends
  - Early May and late September offer warm water, warm weather, 
    and noticeably thinner crowds — arguably the best time to visit

═══════════════════════════════════════════════════════════
## FINAL DELIVERABLES CHECKLIST
═══════════════════════════════════════════════════════════

For each of the 22 posts above, create:
- [ ] posts/{slug}/index.md
- [ ] posts/{slug}/index.html (self-contained, works offline)
- [ ] posts/{slug}/README.md (sources + fact-check list)
- [ ] images/ subfolder with placeholder references and sourcing notes

Additionally:
- [ ] Top-level README.md with series overview and post index
- [ ] Shared CSS file at assets/style.css referenced by all HTML files
- [ ] Navigation bar in every HTML file linking to all other posts

## Spelling and Name Corrections Applied
| Original | Correct |
|---|---|
| secnic highway | Scenic Highway |
| panana city beach | Panama City Beach |
| Barret square | Barrett Square |
| Timpoochee | Timpoochee (verify current official spelling) |
| aloud | allowed |
| Carribean | Caribbean |
| Applacian | Appalachian |
| crab isalnd | Crab Island |
| Silvar Sands | Silver Sands |
| restuarant | restaurant |
| hghway | highway |
| favorita | favourite |
| FFrose | verify actual menu item name at Crêpes de Soleil |
```
