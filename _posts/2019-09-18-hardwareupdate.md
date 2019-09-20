---
title: "Snake Harvesting"
date: 2019-09-18
---

_**Context:** 11:03PM EST, back on the living room couch in Queens.  It's a tad cooler tonight -- maybe because the summer season is coming to an end. I have Miles Davis' cover of "[Bye Bye Blackbird](https://en.wikipedia.org/wiki/Bye_Bye_Blackbird)" playing in my head. There are the three versions that have persisted in my memory:_
- _The [original 1957 recording](https://www.youtube.com/watch?v=KV2lNHfSXBQ) from his album 'Round About Midnight._
- _A [live recording](https://www.youtube.com/watch?v=x6bz-hByzv4) from 1960 at The Olympia in Paris, with John Coltrane._
- _A cover of Miles' cover from a gentleman who was testing out his plastic cornet at a wedding gig or something. I can't seem to find it on YouTube or Facebook for the life of me, but his instrument sounded absolutely beautiful in the spacious hall._

_I ended up listening to the recording at the Olympia. Because I love the album cover design. All is well._

-----

I've been spending just about every afternoon/evening for the past five days looking at hardware. I had dreamed of making a polished audio rig since I was a child. Now that I have a little spending money, I'll try to fulfill as many of these desires as I can alongside this project.

Starting with the interface with my computer, I decided to buy a [Cymatic uTrack 24](https://cymaticaudio.com/utrack24-productpage/). The unit comes from a relatively new company somewhere in Germany, and it seems to be an absolute gem: It's an interface that can either work as (1) a standalone 24ch recorder, (2) a standalone 24ch playback device, or (3) a 24in 24out USB interface -- and it fits in a succinct 1RU chassis and **runs new for about $550**[^1][^2].

Like many other high channel count interfaces, the connectors are [DB25](https://en.wikipedia.org/wiki/D-subminiature)'s. It's a great type of interconnect for saving panel space and for plugging in 8 balanced channels at a time. Not so great for constantly patching microphones and instruments in live settings. If I want this rear panel to survive anywhere other than the safe untouched spaces behind racks and consoles, I'm going to need a patch bay.

I found a handful of used 48-point 1/4" TRS patchbays. While I do plan to wire some of these inputs to dedicated preamps (and not through the bay), having the option to wire the entire 24x24 I/O in 1RU sounds beautifully compact.

<img src="//images.weserv.nl/?url=https://github.com/alextongue/live-project/blob/master/_posts/pics/samsonpatch.jpg?raw=true&w=600">

I'll just need a bunch of breakout cables on one side to get from DB25 to TRS, then TRS to XLR female/male for in/out. For repairability, I decided on "banks" of 8. Here's a block diagram to visualize what I'm thinking:

<img src="//images.weserv.nl/?url=https://github.com/alextongue/live-project/blob/master/_posts/pics/blockdiag.png?raw=true&w=600">

For now, I can forget about two entire input banks because I don't anticipate using more than 8 inputs for any of my project needs. So looking at 3 output banks and 1 input bank, I would need 4 DB25-TRS breakout/snake cables and 3 TRS-XLR-Male snakes.

<img src="//images.weserv.nl/?url=https://github.com/alextongue/live-project/blob/master/_posts/pics/blockdiag2.png?raw=true&w=600">

**Here's where the analysis starts.** After finding some pretty inexpensive [DB25-TRS](https://www.amazon.com/Hosa-DTP802-Snake-Cable-6-6Ft/dp/B001B2SA30) and [TRS-XLR Male](https://www.monoprice.com/product?c_id=301&cp_id=30110&cs_id=3011005&p_id=601296&seq=1&format=2) snakes, the totals would come out to 146.52 + 69.72 = $216.24 before tax and shipping. But there's a big problem that I didn't think about: The DB25-TRS connection is between two units in the same rack. Even if I bought the shortest length of 2m, I'd have 8m (4 x 2m) worth of 8-channel, 3-conductor cabling for a total span of like, 1m (est. 4 x 0.3m).

Also remembering that I have 26 1/4" TRS plugs sitting in a drawer at home from some more adventurous days[^3], I wondered if there would be a cheaper alternative that involved taking apart and building some custom snakes. After all, I had just ordered a new soldering iron that I'm itching to try. Here's what I've gathered:
- I can get 10 DB25 Male plugs for about $10.
- If I buy four 8ch TRS-XLR Make snakes ($69.72), I can cut like a foot off from the TRS side and wire the bare ends to DB25 plugs. I now have four DB25-TRS snakes of the length I need in my rack, for connecting all three output banks and one input bank.
- Of the remaining snakes, I can then terminate three of them with my TRS connectors to get three TRS-XLR output snakes.

This total comes out to almost $80 and some hours of soldering labor (read: experience), as opposed to almost $220 for off the shelf snakes, with half of the length simply taking up space and weight in the rack.

Exciting.

-----

[^1]: for those who are familiar with interfaces with a high analog I/O count (16x16 minimum), you probably know that $550 is comparatively low. For those who don't know: $550 is comparatively low. And I snagged a new one on Reverb for just under $450 weeeee

[^2]: I've also collected enough thoughts while comparing this with other high-channel-count interfaces to warrant a whole other blog post, but I'll go into that once the unit arrives.

[^3]: I've heard of phases where folks have tried out a daring hairstyle or something. While I didn't have a red hair phase, I did have a "red cable" phase: 10 XLR starquad cables: 8 in candy-apple red and 2 in muted purple, all with black Neutrik NCMXX connectors. A true statement. So I also had plans to make a bunch of blue and white TRS cables, but I didn't follow through on those. That's how I have my extra plugs. I've since mellowed down to a black and discreet cable kind of guy...
