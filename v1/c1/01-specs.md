---
title: Specs
pagenum: 1
---

so the thing I probably want to do, when I have time, is...tidy up his code. I've already gotten a good 50% of the way into de-architecting it. gotta refactor. add support for multi-collections, say, in roughly the way MM does it - I bet how MM does it is available open source. and that'll be us, neat and tidy. 

I bet I can port over some of the good stuff from MM. what's the good stuff? figure that out and put it in here. various _includes, I think. MM has too many moving parts to effectively modify. 

considered that index.html per subfolder can have chapnum assigned in front matter- then you would have to make a setting in the config whether you're auto or manual numbering chapters. default to auto. decided against, because ugh manual. but index can still hold chapter metadata, I think. I think this is sorta reasonable? rather than pulling from folder name. yeah, let's make it work that way. and that way it can also hold a preface or whatever, if you want it. so we are keeping that toggle setting after all, go figure. 

therefore: if there is an index and chapter name is defined in the index, go with that. otherwise, use the folder name. 

o hey gitbook has that lil header with the tabs. I want that. 

we're definitely grabbing slugs from chapterbook. similarly, the index pages should be linked from section titles, so that's chapterbook's script. use a dropdown for collapsing, or remove collapsing entirely, but that's really AR script. I think the scripting is going to end up as a horrible mishmash at best, considering how fucking wordy the chapterbook scripting is. keep front and back sections from chapterbooks. 

I also like the idea of drafts. basically this reads as "remake chapterbooks but in AR, because hell if I'm going to find-and-replace every instance of chapter by page.collection" well hey that wouldn't be too bad would it
