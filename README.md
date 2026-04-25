# iku-nihongo-audio

Audio assets for [jp.ikuchannel.com](https://jp.ikuchannel.com) — Iku 老師の日本語学習サイト。

Hosted via **GitHub Pages** so the main app at `iku-nihongo` can keep its deploy bundle small.

## Layout

```
audio/
  kana/        — 五十音 (a.mp3, ka.mp3, ...)
  words/       — JLPT vocabulary (Nanami TTS, romaji-keyed: aki.mp3, kau.mp3, ...)
  examples/    — Example sentences for vocab (level-prefixed: n5-aki.mp3, n4-...)
  lessons/     — Slide audio per lesson (lessons/<slug>/<key>.mp3)
```

## Public URL pattern

```
https://hangbuhangtw.github.io/iku-nihongo-audio/audio/<category>/<file>.mp3
```

Used by the main app as `NEXT_PUBLIC_AUDIO_BASE`.

## License

Audio is generated TTS (Microsoft Edge Nanami) plus a few hand-recorded samples by Iku 老師.
Distribution allowed for the iku-nihongo learning site only.
