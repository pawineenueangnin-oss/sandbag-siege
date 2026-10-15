# Sandbag Siege – audio licenses (v26)

Embedded audio (base64 Ogg/Opus inside index.html): 22 recorded sound effects (CC0, ~130 KB raw / ~174 KB base64) and the soldier voice clips (CC BY 4.0, below).
Music, the tesla zap, sub-bass explosion tails, engine rumble, ambience, reverb impulse responses and all UI tones not listed below are synthesized at runtime with the Web Audio API (original, no third-party material).

## Recorded sound effects (v26) – all CC0 1.0 (public domain dedication)

Every file below was checked on its Freesound page on 2026-10-15 and is published under **Creative Commons 0 (https://creativecommons.org/publicdomain/zero/1.0/)**: commercial use and embedding allowed, no attribution required (credited anyway). Source = Freesound's HQ preview of the sound. Processing (ffmpeg + numpy, build machine only): trim, 3 ms fade-in / fade-out, 35 Hz high-pass, light EQ, compression (3:1), peak normalize to −1 dBFS, loop crossfade for loops, mono 48 kHz Opus 28 kbps (v25; v26: 64 kbps). At runtime: random pitch ±6 %, random gain, stereo panning + distance low-pass, short outdoor reverb, ducking, 8-voice gun pool.

| Clip | Used for | Source | License | Size |
|---|---|---|---|---|
| `rifle` | rifle tower shot | [Ar15-Real Recording.wav](https://freesound.org/people/SuperPhat/sounds/432366/) by SuperPhat (Freesound #432366) | CC0 1.0 | 0.59 s, 2380 B |
| `mg` | MG single round | [50 Cal MG](https://freesound.org/people/qubodup/sounds/239138/) by qubodup (Freesound #239138) | CC0 1.0 | 0.17 s, 757 B |
| `mg_b` | MG burst (embedded, reserved) | [Heavy Machine Gun](https://freesound.org/people/ShawnyBoy/sounds/165394/) by ShawnyBoy (Freesound #165394) | CC0 1.0 | 0.75 s, 2729 B |
| `sniper` | sniper shot | [Sniper Rifle M24 SFX.mp3](https://freesound.org/people/kennysvoice/sounds/351777/) by kennysvoice (Freesound #351777) | CC0 1.0 | 1.32 s, 4552 B |
| `mortar` | mortar launch thump | [tinymortar.wav](https://freesound.org/people/j1987/sounds/140727/) by j1987 (Freesound #140727) | CC0 1.0 | 0.55 s, 1835 B |
| `impact` | heavy shell impact layer | [Mortar](https://freesound.org/people/Mozfoo/sounds/529239/) by Mozfoo (Freesound #529239) | CC0 1.0 | 2.4 s, 8167 B |
| `rocket` | rocket launch | [Rocket Launch](https://freesound.org/people/qubodup/sounds/840511/) by qubodup (Freesound #840511) | CC0 1.0 | 1.92 s, 6968 B |
| `flame` | flamethrower burst | [Flamethrower](https://freesound.org/people/LilMati/sounds/459884/) by LilMati (Freesound #459884) | CC0 1.0 | 1.5 s, 5315 B |
| `aa` | AA cannon round | [Autocannon Three Shot Burst](https://freesound.org/people/qubodup/sounds/854186/) by qubodup (Freesound #854186) | CC0 1.0 | 0.24 s, 1030 B |
| `boom_s` | small explosion | [small explosion](https://freesound.org/people/bevibeldesign/sounds/315826/) by bevibeldesign (Freesound #315826) | CC0 1.0 | 1.0 s, 3026 B |
| `boom_l` | large explosion | [Distant Explosion](https://freesound.org/people/Mr_KeybOred/sounds/372086/) by Mr_KeybOred (Freesound #372086) | CC0 1.0 | 2.2 s, 7983 B |
| `boom_d` | distant explosion tail layer | [Distant Explosion](https://freesound.org/people/danlucaz/sounds/517747/) by danlucaz (Freesound #517747) | CC0 1.0 | 1.43 s, 5355 B |
| `step` | boot step (marching built from it) | [Hiking Boot Footsteps on Gravel](https://freesound.org/people/Fission9/sounds/521588/) by Fission9 (Freesound #521588) | CC0 1.0 | 0.3 s, 1004 B |
| `click` | UI click | [SFX UI Button Click](https://freesound.org/people/suntemple/sounds/253168/) by suntemple (Freesound #253168) | CC0 1.0 | 0.14 s, 1241 B |
| `coin` | coin pickup | [coin object](https://freesound.org/people/Leszek_Szary/sounds/146723/) by Leszek_Szary (Freesound #146723) | CC0 1.0 | 0.14 s, 761 B |
| `wrench` | engineer ratchet | [ratchet socket wrench tool](https://freesound.org/people/AlaskaRobotics/sounds/551497/) by AlaskaRobotics (Freesound #551497) | CC0 1.0 | 0.95 s, 3343 B |
| `whistle` | incoming shell whistle | [Incoming mortar 4](https://freesound.org/people/Zagge28/sounds/241837/) by Zagge28 (Freesound #241837) | CC0 1.0 | 1.6 s, 5580 B |
| `siren` | air-raid siren (engineers / alarm) | [air_raid.R.wav](https://freesound.org/people/torn.rugged.audio.35/sounds/45933/) by torn.rugged.audio.35 (Freesound #45933) | CC0 1.0 | 4.75 s, 20171 B |
| `jet` | jet flyby (enemy jets, airstrike) | [Jet.ogg](https://freesound.org/people/egomassive/sounds/536809/) by egomassive (Freesound #536809) | CC0 1.0 | 6.4 s, 21115 B |
| `heli` | helicopter rotor loop | [MILITARY ROTOR LOOP](https://freesound.org/people/UnderlinedDesigns/sounds/172667/) by UnderlinedDesigns (Freesound #172667) | CC0 1.0 | 0.78 s, 2935 B |
| `jeep` | jeep engine | [djeep_idle.wav](https://freesound.org/people/Mihacappy/sounds/840649/) by Mihacappy (Freesound #840649) | CC0 1.0 | 2.48 s, 8460 B |
| `tank` | tank engine + tracks (also APC, pitched) | [t26_moving_01.wav](https://freesound.org/people/greatmganga/sounds/329800/) by greatmganga (Freesound #329800) | CC0 1.0 | 4.38 s, 14955 B |

No CC BY-NC, CC BY-SA or unclear-license material is used. Sonniss/GDC bundles were not used.

## Soldier voice clips (English, 14 lines: "Yes sir!", "Roger!", "Copy that!", "Go go go!", "Move, move!", "Contact!", "Boss incoming!", "HQ under fire!", "Airstrike inbound!", "Enemy aircraft!", "Hold the line!", "Target down!", "Engineers on the way!", "Repairs complete!")

| Item | Detail | License |
|---|---|---|
| Voice model | Piper `en_US-libritts-high`, speaker ids 520, 760, 472, 288 (deep male; 2–3 takes per line from different speakers; calm delivery for confirms, faster/louder/more driven "urgent" processing for combat calls) (rhasspy/piper-voices on Hugging Face) | Model repo: MIT. Model card: *trained from scratch* on LibriTTS train-clean-360 |
| Training data | LibriTTS (Zen et al., 2019), derived from LibriSpeech / LibriVox public-domain readings | **CC BY 4.0** – commercial use allowed, attribution required |
| Synthesis software | piper-tts 1.8.0 (GPL-3.0-or-later) + espeak-ng phonemizer (GPL-3.0) | Used only offline on the build machine; GPL does not apply to the generated audio, and no GPL code ships in the game |
| Post-processing | ffmpeg (pitch −~2 st, EQ, compression, soft-clip, loudnorm, silence trim), libopus 24 kbps | Tools only |
| QA | faster-whisper `base.en` (MIT) speech recognition used to pick intelligible takes | Tool only |

**Attribution (shown in-game on the title screen and here):** "Voice: Piper TTS · LibriTTS (CC BY 4.0)".
Suggested store-listing / credits text: *Soldier voice synthesized with Piper TTS using a model trained on the LibriTTS corpus (Zen et al., 2019), licensed CC BY 4.0.*

### Voices considered and rejected
- Piper `en_US-joe`, `en_US-mike`, `en_US-libritts_r`, `kusal`: CC0/CC BY datasets, but **fine-tuned from `lessac`**, whose Blizzard-2013 data is research-only (commercial use excluded) → avoided.
- Piper `en_US-ryan`, `hfc_male`: CC BY-NC-SA datasets → non-commercial, avoided.
- edge-tts / Azure neural voices: output terms unclear for redistribution in a commercial app → avoided.
- Coqui XTTS-v2: Coqui Public Model License (non-commercial) → avoided.

## Thai voice – NOT shipped (Thai UI currently plays the English clips)
No neural Thai TTS with a clean commercial license was found:
- Piper `th_TH-tsync2`: dataset NECTEC TSync2 – CC BY-NC-SA 3.0 (non-commercial).
- Facebook MMS-TTS (tha): CC BY-NC 4.0.
- Wayu-Paxa-TTS-Edge: weights CC BY-NC 4.0. ThonburianTTS / F5-TTS-THAI: weights CC BY-NC(-SA).
- KhanomTan TTS v1.1: labeled Apache-2.0, but it was trained on TSync1/TSync2 (non-commercial corpora) and has no native Thai male speaker (cross-lingual French/German voices) → provenance too doubtful.
- Coqui XTTS: non-commercial license and no Thai.

Options for Thai:
1. **Record a real Thai male voice actor** (7 lines, ~10 min session; Fiverr/local studio or a friend) with a written release granting commercial use – best quality and cleanest rights. Drop WAVs in and re-run the same ffmpeg chain.
2. Buy a commercial TTS license that explicitly permits redistributing generated audio in apps (e.g. a paid plan of a Thai TTS vendor such as Botnoi Voice / Paxa TTS Flash / ElevenLabs paid tier) – check the terms first.
3. Keep English clips for all languages (current behaviour).

## v25 processing
All clips: high-pass 100 Hz, −2 dB @ 250 Hz, no compression/saturation, normalised to −3 dBFS peak, 5 ms fade-in, Opus 28 kbps (v25; v26: 64 kbps). Runtime: 8 ms/12 ms fades, master HP 110 Hz + gentle limiter (ceiling −1 dBFS). Whistle and jet sources replaced in v25 (previous recordings were clipped).

## v26 encoding / engine
- Recorded SFX re-encoded as Ogg Opus **64 kbps** mono (was 28 kbps); soldier voice clips re-encoded from the original Piper renders at **40 kbps** (was 24 kbps, "voip" mode).
- Music is still original and generated in code; it is now rendered once at start-up (OfflineAudioContext, 24 kHz stereo) into seamless loops instead of being synthesized live.
- Synth-only UI/game sounds (build, upgrade, deny, zap, casing, …) are generated in code and pre-rendered once into buffers. No new third-party material.
