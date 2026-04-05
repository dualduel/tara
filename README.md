# tara
Your daily recovery score for Android &amp; Samsung Galaxy Watch
# Tara

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Android-blue)
![Status](https://img.shields.io/badge/status-MVP%20in%20progress-yellow)

Tara is an open-source Android app that calculates a daily recovery score from heart rate and HRV data collected by your Samsung Galaxy Watch via Health Connect.

## Status

Version 0.1 is in active development.

- [x] Project setup
- [ ] Health Connect integration
- [ ] Resting heart rate and HRV reading
- [ ] Recovery score (0 to 100)
- [ ] Dashboard UI

Planned for later releases: sleep tracking, strain score, AI health coach, Wear OS companion.

## Stack

| Layer | Technology |
|---|---|
| Mobile | Flutter |
| Health data | Android Health Connect API |
| Watch data | Samsung Health synced to Health Connect |
| AI coach | Anthropic Claude API (planned) |

## Setup

Requirements: Android Studio, Flutter 3.x or later, Samsung Health installed, Galaxy Watch with Health Connect sync enabled.

```bash
git clone https://github.com/YOUR_USERNAME/tara.git
cd tara
flutter pub get
flutter run
```

To connect Galaxy Watch data, open Samsung Health, go to Settings, select Health Connect, and grant the required permissions.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT. See [LICENSE](LICENSE).
