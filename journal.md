# 02202018

I should have started this journal a few weeks ago, but better late than never.

Here's a table of what I've bought so far:

Qty. | Price | Item | Notes
-----|-------|------|------
1 | 380.66 | K40 laser cutter kit | eBay
5 | ?? | 1 gallon distilled water | Fleet Farm
1 | ?? | 5 gallon bucket & lid | Fleet Farm
1 | 14.99 | Flow meter | Amazon
1 | ?? | Short USB cable | lab stock
1 | 11.29 | Exhaust manifold | Amazon
1 | 7.99 | 4" exhaust hose & 2 clamps | Amazon
1 | 18.99 | 4" in-line exhaust fan | Amazon
1 | 5.28 | Louvered exhaust port | Amazon
1 | 8.29 | 0-30mA panel meter | Amazon
1 | 27? | 4'x4'x3/4" plywood sheet | Hardware Hank
2 | ?? | 4" hose clamp | Hardware Hank
1 | 30.00 | Laser safety goggles | Amazon
1 | 13.99 | Air assist and laser cross holder | eBay
1 | 2.99 | Red cross line laser | eBay

I also wrote a blog post describing the setup so far: https://jasongullickson.com/posts/lasertime/

Using this configuration I made a few runs at engraving some material with the following results:

Material | Power | Speed | Air Assist |  Results
---------|-------|-------|------------|---------
Cardboard | 10% | 500 mm/s | no | Clean if shallow engraving
Cardboard | 10% | 100 mm/s | no | Cuts/burns dirty
Linoleum | 13% | 100 mm/s | no | Marks but doesn't etch very deep
Linoleum | 20% | 50 mm/s | no | Engraves deeply, lots of smoke and charring

During some of these tests the laser would stop before finishing a job.  I researched a number of potential causes but after swapping-out the long (6'?) USB cable that came with the machine for a short (6"?) one the interruptions did not return.

It's clear from the results of these first tests that the machine requires the following upgrades before I can start using it on a regular basis:

* Air assist
* Replacement bed
* Additional exaust capacity
* More accurate measurement of laser power

I have parts on-order to address all three of these areas.  I hope to have some time next weekend to implement some or all of these measures.  I'm still deciding how I want to address the issues with the stock bed, but I'm leaning toward a self-adjusting system like the one described here:

http://www.scorchworks.com/Blog/spring-loaded-k40-laser-platform/

I should be able to source most of these parts locally, the only one I'm not sure about is the "expanded metal sheet" (although I could probably come-up with an alternative for that).


# 03142019

I'm doing a bad job maintaining this journal.

Since the last post I've installed a larger-capacity exaust fan and a cheap air assist.  This combination makes a big difference.  The air assist is essentially an aquarium air pump connected to a sportsball inflation needle, held in place by a 3d-printed collar mounted on the laser head.  This works surprisingly well, but I'd like to do a better job of keeping things in place and managing the air hose.  I also think that the system could benefit from a better air pump, so I'm on the lookout for a suitable replacement.

I think the exaust is good, but I ended-up using a piece of plastic 4" hose for one section and I think I'm going to replace that with aluminum like the rest of the system.

The cooling system is holding up but the pump has become louder and I'm expecting it to fail at some point.  I need to get a replacement so I have something on-hand when that happens, and I should really get some sort of automated shut-down setup in the event of a cooling failure, but at the moment I'm not sure if there's a simple/cheap way to accomplish this.

I also picked up an ammeter so I can accurately measure the current going to the laser.  This is essential to prevent overdriving the tube.  I haven't installed this yet because it's going to be messy (I need to cut holes in the control panel to mount it) and I'm using low enough power levels that I shouldn't be getting anywhere near overdriving the tube.  I'm also in te middle of a project and I don't want to break the thing before we finish.

Speaking of this project, it's an engraving project and I've managed to find some settings that work very well for raster engraving bamboo cutting boards.  Surprisingly fast and low power, and engraves well without a lot of smoke, charing, etc.  I've started a new page on jasongullickson.com to document the working feeds & speeds that I come across for various materials.

I also took a swing at cutting some 3mm baltic birch plywood.  I've only tried a few settings but found that 10mm/s at 40% power works well.

Did a more substantial cutting test with worse results.  On one end of the board the cuts are OK, but they don't go all the way through at the other end.  The most likely cause of this is the bed not being "tram" with the laser head, so I'm going to hold-off on trying to improve cutting until I get a better bed in place.
