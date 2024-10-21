# Introduction
In the rapidly evolving landscape of wearable technology, we find ourselves at a crossroads. The market is flooded with sleek, feature-packed devices promising to revolutionize our approach to health and fitness. Yet, beneath the polished exteriors and marketing hype lies a troubling reality: most of these devices are black boxes, their inner workings shrouded in proprietary code and closed-source hardware. As consumers, we're left in the dark about how our intimate health data is collected, processed, and potentially shared.

Enter `Halo`, an open-source alternative that aims to democratize health tracking. This playbook serves as your entry-level guide to building and using a fully transparent, customizable wearable device.

It's important to note that `Halo` is not intended to compete with consumer-grade wearables in terms of polish or feature completeness. Instead, it offers a unique, hands-on approach to understanding the technology behind health tracking devices.

We'll be using `Swift 5` to build the accompanying iOS interface and `Python >= 3.10`. Since the code for this [project](https://github.com/cyrilzakka/Halo-iOS) is 100% [open-source](https://github.com/cyrilzakka/Halo), please don't hesitate to submit pull requests, or fork the project to take it in a whole new direction.

## Getting Started
To get started you'll first need:
- Physical access to the [COLMI R02](https://www.aliexpress.us/item/3256806445134241.html?gatewayAdapt=glo2usa4itemAdapt) which you can grab for $11-$30 at the time of writing.
- A development environment with `Xcode 16` installed, and an optional membership to the Apple Developer Program
- `Python >= 3.10` with `pandas`, `numpy`, `torch` and of course, `transformers` installed. 

## Acknowledgements
This project is built on code and my learnings from https://tahnok.github.io/colmi_r02_client/. Go give them a follow!

## Disclaimer
As a doctor first, I'm legally obligated to remind you: none of what you're about to read is medical advice. If you accidentally give yourself superpowers, that's on you. Now, let's go make some wearables beep!