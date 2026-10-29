# Bald Eagle Flight

An animated 3D scene of an American bald eagle (*Haliaeetus leucocephalus*) over a lake. The day loops continuously, with weather, wildlife and a lakeside campsite. Everything lives in a single file, `bald-eagle-flight.html`, built with [three.js](https://threejs.org/) r128.

![The eagle skimming low over the misty lake in the early morning in front of the waterfall and its stream, with the nest pine, the beavers' lodge and a feeding moose on the left, ducks, an otter and a heron on the water, a dewy spider's web and the turtles' log in front, and on the right-hand shore the campers by their tent, where he's casting from the water's edge](docs/screenshot.png)

## Running it

Open `bald-eagle-flight.html` in a modern browser, either straight from disk or through any web server (for example `http://localhost/bald-eagle-flight.html`). There is no build step. The page loads three.js from cdnjs and its fonts from Google Fonts, so it needs an internet connection.

## Controls

| Control | Action |
| --- | --- |
| Drag (mouse or one finger) | Look around the eagle |
| Mouse wheel (or trackpad pinch) | Zoom in or out |
| Double-click / double-tap, or `R` | Reset the view and zoom |
| `1` / `2` / `3` | Camera distance: Close (3.2 m), Away (9 m) or Far away (30 m) |
| `F` | Follow the eagle on a tour of the whole landscape |
| `E` | Eagle's-eye view, riding just ahead of the beak |
| `L` | Look around: leave the eagle and glide slowly round the lake |
| `M` | Sound on or off (off by default) |

In Look around, the camera leaves the eagle to itself and drifts on a slow, curving loop of about two minutes. It starts at a vantage behind the tent, looking over the campsite to the lake. Then it swings behind the camp and along the far shore past the deer and over the beavers' lodge, turns to the snag and up to the eagles' nest, and rounds the left end of the lake past the moose (when he's in the water) and the otters' rock to the heron in the shallows. It glides low across the water, high enough to clear the canoe, and curls back round to the tent. Once a lap, if the fox or owl is out, the camera leaves the loop to watch it from a little way off, then glides back to where it left off. It rises above the treetops before it travels. For the fox it zooms in close; for the owl it watches the whole circling loop. The nights are short, so the two take turns to go first. The camera keeps its gaze on the deer, the moose and the heron as they move, leans gently into the curves and eases in and out of the mode over ten seconds. Dragging turns its head, the mouse wheel zooms, and `R` or a double-click puts both back.

The card in the top-left corner shows how far the eagle is from the camera, the time of day, the weather and when the northern lights are out.

## What's in the scene

### The eagle

- Built life size, with a wingspan of about 2.2 m. It has a dark brown body, a white head and tail, a hooked yellow beak and spread "finger" primaries.
- Flies with slow, deep wingbeats between long glides and banks into its turns.
- **Fishing:** it picks out one of the fish visible under the surface and dives on it. It skims the water with its talons forward, snatches the fish with a splash and carries it either to a dead tree on the far-left shore, where it eats it, or home to its nest to feed the eaglets. Either way it dips its head to tear at the fish, then takes off again.
- **The nest:** a big platform of sticks in the top of a tall pine behind the far-left shore. The eagle's mate, a little larger, stands guard on the rim with its wings folded, scanning the valley. Two downy grey eaglets sit in the cup. When a parent comes in with food they crane up with their beaks open, begging, and the mate calls the eagle in. The eaglets doze at night.
- **Storms:** it waits out thunderstorms perched on the dead tree.
- **Robbing the osprey:** when the osprey climbs away from the lake with a fish and the eagle is nearby, the eagle often gives chase round the osprey's circle. It harries the osprey until it lets go of the fish, then drops on the fish and snatches it out of the air, and carries it off to the snag or the nest as if it had caught it itself.
- **Neighbours:** at night it swoops low over the fox twice, and when its flight brings it near the owl it chases it round its loop. The deer bolt when it comes in low near them, and the beavers, turtles and loon dive for cover when it swoops low over the water.

### Wildlife

- **Deer:** a herd of four, one of them a buck with antlers. They graze, look around, amble about and walk down to the lake to drink. They keep a wary eye on the fox.
- **Mallards:** three ducks paddling about the lake, each trailing a faint wake. The lily pads bob as they pass.
- **Water lilies:** some of the pads carry a white water lily, which opens in the morning and closes again at dusk.
- **Common loon:** rides low on the open water with its chick on its back. It dives for fish, leaving the chick bobbing on the surface, and comes up somewhere else, sometimes with a fish. Then it swims back and the chick climbs aboard again. Once a day, in the late morning, it swims to the left end of the lake and makes its long, pattering, splashing run to take off. It circles out over the trees on both sides of the valley and comes back in on a long skidding landing. If the eagle comes in low nearby, it gives its tremolo and dives with the chick.
- **Moose:** a bull with broad, flat antlers walks out of the trees on the left before dawn and wades into the shallows among the lily pads. He dunks his whole head under to feed, hauls it up with water streaming off his muzzle, and stands chewing and looking about before the next dunk. By mid morning he wades out and goes back into the trees.
- **Frogs:** green frogs sit on some of the lily pads and bob with them. They croak, mostly after dark, puffing out their throats, and every so often hop across to a free pad nearby, which rocks as they land. When a duck, the loon, the heron, the moose or the canoe comes close, they leap into the water with a plop, then climb back onto their pads a while later.
- **Dragonflies:** on fine, sunny days they hover over the lily pads and dart suddenly from spot to spot, their glassy wings a blur.
- **Butterflies:** monarchs, whites, sulphurs and blues flutter over the meadow round the shore on fine days, settling on the flowers with their wings slowly opening and closing.
- **Osprey:** on fine days it comes in over the trees to fish. It circles high over the lake, hangs on quick wingbeats to look down, then drops feet first with a great splash. It labours up out of the water with the fish held head first, shakes off the water and climbs away in a wide circle before carrying it off.
- **Beavers:** a pair live in a lodge of sticks and mud beside the stream mouth. From dusk until after dawn they come out to nose about where the stream runs into the lake, a little way up the stream and in the shallows off its mouth, dipping their noses into the water. Often they then swim on along the shore, trailing a wake, gnaw off a leafy branch and tow it home, diving at the lodge to take it in. If the eagle swoops in low or the canoe comes close, one slaps the water with its tail with a loud crack and they both dive.
- **River otters:** a pair porpoise and chase each other round the left half of the lake by day, rolling over as they go. Every so often they haul out together on a rock to rest, one grooming while the other looks about.
- **Painted turtles:** a row of them basks on a half-sunk log off the near shore on fine days. When anything swims or wades close, or the eagle swoops low, they slide off one by one with a plop and climb back out a while later.
- **Belted kingfisher:** watches from a dead stick in the shallows of the far shore. It flies out with a rattling call to hover over the water, plunges in head first and flies back, sometimes with a minnow, which it beats on the perch before swallowing it.
- **Black bear:** every morning it comes out of the trees beyond the meadow and wades into the middle of the stream to fish. It stares into the water, swipes a paw down with a splash or rears up and pounces with both front paws, and now and then comes up with a fish and eats it. It fishes until dusk, then ambles back into the trees. On some days (never before northern-lights nights) it leaves the stream after lunch instead and crosses the meadow to the berry bushes behind the camp, sometimes rearing up on its hind legs to reach, and in the evening wanders on into the camp.
- **Wolves:** never seen, but on some nights a pack howls from the hills behind the lake, and the deer stop and lift their heads to listen.
- **Chipmunks:** two dash about the camp by day, stopping to sit up and look about, and scurrying out from under the campers' feet.
- **Pileated woodpecker:** works its way up the dead snag by day in short hops, hammering at the wood and now and then drumming, then swoops back to the foot of the trunk to start again. It keeps clear while the eagle is on the snag.
- **Hummingbird:** a ruby-throated hummingbird zips between the wildflowers round the camp, hanging in front of each on a blur of wings. Every so often it comes to hover right in front of one of the campers' faces.
- **Raccoon:** on some nights, once the campers are asleep, it creeps out from behind the tent, pries the lid off the cooler with a clatter and rummages inside, then noses under the chairs and round the fire pit before slipping away. The lid is shut again in the morning.
- **Spider's web:** strung between two reed stems on the near shore at the left of the starting view. Beaded with dew, it lights up with the low sun behind it at dawn and fades from sight as the dew dries.
- **Fish:** dark shapes cruise just under the surface, and now and then one leaps clear of the water.
- **Great blue heron:** wades the near-left shallows, freezes, then stabs at the water. It sometimes comes up with a fish and swallows it.
- **Red fox:** trots a loop behind the deer meadow from dusk to dawn, stopping to sniff. It bolts when the eagle buzzes it.
- **Great horned owl:** glides a slow loop along the treeline behind the lake after dark.
- **Bats:** flit low over the lake from dusk into the early night.
- **Distant birds:** small flocks in V formation cross the sky.

### The campsite

A man and a woman are camping on the right-hand shore. Their camp has an orange ridge tent, two folding chairs and a stone fire pit.

- **By day:** they sit in their chairs or wander around the tent and fire pit. When the eagle passes close overhead, they stop and point at it, following it with their heads. If they're sitting, they twist round in the chair to point. The eagle comes close most often in the Far away and Follow views.
- **Fishing:** on dry mornings he's up at first light, before sunrise and before she is, and takes a rod down to the shore below the camp. He casts out and waits for the bobber to dip. When he gets a bite he reels the fish in, holds it up to admire it and tosses it back.
- **The canoe:** a red canoe is pulled up on the shore below the camp. On calm, clear mornings (but not when the floatplane's due) they walk down, climb in and paddle a slow loop of the open water, on opposite sides, trailing a wake. On his fishing mornings they wait till he's finished. They glide back in to land and walk up to camp. If the sky starts to cloud over, they turn for home before the rain comes. On the water they still stop paddling to point at the eagle.
- **Rain:** they go into the tent when it starts raining and come back out when it clears.

### The floatplane

Every other afternoon, starting with the first, a red and white floatplane appears over the crest of a foothill ahead and to the right, comes in low over the trees and roars along the lake a few metres up, sending the ducks paddling off and the loon, beavers and otters diving. It climbs away into a wide, banking circuit round the far side, lines up over the trees again and touches down in bursts of spray, then slows to a stop. It sits a while with its propeller ticking over, swings round on the water, then roars off back the way it came, climbs away over the trees and drops out of sight behind the foothill. If it's raining when it's due, it comes the next afternoon instead. The campers leave the canoe ashore on its days, and the eagle doesn't fish and the loon doesn't take off while it's on the lake. In Look around, the camera turns to watch it as it comes close and slows on its path to follow the whole visit. It rises well above the lane along the lake where the plane flies low, so the plane passes beneath it. When the plane's gone, the camera sinks back down and turns back to the tour.
- **Evening:** they light the fire at dusk and sit round it toasting marshmallows, which turn from white to golden brown. Smoke rises from the fire and leans with the wind, and lingers in the morning as the embers die.
- **The lantern walk:** at dusk (except on northern-lights nights) she takes a lantern down to the water's edge, stands looking out over the lake for a while and walks back up to the fire.
- **The bear:** on the evenings the bear comes into the camp, they hurry into the tent and stay there with the lamp lit until it has nosed round the blanket, the chairs and the fire pit and gone.
- **Stargazing:** on northern-lights nights they lie out on a blanket beside the fire to watch them, and stay up until 23:30.
- **Night:** once they turn in (21:00, or later after stargazing) until sunrise, they're in the tent. A lamp lights it from inside and the fire burns outside, throwing sparks and a warm glow on the ground.

### Day and night

- The sun rises at 06:00 behind the left hills and sets at 20:00 behind the right hills. Daylight lasts about 70 seconds and a full day about a minute and a half. The deep night passes faster once the campers have turned in, so on northern-lights nights, when they stay up late, the night lasts a few seconds longer. The page opens at 05:36, just before dawn.
- The sky shifts through pre-dawn, pink dawn, blue midday, golden dusk and deep night.
- At dawn, mist hangs over the lake and burns off as the sun climbs. By day, sunbeams slant down from the clouds and cloud shadows drift across the land.
- At night, stars come out along with shooting stars and fireflies. About one night in three brings a meteor shower, a shooting star every second or so, all streaking out from one point high in the sky in front of the starting view (the clock line says when). In the hours after dusk and before dawn, satellites glide steadily across the sky, some fading out partway as they pass into the Earth's shadow. The moon moves through its phases over eight days and lays a glittering path across the lake. The northern lights appear on the first night and on about half of the nights after, behind the starting view.

### Weather

- Long clear spells, now and then clouding over into light rain or a thunderstorm.
- Rain falls in slanting streaks and makes rings on the lake. The grass and trees sway harder in the wind.
- Lightning strikes whenever it rains and most often in a thunderstorm. Each strike is a forked bolt with a double flash across the sky, followed by thunder.
- A rainbow appears as the rain clears.

### Landscape

- A lake that reflects the sky and scenery, broken up by moving ripples. The sun and moon glint on the water.
- A waterfall straight ahead of the starting view, pouring off a rocky crag at the foot of a bluff beyond the deer meadow, with spray rising from its pool. On sunny afternoons a small rainbow hangs in the spray. Its stream winds down through the meadow between reeds, carrying streaks of foam, and runs into the far shore of the lake beside the beavers' lodge.
- A meadow of around 41,000 grass blades and 4,500 wildflowers, with reeds and cattails along the shore.
- Trees, boulders and hills all round, so there's scenery whichever way you look. The layout is generated from a fixed seed, so it's the same on every load.

### Sound

All sound is generated in the browser with the Web Audio API; there are no audio files.

- **Wind and rain:** wind blows all the time, louder in bad weather, with a rain hiss whenever it rains.
- **Water:** the rush of the waterfall and the stream, louder the closer the camera comes.
- **Day and night:** birdsong while the sun is up and it's dry. After dark there are crickets, frogs and the owl's hoot. The frogs on the lily pads croak in time with their puffing throats.
- **The loon:** its long, rising, quavering wail at dusk and through the night (and sometimes at dawn), echoing across the lake. It gives its rapid tremolo when it's alarmed and when it takes off.
- **The nest:** the eaglets peep while they're begging, and the mate calls when the eagle brings food in.
- **More wildlife:** the osprey's whistled call, the kingfisher's dry rattle, the crack of a beaver's tail slap echoing across the lake, the woodpecker's drumming, the clatter of the raccoon at the cooler, and on some nights a distant wolf pack howling.
- **The floatplane:** the drone of its engine, rising to a roar for takeoff.
- **Events:** the eagle's high chatter when it dives or gives chase, and splashes from catches, leaping fish and the heron. Thunder follows lightning after a delay that's longer for distant strikes.

## Accessibility

- When the system's reduced-motion setting is on, the animation runs at half speed.
- The canvas has a text description of the scene for screen readers.
