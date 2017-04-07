+++
author = "Thiago Kenji Okada"
date = "2017-04-07T13:14:23-03:00"
description = "Yet another new blog"
tags = ["misc"]
title = "Hello World!"

+++

I am starting a yet another blog, this time based on [Hugo](https://gohugo.io/)
instead of [Pelican](http://docs.getpelican.com/en/stable/) or
[Jekyll](https://jekyllrb.com/).

I decided to use Hugo because it is fast, thanks to the fact that is written
in Go. Even if this blog shouldn't have too much content so that the compile
times shouldn't take too long, it is still nice to have sub-second compile
times. And thanks to the static binaries that is used in Go applications,
this makes much easier to deploy my blog. When I used Pelican, I needed to
first install Python, so afterwards I could do a `pip install -r requirements.txt`.
Not really difficult, however it can be made easier.

The theme of choice, at least for now, it is
[ghostwriter](http://themes.gohugo.io/ghostwriter/). I chose a theme that is
relatively lightweight and could still work even with disabled Javascript/CSS.
And of course, it should be good looking.

Expect posts in this blog about development and random thoughts. Run your `bsh`
(brain shell) and run:

```sh-session
$ dd if=/dev/random of=/dev/brain
```
