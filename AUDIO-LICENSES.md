# Sandbag Siege – audio licenses (v18)

All music and sound effects are synthesized at runtime with the Web Audio API (no audio files).
The only embedded audio is the soldier voice clips (base64 Ogg/Opus inside index.html, ~36 KB raw / ~49 KB base64).

## Soldier voice clips (English: "Yes sir!", "Roger!", "Go go go!", "Copy that!", "Contact!", "Boss incoming!", "HQ under fire!", "Airstrike inbound!")

| Item | Detail | License |
|---|---|---|
| Voice model | Piper `en_US-libritts-high`, speaker id 520 (rhasspy/piper-voices on Hugging Face) | Model repo: MIT. Model card: *trained from scratch* on LibriTTS train-clean-360 |
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
