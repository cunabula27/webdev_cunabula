# webdev_cunabula
Ongoing design work for my websites cunabula.io and cunabulapress.com

I originally put them together in 2011 but I never finalised some of the details of the design and there was a fair bit of hacky code to get them to look the way I wanted. Now I want to be working on them again, or more specifically showing work through them, so I have to get them in a more polished state.

All that would be fine but they were originally put together with a float and percentage-based layout and now we have grid and flexbox, so I'm taking the opportunity to completely overhaul the underlying code rather than just finish them off from where I left them.

---

**Version_1** is all the code that runs the old (current) version of the site.

**Version_2** is the first stab I had at a grid-based redesign.

**Version_3** is the rewrite of that fixing my beginner's mistakes with Version_2.

---

Mistakes like, I wanted to put rules in the grid gaps but thought you couldn't, so instead of using `grid-gap` I used `padding` on pretty much everything. Then after almost a month of working on the redesign I suddenly thought 'I wonder what would happen if I used negative margins?' Because I'm an idiot.

So, Version_3.
