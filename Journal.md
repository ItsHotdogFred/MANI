---
title: "MANI"
github: "https://github.com/ItsHotdogFred/MANI"
description: "MANI, Many Absurd Needless Inputs. Is a gaming controller which consists of a bunch of features / inputs with some being useful like thumb sticks and some being somewhat useless like a microphone."
created_at: "2026-11-16"
total_time: "3h 30m"
---

# November 17, 2026: Sketch of the design / parts of the controller
<!-- fabricate:entry 3267 -->

![Sketch](https://fabricate.hackclub-assets.com/94de1734109788e073a9493a3562295298c5713562c08e8a9f59a83db3176642/image-png/image.png)

This is a rough sketch of what I want the controller to look like / include. I intend to add more things as I think of them and the layout is not final

**Total time spent: 1h**

# November 20, 2026: Created the schematic
<!-- fabricate:entry 3493 -->

I have created and finished (hopefully) the schematic of the controller. I have chosen a 
nice!nano as the microcontroller as they have a built in battery handler (though I am using chip to get more accurate battery percentage) and also bluetooth. Although I have decided that I will use another cheap MCU as a 2.4ghz dongle to get 1000hz polling rate because I don't want to be stuck with 100hz polling (10ms extra latency on top of everything else) Everything went well apart from not realizing that the MCU only exposes 3 out of the 4 analog pins I need so I have to use an expander but it shouldn't case any issues (hopefully).

![](https://fabricate.hackclub-assets.com/7317c8d774066f7c4f2c98c77ca92362e233d562b51ad7ac77a8b335ecda044f/image-png/image.png)

**Total time spent: 2h 30m**
