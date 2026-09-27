## [Hi, I'm Len](https://len-pgh.github.io/)

I teach telephones to hold up their end of a conversation.

My work sits where telephony meets language models: real calls over real carriers, real
APIs, real video in the browser, built on the
[SignalWire AI Agents SDK](https://developer.signalwire.com/agents-sdk). The phone network
is a century of accumulated engineering discipline and it is unforgiving in the way good
infrastructure should be. Teaching it to think is the most interesting problem I've been
handed.

I came to it from the PBX side, after a decade of FusionPBX and FreeSWITCH, and that decides
the order I build in: prove the thing end to end on real infrastructure first, then make it
elegant. A demo that survives a live call has earned the right to look good.

Pittsburgh, PA.

### Upstream

Eleven years of open-source contribution, primarily across FusionPBX, FreeSWITCH
and SignalWire.

| | |
|---|---|
| **1,426** pull requests merged | 96% of the 1,478 I opened |
| **372** issues opened | 94% of them closed |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="chart-dark.svg">
  <img alt="Merged pull requests by year, 2015 to 2026. FusionPBX dominates 2015 to 2021, peaking at 520 in 2019; FreeSWITCH and SignalWire work runs 2022 to 2026." src="chart-light.svg" width="760">
</picture>

Of the merged pull requests, 1,390 landed in public repositories (97%) and 36 in
private ones (3%). The public ones:

| Project | Merged | PRs | Span |
|---|--:|--:|---|
| [fusionpbx/fusionpbx](https://github.com/fusionpbx/fusionpbx) | 1,012 | 1,031 | 2015–2021 |
| [fusionpbx/fusionpbx-install.sh](https://github.com/fusionpbx/fusionpbx-install.sh) | 171 | 177 | 2016–2022 |
| [fusionpbx/fusionpbx-docs](https://github.com/fusionpbx/fusionpbx-docs) | 120 | 127 | 2015–2020 |
| [signalwire/freeswitch-docs](https://github.com/signalwire/freeswitch-docs) | 27 | 28 | 2023–2026 |
| [signalwire/WireStarter](https://github.com/signalwire/WireStarter) | 21 | 22 | 2022–2024 |
| [signalwire/digital_employees](https://github.com/signalwire/digital_employees) | 13 | 13 | |
| [signalwire/freeswitch](https://github.com/signalwire/freeswitch) | 4 | 4 | |

Plus smaller sets in [freeswitch/verto-client](https://github.com/freeswitch/verto-client),
[freeswitch/freeswitch-sounds](https://github.com/freeswitch/freeswitch-sounds),
[signalwire/libstirshaken](https://github.com/signalwire/libstirshaken) and
[signalwire/docs-legacy](https://github.com/signalwire/docs-legacy).

### Built and maintained by me

Chess is mine start to finish. Sidecar began as an earlier prototype from
[Brian](https://github.com/briankwest); I did the bulk of the build.

| | |
|---|---|
| **[Chess](https://github.com/signalwire-demos/chess)** · sole author | Play live chess against an agent over a realtime connection |
| **[Sidecar](https://github.com/signalwire-demos/sidecar)** · primary author | AI assisting a human rep on a live call, rather than replacing them |

### Things you can actually talk to

Team projects I contributed to. Every one of them is live: call it, or click the video
button and talk in the browser. They answer.

| | |
|---|---|
| **[Holy Guacamole](https://holyguacamole.signalwire.io)** | Drive-thru ordering |
| **[CineBot](https://cinebot.signalwire.io)** | Movie and TV discovery, with trailers, over video |
| **[Blackjack](https://blackjack.signalwire.io)** | Play 21 against an AI dealer over WebRTC video |
| **[Bobby's Table](https://bobbystable.ai)** | Restaurant reservations, start to finish |
| **[After Hours](https://afterhours.signalwire.io)** | After-hours HVAC intake and dispatch |
| **[Santa](https://santa.signalwire.io)** | Seasonal, and a hit with the under-10 crowd |
| **[Tech Tarot](https://techtarot.signalwire.io)** | Exactly what it sounds like |
| **[Cabby](https://cabby.signalwire.io)** | Taxi booking |
| **[GoAir](https://goair.signalwire.io)** | Airline agent doing real work against real APIs |

### ClueCon

Maker challenges and stage tooling built for ClueCon, the annual FreeSWITCH and telephony
developer conference. Once a year the industry gathers in one room, and I try to give it
something hands-on to build.

**2026 · [The Prompt Pit](https://github.com/Len-PGH/prompt_pit)** · sole author
An esports-style control room for the Vibe Coding Championship. A single container drives
every screen in the house (stage, scoreboard, admin) and lets the entire audience vote from
their phones three ways: on the web, by SMS, or by ringing a number and telling an AI agent
who they are backing. The
[prototype challenges](https://github.com/Len-PGH/prototype_challenges_for_prompt_pit), five
callable agents that contestants had to bend to their will, live in their own repo.

**2026 · [Buzzword Bingo](https://github.com/Len-PGH/buzzword-bingo)** · sole author
Live audience bingo for conference talks. Scan a QR, draw a card that locks to you, and blot
buzzwords as the speaker says them. Positive buzz counts for sound engineering and responsible AI,
negative for hype, and AI product names are a free-for-all. The room's collective sentiment updates
on stage in real time, which speakers enjoy right up until the hype column starts filling in.

**2025 · [Coder Games, Maker Challenge](https://github.com/signalwire/ClueCon_Coder_Games)** · sole author
The SignalWire Maker Challenge for [ClueCon Coder Games](https://www.cluecon.com/coder-games):
an ESP32 whose LEDs answer to the phone network, one sketch driven by an inbound SMS and another
by a voice call. It ships with the wiring diagram and a credentials scaffold, so entrants spend
the hour on the idea rather than the boilerplate. Paired with an
[LED control agent](https://github.com/Len-PGH/2025) that takes colour and on/off state by voice.

**2024 · [FreeSWITCH ClueCon Lab](https://github.com/signalwire/freeswitch-cluecon-lab)** · contributor
Brought the hands-on FreeSWITCH lab up to date for the conference: moved the image to Debian
bookworm, took the IPv6 profiles out of the load path, and corrected the docker-compose and
event-socket config so the lab came up clean for attendees.
**2023 · [Maker Challenge, ESP32-S3](https://github.com/Len-PGH/Cluecon2023)** · sole author
Place a phone call from a button press. Five sketches that climb from "the board joined wifi,
send an SMS" up to a physical button dialling out, with an optional temperature reading along for
the ride. Parts list, wiring photos and a write-up for each one.


### Microcontrollers

Small boards with something to say to the phone network. Most of them are well grounded.

| | |
|---|---|
| **[ESP32-S3 call button](https://github.com/Len-PGH/Cluecon2023)** | Button press places a real phone call; wifi-connect and SMS variants, optional DHT11 |
| **[Phone-controlled LEDs](https://github.com/signalwire/ClueCon_Coder_Games)** | ESP32 LEDs driven by an inbound SMS or a voice call, with wiring diagram |
| **[ESP32 / AHT10 / OLED](https://github.com/Len-PGH/ESP32-AHT10-OLED)** | Temperature and humidity on a little OLED, reporting over HTTP |
| **[Sensor AI](https://github.com/Len-PGH/Sensor-ai)** | ESP8266 and DHT11 into ThingSpeak, read back to callers by a voice agent |

### Side projects

- **[FusionPBX + Jitsi Meet](https://github.com/Len-PGH/fusionpbx-jitsimeet)**: embedding a Jitsi room inside FusionPBX, so the phone system could finally put a face to the name

---

More at **[len-pgh.github.io](https://len-pgh.github.io)**
