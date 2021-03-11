---
title: 'Meeting of the Minds #13'
permalink: motm/13/
category:
  - MotM
tags:
  - MotM
subtitle: 'Scheduled for Thursday, June 7th @ 6:30pm'
location: 'Third Space Coffee House'
location_link: 'https://sites.google.com/view/thirdspacecoffeehouse'
topic: Heroku
date: 2018-05-12 10:53:26
---
The growing season has been a little late this year and it feels a bit like we may have skipped Spring straight over to Summer 🔥 here in Kansas, but I think I'm happier with the cold having moved on.  The wind has also calmed itself more lately.  However, since I can't resist a good pun, the winds of change are still strong at work and that certainly helps us consider new and improved ways of deploying some of our applications!  <-- Great segway, yeah?  😆 🤓

The topic for June's Meeting of the Minds session is Heroku, and yours truly will be doing the presentation.  I've been intrigued by [Heroku][] and its offerings since I became enamoured with container computing more than a year ago.  Lately I've actually been putting it to good use deploying some [MkDocs][] solutions for customer review.  We'll be reviewing at least the core offering (there is a _lot_ more under the Heroku umbrella) at MotM-13 with some discussion and application demos.  At {% post_link motm-12 MotM-12 %}, we discussed the plans for this upcoming session and mentioned a Modbus simulator as a good demo app to implement and deploy via Heroku.  If you have any other application suggestions (remember, these will be demos! 😀) please join us in the discussion over in our [Slack](/slack) group or leave a comment below.

I'm pretty excited to demonstrate how even the free tier of [Heroku][] can be used to host some great application content.  It isn't just about web pages either--our Modbus simulator will be emulating remote device behavior, and our documentation demo is a great way to host documentation packages.  Combine these with a custom domain name integrations and you can have a pretty broad set of functionality without much hosting upkeep!  I look forward to some wonderful brainstorming on this during next month's session.

If I haven't just completely convinced you to drop by yet, don't forget that each month we raffle off a free license to one of **[JetBrains'](https://www.jetbrains.com)** amazing developer tool offerings!  We're very happy to have them as a continuing sponsor of our group.  Come by and take advantage with a chance to leverage their productivity enhancing IDE's or refactor/linting tools.

<center>
{% img /images/jetbrains.svg JetBrains Logo %}
</center>

Finally, we're looking for more discussion topics for future sessions, so please let us know if you have interest in a particular discussion topic.  I've updated our [Mindmap](/mindmap) with some more topic ideas--let's build that list out even more and get some folks lined up to dive in on these!

That's all I have for now.  Enjoy the weather everyone, don't forget to go outside and do a little analog processing; all the same, happy coding as well!  😎

--Kevin Collins
<span class='post-entry-small'>
_UPDATE_:  As it turned out during preparing materials for this MotM, Heroku is really just for deploying web applications.  It supports WebSockets, but you can't deploy an application that listens on an arbitrary TCP socket--something that you need if you're going to perform device simulation as my hopes outlined above.  As we discussed during the session, you can have what are called "worker" dynos to perform background tasks, but they won't be reachable externally.  Thanks to those who made it out, and we're all looking forward to a great rest of 2018, to be continued with a session on ZeroMQ in July!
</span>

[Heroku]: https://www.heroku.com "Heroku"
[MkDocs]: https://www.mkdocs.org "MkDocs"