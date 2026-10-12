# NeuroFlow

Offline focus, relax, sleep and meditation audio for macOS. No account, no subscription, no network, no tracking.

**Download:** [latest release](https://github.com/lole-sc/neuroflow-releases/releases/latest) · **Try it in the browser first:** [neuroflow-lole.vercel.app](https://neuroflow-lole.vercel.app) (web demo with a sample of the library)

## Requirements

- Mac with **Apple Silicon** (M1 or later). This build does not run on Intel Macs.
- macOS 12 or later.
- About 1 GB of disk space (the whole audio library ships inside the app).

## First launch

The app is ad-hoc signed and **not notarized** by Apple, so macOS blocks it the first time:

1. Open the `.dmg` and drag **NeuroFlow** to **Applications**.
2. Double-click NeuroFlow and close the warning.
3. Go to **System Settings → Privacy & Security**, find "NeuroFlow was blocked…" and click **Open Anyway**, then **Open**.

You only do this once. On macOS 14 and earlier, right-click → **Open** in Finder also works.

## Verify the download

Latest: **1.0.2** ([release notes](https://github.com/lole-sc/neuroflow-releases/releases/tag/v1.0.2)).

```
shasum -a 256 NeuroFlow-1.0.2-arm64.dmg
```

`5e9f9fd84a1ca10e84da226de4286468910a28a104eb5c7bc1fd90a62d0d9847`

## What's inside

103 listening experiences: 50 original compositions, 9 Bach suites performed by Kimiko Ishizaka (CC0), 21 soundscapes from CC0 field recordings, plus noise, binaural experiments and guided breathing generated live. Timers, Pomodoro, a layer mixer and local statistics.

NeuroFlow follows the format of focus-music apps such as Brain.fm. It is an independent project, not affiliated with or endorsed by Brain.fm, and contains none of its audio, artwork or code. The optional "Neural Effect" is a listening preference, not a medical treatment.

Audio licenses: original material, CC0 1.0 and Public Domain Mark recordings; the full credits are in the app under Settings → About & licenses.

---

Made by [Lorenzo Scaldaferro](https://portfolio.loleautomations.com).
