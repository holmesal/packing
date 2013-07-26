packing
=======

Open source packing. An np-hard problem.


List
=======

* swim trunks
* flippie floppies
* thinking cap

#! /usr/bin/python
import trip
from room import closet, accessories

clothes = [random.choice(closet.underwear) for _ in range(trip.duration.days)]

shirts += [random.choice(closet.shirts) for _ in range(trip.duration.days)]
assert favorite_shirt in shirts
clothes += shirts

legwear += [random.choice(closet.shorts) for _ in range(trip.duration.dats)]
assert all(isinstance(pant, jorts) for pant in legwear), 'Get some jorts, bro.'
clothes += legwear

stuff = []
stuff.append(accessories.sunglasses)
stuff = filter(lambda accessory: accessory.isNecessary, accessories.iphone_accessories)
assert iphone_charger in stuff, 'Dont forget the iphone charger'
stuff.append(accessories.moleskine)
stuff.append(accessories.tooth_brush)

assert pats_toothpaste not in stuff, 'You better not take my toothpaste!'
