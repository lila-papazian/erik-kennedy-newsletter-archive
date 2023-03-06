![Design Hacks Newsletter](https://ci5.googleusercontent.com/proxy/i5lB1CJkqmPPaNTz9WbHdJYqCYPsDwcovaQPtOyfwrRaEAYFcSlFq2zOFkrvKh8PkEsKV2XICb6f25qqLji4GSBG02oQz5aqm2n3=s0-d-e1-ft#https://learnui.design/extras/img/dh-email-header-hd.png) 

Hey Lila,

If you ever have to design **data table on mobile devices** (websites or native apps), we’ll cover the **3 best techniques** for doing so in this email. That's it. Feel free to archive if not applicable.

But first... have you *seen* this?

![](https://ci5.googleusercontent.com/proxy/CG5je6nQDBHjsHBnBhDYsUBjuwFWOQqMeoXoGHFx6BCshRGNriV3CbemSAeu9dVFWOIdzC6wjlIIRKzSGoeXTwPIvpBbXyaokWnvnP3QXLV_rc0Ho6qmvb0QWJtL-2vrPP2gM-Y=s0-d-e1-ft#https://embed.filekitcdn.com/e/gJxGcuzsv4KXrV4Q8BDmRk/o7cnWRpyqVbtqvqqgG7Ro8/email)​

It’s a quantum computer. Yes, it *actually exists*. No, it doesn’t work very well… yet.

(Unlike the computer you’re using now, quantum computers need to be hermetically sealed from the outside world. If so much as a stray atom or photon hits them wrong, their unworldly powers of computation are completely nullified… so, uh, good luck to those engineering teams :grimacing:

“Erik”, you might be wondering, “What on *earth* are you talking about?”. Good question. I bring this up for 3 reasons:

1. I’m on a **ridiculous quest** to trade my UX/UI design services for part of a **decommissioned quantum processor** (if you know anyone who can help me in this quest, I’d appreciate the introduction) 
2. Quantum computing will be the subject of our example design today 
3. The picture – and story behind it – are *awesome*. Nuff said.

OK, now let’s look at some tables. In particular, one that’s a *bit* wide for mobile:

![](https://ci5.googleusercontent.com/proxy/gXdbMNP_C2t5cTfaHTdQJijaYau6V1ZQLdCGMr-Zpz4PqFPDtSXnRvDZzuFqYAKDkpdhB6wlX3aWtFDSn2NPkT0Iu5o6cHZwmmMj-JYgpd5BNQP17F64FOoFn-9KEC7P7bVhA_MKC8_GXw4=s0-d-e1-ft#https://embed.filekitcdn.com/e/gJxGcuzsv4KXrV4Q8BDmRk/uiWXmdMTErLgSTZju4s3mL/email?auto=)​

What are our options? :thinking:

3/ Hide the least important columns
===================================

Look, it’s pretty basic, but if some data is *truly extraneous*, we can just *not show* *it on mobile* :shrug:

![](https://ci6.googleusercontent.com/proxy/OoTzHlLThsqc4ryBvXZd55lHH98N_20MNtrNrzxW8KhClL6PaXLEVbxQ7ZmWxOg0MLfiVlQ6lYzFe4-POLactX5l174R3r5ShRJ-XEcBa9TqX9KYqzucya_uozbb3VxdnHW8YRpY1BwEOIo=s0-d-e1-ft#https://embed.filekitcdn.com/e/gJxGcuzsv4KXrV4Q8BDmRk/htRM9isZWHWmoojDhdzuNv/email?auto=)​

Design = tradeoffs, *so*:

- :white_check_mark: Super cheap to implement
- :x: Doesn’t actually show all the data – and therefore not widely practical
- :point_up_2: You could add a “Show All” button as a compromise (and then risk massive horizontal scrolling)

Let’s get more nuanced here.

2/ Label-Value Pairs
====================

Slightly more refined is to expand each **row** into a **full blown 2-col table.**

![](https://ci5.googleusercontent.com/proxy/j7pSwgoAtZFxIAKfzK1yHa8OLavSD22fjogUrFOpJmxZUMk-v4veXQzUinPy_VeuxzmR209fVtjF3_x1SbuRa0vdZSamDDi7QFg0sWxb7br9V0aT9oWasjArzRj17g8hKHniPLTEtozi4eM=s0-d-e1-ft#https://embed.filekitcdn.com/e/gJxGcuzsv4KXrV4Q8BDmRk/uPx3zCrCzYunrr6WJWUGSJ/email?auto=)​

Thinking through this one:

- ✅ Shows all data
- ✅ Actually possible with [pure CSS](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/p8heh9h9v2kqortq/aHR0cHM6Ly9jb2RlcGVuLmlvL3BpeGVsY2hhci9wZW4vck5hS0xN)​
- :x: Takes a TON of vertical space
- ☝️ If there are too many rows for each item, you could hide some with a “Show All” link

But my *favorite* option is…

1/ Recreate as mobile list
==========================

Your developer might not like it, but by far the most flexible option is to redesign the desktop table as a mobile list. Mobile lists are standard, flexible, and can even open up to their own modal/page to show more details.

![](https://ci3.googleusercontent.com/proxy/_VOJSQZMMi2dqj8hp1PiW4Xoyk3KTU7eWcfk1sTbMrqFYSIjY_Kl59mHRn9ueKBppp99J1f7g3xfjCX8Qjtn5LQNdxbztELfQZeALteJVpKPzvZXotinpBNdec24KU37ueVzWkAag4QQ3zI=s0-d-e1-ft#https://embed.filekitcdn.com/e/gJxGcuzsv4KXrV4Q8BDmRk/pBov887ovNDJeCDAmkRemU/email?auto=)​

The tradeoffs are pretty clear:

- ✅ Flexible (you can have grouping/sorting/filtering/modals/etc. as needed)
- ✅ Makes use of commonly-used design patterns
- :x: Requires more development effort (sometimes *way* more)

Overall, this is my favorite. Apologies to all the developers who I work with 😉.

Anyhow, I think **these three patterns** are the major ones you’ll use for almost every responsive table.

Did I miss anything? Reply, let me know; I read every response 😎.

Oh, and if you want to bookmark or send this one, [click here](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/6qheh8hpq5v9erso/aHR0cHM6Ly9ja2FyY2hpdmUuY29tL2IvNzV1N2g4aGs0bW5lMw==).

Cheers,  
Erik D. Kennedy

PS. I’ve got a rare **UX/UI client project slot** open in the next few months. I’m most interested in projects involving new tech with huge potential – like quantum computing, alternative energy (especially fusion / nuclear / geothermal), medical, regenerative agriculture, etc. – but open to anything awesome 😎

Know of someone looking for UX/UI design work in those (or similar) areas? Discount applies if I can use the project in curriculum. Would love a quick reply. Thanks! :v:


**Was this design article useful?** Please forward this email to anyone else you know who’d benefit from it. It only takes 5 seconds – and I put hours into writing each one. Thanks! 😎
**New around here?** I'm Erik, and I post free design content on the [Design Hacks list](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/58hvh7h5enp628a6/aHR0cHM6Ly9sZWFybnVpLmRlc2lnbi9uZXdzbGV0dGVyLmh0bWw=), the [Learn UI Design blog](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/qvh8h7h8x4gkp9ul/aHR0cHM6Ly9sZWFybnVpLmRlc2lnbi9ibG9n), my [YouTube channel](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/g3hnh5hevl7qwqir/aHR0cHM6Ly93d3cueW91dHViZS5jb20vY2hhbm5lbC9VQ2FrUHI4bGM3WmNvd2Q4Q3AyVXlfRWc=), [my twitter](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/3ohphkhqw26pg8sr/aHR0cHM6Ly90d2l0dGVyLmNvbS9lcmlrZGtlbm5lZHk=), and more (check out my [free design tools](https://click.convertkit-mail.com/4zuq65w5k0heh52nx3kbx/48hvheh0opzxezfx/aHR0cHM6Ly9sZWFybnVpLmRlc2lnbi90b29scy9pbmRleC5odG1s) too!)
