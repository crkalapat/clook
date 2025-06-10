---
title: "Clook"
author: "crkalapat"
description: "A visual time tracker"
created_at: "2025-06-04"
---

**Total time spent on project: 3.5h**

# June 4th: Start!

After some thinking for almost an hour, I decided to make my own timer/stopwatch thing. Calling it "Clook" because it sounds similar to "clock", but in a fun and unique way. 

Whipped out an online painting tool to flesh out my intial idea. Features I want to have are:
- USB C charging
- LED ring to show timer status and display things
- Screen to show exact time left (maybe touch screen?)
- Physical buttons to also interact with the device

You can see my very rough rendering below.

![Initial idea render](assets/idea.png)

**Total time spent: 1.5h**

# June 7th: Finding the Display

Today was spent primarily trying to figure out what display I would use for the project. After thoroughly checking DigiKey, Mouser, and LCSC for a small circular OLED display, I decided (tentatively) to just use [this](https://www.alibaba.com/product-detail/1-5-Inch-466-466-16_1601271796179.html) display from Alibaba. Because it was from Alibaba, and the product description had no datasheet whatsoever, I had to track it down from the vendor website. Eventually though, I was able to make a symbol for the display in KiCad.

![Display Symbol](assets/symbol1.png)

The one thing that is scaring me though is the shipping time. If I were to order right now, the screen would come earliest July 11th...

Don't know yet though if that will be a dealbreaker. Another display that I might pivot to is an [LCD](https://www.mouser.com/ProductDetail/Microtips-Technology/AWD-360360T18N01?qs=sGAEpiMZZMt7dcPGmvnkBgpwamjCGwcHVYYbZzFyeqeK65tjxJno9g%3D%3D) from Mouser, simply because it's around the same price with shipping, and it can come significantly quicker. Its datasheet is also easier to understand and simpler overall.

**Total time spent: 2h**