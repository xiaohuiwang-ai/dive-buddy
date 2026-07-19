# Dive Buddy — Garmin watch faces for divers

![Dive Buddy Scuba](docs/hero_scuba.png)
![Dive Buddy Free](docs/hero_free.png)

Two watch faces for **Garmin Descent G2**:

- 🤿 **Dive Buddy — Scuba**: surface interval, conservative no-fly countdown, last-dive stats (depth · bottom time · HR · gas), total dives.
- 🌊 **Dive Buddy — Free**: surface interval, session min-HR (your dive reflex), best single dive, session/total counts.

Data auto-syncs from your Garmin Connect account through a free hosted cloud — no server of your own, no manual URL/token.

## Setup (2 minutes)

1. Install the face from the Connect IQ store — it shows a **6-digit pairing code**.
2. Open **https://watch.xiaohuiwangai.cn/dive** on your phone and type the code.
3. Bind your Garmin account there (password is used once for Garmin SSO and never stored).

Done — the face activates itself within ~10 minutes. On dive days it refreshes every 10 minutes; a **Sync now** button is on your dashboard for when you're back on the boat.

## Privacy

- Your Garmin password is never stored; only a revocable session token is kept.
- Unbind any time on your dashboard — that wipes the tokens.
- Your data is served only to your own watch (personal token).

## Disclaimer

Dive Buddy is a watch face, **not a dive computer**. The no-fly figure is a conservative estimate (18 h after the last dive). Always follow your dive computer and your training.

## Feedback

Found a bug or want a feature? [Open an issue](../../issues/new/choose).

## Support

Dive Buddy is free. If it makes your surface intervals better, you can
[buy me a coffee ☕](https://ko-fi.com/xiaohuiwang) — it keeps the cloud running.
