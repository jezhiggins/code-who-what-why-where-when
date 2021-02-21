Hello, I'm Jez

Code is Easy 

Code is Hard

This is the essential paradox

Because code is easy, it's hard to write the correct thing

Because code is hard, it's easy to get into a mess

Taming the paradox
  * There is no trick
  * We aren't cutting the Gordian knot, or suddenly untwisting the Mobius strip
  * There are no rules

If there were any of the above, then software would be straightforward, everyone would be doing it just fine, and none of would have gathered together today. 

The best we can do apply some guidelines, some heuristics. 

It's a perpetual balancing act between, well not good and evil, or even between law and chaos, but between everyone who's interested in the code.

Consequently, there's a tension between the guidelines - not just in this session, but you'll no doubt notice it again and again throughout the day - but within the guidelines themselves. 

Ok then Jez cut the burble, give me them sweet guidelines

Here's a couple of high level things to get us started

_The code is not the important thing_

The people who use our software are deeply, deeply uninterested in our code. They are interested in what the code does and, generally speaking for the kind of commercial software most of us are engaged in it, how it makes their life easier. They are interested in _outcomes_. 

_People don't know what they want_

The only way to find out the outcomes people really want is to ask them, build some software for them to use, then ask them again -> _Build for now_

Or as you might have heard it put 

_Do the simplest thing that could possibly work_

Not _the simplest thing_. Not _can work_. The _simplest thing that could possibly work_. We don't have to be sure, we have to find out. 

This isn't my phrasing, of course it isn't, this is far too sensible for anything I'd have come up with. No fart gags, for a start. This is a deeply, deeply profound insight. It applies at all levels - from the architecture of our system, through the tiers of system, to the packages or modules or namespaces, to the class and functions, right down lines we write. 

This talk is notionally about code, so let's look at how that might apply down at the level of lines of code 

* idiomatic language
    * what's normal for the language you work in
    * what's normal for the people you work with - do you have a local vernacular?

* naming
    * naming is hard, of course
    * good names are hugely powerful
    
* small methods
    * naturally lead to good names

If we pursue these things relentlessly, mercilessly even, then we will simplify our code. And weirdly, once people are bopping around with it and that say _yea, this is great but could it do ..._, we'll come back to code and go _yea, actually we can_. 

(I've danced around saying _users_. It really helps to have a better name for those people. Probably for some of you here, then _quants_? But it could be teachers, maybe specifically maths teachers, geologists, whomever. For me at the moment I have two really quite distinct types of users for my software - convicted offenders and probation officers.)

The human brain is an immensely complex structure, the most complex of all known living structures. But how many things can we keep in our mind at any given time? A handful. If we minimise what we have to think about, as far as we can, we can focus more on the problem we're trying to solve. And then when the future arrives, we will be free to embrace it. 

