---
layout: post
title:  Aw, snap! - No Overflow Menu
date:  Mon Jun 22 19:29:20 PDT 2015
---


# Reported on Android KitKat 4.2.2


<img src='/images/settings.screen.png'
     alt='Overflow menu does not appear'
     title='Overflow menu does not appear'
     style='float: right; margin: .5em;' />

Sadly, on some versions of Android, the three-dots "Overflow Menu
indicator" does not appear. (See yellow arrow in image at right.)

Because of that, the following options are not available:

<ul>
  <li>Shutdown</li>
  <li>Restart</li>
  <li>Note Check</li>
  <li>GPS</li>
  <li>Settings</li>
</ul>

# Shutdown

The missing menu option is particularly problematic because, if you
leave it running, the Plnkx App will suck the battery life from your
phone. It sucks your battery life because it's working hard on your
behalf. It *pings* and *pings* and *pings*, looking for new notes, as
you move around.

# That's a *feature*

Yes, that's a feature, but maybe it's not what you want.

You can (if you're able to get to the Settings option) change **Note
Check frequency** and **Note Check distance**. Reducing the frequency
from, say, Every 15 seconds to Every 3 minutes, will reduce the load
on your phone.

# New plnkx app on the way

App settings aside, you probably want everything to *just work*,
without having to worry about it. Me, too.

Because of that, we're working on a slimmer version of the app that
let's -- well, okay, *requires* -- you to <a
href='http://my.plnkx.com/zapapp'><span style='background-color: #216d99; padding-left: .5em; padding-right:
.5em; color: #ffffff;'>Check</span></a> for notes. So instead of the app
automatically *pinging* the server periodically, you press the big
Check-for-notes button, as-needed.

This changes the dynamic of the app. Instead of being surprised by
what's there, you have to be curious about what's there. There may be
nothing at all. Given the amount of heads-down time we see with
phones, this may be a more natural approach.

Long-term, though, I see a blending of the two approaches. Which is
to say, when battery-life improves and plnkx coding skills mature,
why not have your suprise and curiosity, too!

The plnkx app is currently in BETA release.

The new stripped-down plnkx app is on the way!
