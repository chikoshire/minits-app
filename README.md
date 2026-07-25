# Minits

**Local-first second brain — capture, dictate, remember.**

Minits is a personal knowledge and capture system spanning **Mac and iOS**: on-device speech, call-aware recording, dictation, and sync — built to feel instant and private, not like another cloud notes clone.

> Installers: [Minits-downloads](https://github.com/chikoshire/Minits-downloads)

---


## Marketing & public surfaces

| Surface | URL |
| --- | --- |
| **Public installers** | [Minits-downloads](https://github.com/chikoshire/Minits-downloads) |
| **Founder / ecosystem** | [chikoshire.com](https://chikoshire.com) |
| **Mustard Seed Group** | [mustardseed.group](https://mustardseed.group) |

> Dedicated Minits marketing domain can be added here when it ships; installers are public, source is not.

## The problem

Notes apps are everywhere. **Capture that keeps up with how you actually think** is not.

You need:

- Speech that works when the network does not  
- A Mac brain and an iPhone mic that cooperate  
- Sync without surrendering the whole corpus to a black box UI  

Minits is that system.

## What Minits does

| Capability | Detail |
| --- | --- |
| **On-device speech** | WhisperKit / Apple speech paths for local dictation |
| **Call & conversation capture** | Recording flows designed for real sessions |
| **Mac ↔ iOS pairing** | Phone as remote mic for the desktop brain |
| **Sync** | Structured sync to your backend — not a social feed |
| **Local-first posture** | Prefer on-device intelligence; cloud as coordination |

## Product surfaces

```text
┌─────────────┐         ┌─────────────┐
│  Minits Mac │◀───────▶│  Minits iOS │
│  desk brain │  pair   │  capture /  │
│  + library  │         │  remote mic │
└──────┬──────┘         └──────┬──────┘
       │                       │
       └──────────┬────────────┘
                  ▼
            Sync / vault layer
```

### Related family

- **Flowlet** — local-first macOS dictation (Apple Speech + optional Whisper/Groq fallbacks)  
- **Minits-downloads** — public installer artifacts  

## Design principles

1. **Capture must be faster than friction**  
2. **On-device first** — privacy and latency  
3. **Two-device reality** — desk + pocket as one system  
4. **Private by default** — your corpus is not a growth graph  

## Stack (high level)

- Native Apple platforms (Swift / SwiftUI)  
- On-device speech stacks (WhisperKit / Apple Speech family)  
- Optional cloud fallbacks for speech where the user opts in  
- Sync backend for multi-device continuity  

## What is public vs private

| Public | Private |
| --- | --- |
| This showcase + [installer downloads](https://github.com/chikoshire/Minits-downloads) | Application source (Mac + iOS) |
| Product narrative | Models, prompts, user vaults |
| High-level architecture | Internal sync schemas & keys |

## Status

Active product — Mac + iOS development in parallel, with public downloads published separately from private source.

## Links

- **Downloads:** [chikoshire/Minits-downloads](https://github.com/chikoshire/Minits-downloads)  
- **Founder:** [chikoshire.com](https://chikoshire.com)

---

<sub>Showcase repository — source code is private by design. Installers live in Minits-downloads.</sub>
