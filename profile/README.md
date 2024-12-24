# Ear🔗Link &middot; Revolutionizing Outdoor Communication

> **Because staying connected shouldn’t mean compromising your adventure.**

Welcome to **Ear🔗Link**, a device that aims to seamlessly integrate traditional
radio communication with wireless Bluetooth audio. Whether you’re **skiing**,
**snowboarding**, **motorcycling**, or **climbing**, EarLink helps you keep in
touch with your team—while also letting you enjoy your favorite tunes.

---

## What is Ear🔗Link?

Ear🔗Link is a compact, weather-resistant device that acts as a “bridge”
between:

1. **Traditional Radio Systems** (for reliable, long-range comms).
2. **Bluetooth Headphones** (for modern, wireless audio).
3. **Smartphones** (for music and phone calls).

The core idea is to **pause music automatically** whenever a radio signal
arrives, so you never miss important messages in the field. The result? A
hands-free, convenient, and reliable communication system for outdoor
adventurers.

---

## Why Ear🔗Link?

### 1. Stay Connected in Remote Areas

When you’re far from reliable cellphone coverage, traditional radios are still
the gold standard. Ear🔗Link integrates seamlessly with popular radio systems,
ensuring you can call for help—or just coordinate with friends—no matter where
you are.

### 2. Hands-Free, Seamless Audio

Ear🔗Link pairs with your Bluetooth headphones and smartphone, allowing you to
enjoy music, podcasts, or any audio source without juggling devices or risking
dropping your radio on the slope.

### 3. Tough, Outdoor-Ready Design

From snowy peaks to dusty trails, Ear🔗Link is built to withstand harsh
environments. It’s lightweight, rugged, and designed specifically with outdoor
sports in mind.

### 4. Extend Your Adventure

Long battery life keeps you going during extended climbs, off-road rides, or
day-long skiing. Adventure confidently, knowing your communication and
entertainment won’t cut out halfway.

---

## High-Level Architecture

Here’s an **abstract diagram** showing how Ear🔗Link fits together:

| ![image](https://github.com/user-attachments/assets/3f0d83e4-a7e5-4a30-be4c-2aac29ca3c25) |
| ----------------------------------------------------------------------------------------- |

1. **ESP32 Board** (A2DP Sink): Receives audio from your phone over Bluetooth.
2. **Codec**: Converts between analog signals (radio) and digital signals
   (ESP32).
3. **ESP32 Board** (A2DP Source, “Host”): Streams combined audio to your
   Bluetooth headset.
4. **Bracelet (ESP32 BT HID)**: Optional remote control (push-to-talk,
   play/pause) worn on your wrist.
5. **Radio**: Connects via typical speaker/mic ports, bridging analog radio
   comms with digital Bluetooth audio.

---

## Check Out the White Paper

Want to dive deeper into the technology and our vision?  
[**EarLink White Paper**](https://docs.google.com/document/d/1xk9kzJYLoHj1l52Zh9OlfFfpK6B_a4zJVFg5VTq_kk0/edit?usp=sharing)

It covers:

- The challenges faced by outdoor adventurers.
- Our unique approach to combining radio and music functionalities.
- Key product features, market opportunities, and future developments.

---

## WIP: Community & Support

- **Discord/Telegram:** TODO.
- **Issues:** Found a bug or want to request a feature? Open an issue in the
  relevant repository! (They're private, as our project is not open-source XDD)
- **Wiki:** Browse the wiki for FAQs, troubleshooting steps, and advanced
  configuration guides. (Yeah we don't have any FAQs, so figure it out yourself
  pls)

---

## License

This project is distributed under the [EarLink Strict License](LICENSE). **All
rights reserved.**  
No rights to copy, modify, distribute, or make derivative works are granted
without prior written permission.

Please see the `LICENSE` file for full details.

---

## Contact

- **Organization:** [Ear🔗Link](https://github.com/Ear-Link)
- **Email:** [support@earlink.org](mailto:support@earlink.org)
- **Maintainers:**
  - **Product Owner**: Stanislav Kosarev
    - github: [@miumiumiux](https://github.com/miumiumiux)
    - email: stan@earlink.org
  - **DevOps**: Boris Dvorkin
    - github: [@worthant](https://github.com/worthant)
    - email: [worthant@earlink.org](mailto:worthant@earlink.org)
  - **Embedded Engineer**: Igor Modelkin
    - github:
    - email: igor@earlink.org
  - **?? Engineer 🕶️**: Andrey Setyaev
    - github: [@obormotov](https://github.com/obormotov)
    - email: obor@earlink.org

---

**Ear🔗Link** · _Because the mountains (or slopes, or roads) can be tough
enough—your communication shouldn’t be._
