---
layout: post
title:  "Over-intervention in UI design"
author: "Petar Perovic"
date:   2020-07-11 12:10:00 +0100
readingtime: "2"
excerpt: "Don’t mess up the basics"
categories: typography product design ux ui
---

Designers need a constant reminder about the fundamentals of good UI design. The goal of visual design in user interfaces is to make content accessible, understandable and easy to consume.

However, that gets often neglected, sometimes under the burden of trends, and sometimes out of a personal preference or sheer complexity of the interface that designer is trying to _domesticate_.

We tend to sterilize our work. I do it all the time. In order to fight the visual complexity we remove too many signals and our UIs become unintentionally worse. When there’s not enough signal, eyes can’t stop and rest, and user feels lost. When there’s too many, UI gets messy and incoherent.

Fine-tuning the right amount of signal is absolutely the principal goal of visual design in software interfaces.

So, what is a signal? In broadest sense – all elements in a layout compete for our attention and signal is what gives some of them more importance and meaning. Like underlined text in browser usually means it’s a link, bold text emphasizes the importance, bigger type also, and so on. Everything that sets something apart from uniformity is a signal. Yet, design is often an effort to make things more uniform and this is where over-intervention usually happens.

I can you give a couple of the obvious culprits. We make links hard to identify or choose color so poorly that contrast drops way below accessible values. We use tiny, hard to read font sizes. We abuse font weight just as much. Thin fonts in longform are painful to read, yet designers insist  it’s beautiful. Even Google, a company that arguably hires the best people in the world, at the time of writing this uses `font-weight:300;` for body copy on their official blog. That’s hardly a bearable reading experience on retina screen and good luck reading that on an average cheap display. And so on.

Mistreating fundamentals quickly add up to the cognitive load. User loses a couple of seconds when they’re not sure if that text is a link. Another five seconds squinting at the thin, light-gray passage of text. Even more to figure out what that feature with poorly written copy does. It puts them in the state of permanent unconscious wrestle with the UI. And that’s just typography and visuals, we didn’t even observe what a poor interaction does to their cognitive functions.

In software UIs whose principal goal is to explain, guide and act as the extension of human brain, intervening on foundations must be minimal. Browser defaults are carefully configured for usability before we start to tear them apart. That’s not to say you shouldn’t, but the next time you think of replacing those ugly blue underlined links for something more _elegant_, remember that what’s usable in software, also makes it beautiful.