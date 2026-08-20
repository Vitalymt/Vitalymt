## About

Senior pre-sale analyst by day, **hardware hacker & AI automation builder** by night. I design and ship tools that bridge the gap between electronics, LLM capabilities, and real-world workflows. My stack: **Python / FastAPI / C++ / ESP32 / Docker / n8n / LLM APIs**.

---

## Hardware & Electronics

<table>
<tr>
<td width="50%">

<img src="https://raw.githubusercontent.com/Vitalymt/Pocket-AI-Voice-Assistant-3.0/main/assets/bips-v3.jpg" width="100%"/>

</td>
<td width="50%" valign="top">

### [Pocket AI Voice Assistant 3.0](https://github.com/Vitalymt/Pocket-AI-Voice-Assistant-3.0)

**Pocket-sized AI assistant. Speak — it responds.**

ESP32-S3, 1.3" OLED display, magnetic charging, zero physical buttons. 43x43mm body. Smart sleep, OTA updates, web search via Tavily.

`C++` `ESP32-S3` `ESP-IDF` `I2S` `SH1106 OLED` `Tavily API`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Neon Cassette](https://github.com/Vitalymt/Neon-Cassette---MP3-Player-in-a-Cassette-Shell)

**MP3 Player in a Cassette Shell**

A portable MP3 player hidden inside a real 1980s audio cassette. DFPlayer Mini + Li-Po battery. No microcontroller, no code — pure analog meets digital. Total cost: ~820 RUB (~$9).

`DFPlayer Mini` `TP4056` `Li-Po` `BC547`

</td>
<td width="50%">

<img src="assets/neon-cassette.png" width="100%"/>

</td>
</tr>

<tr>
<td width="50%">

<img src="https://raw.githubusercontent.com/Vitalymt/Pocket-AI-Voice-Assistant-2.0/main/photos/bips-2.0.jpg" width="100%"/>

</td>
<td width="50%" valign="top">

### [Pocket AI Voice Assistant 2.0](https://github.com/Vitalymt/Pocket-AI-Voice-Assistant-2.0)

**Next-gen palm-sized AI assistant**

Transparent acrylic case, hidden capacitive touch button, battery indicator, noise-filtering capacitor. Custom Xiaozhi firmware — rewritten from 16MB to 8MB RAM (using only 2MB), toggle activation, Tavily web search. ~2hr battery.

`ESP32-S3` `MAX98357A` `INMP441` `TTP223` `Tavily`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Stellar Clock](https://github.com/Vitalymt/Stellar-Clock-ESP32C3-Supermini)

**Autonomous IoT desk clock on ESP32-C3**

Vertical OLED display showing time, date, temperature, humidity, and pressure. NTP sync over Wi-Fi. Li-Ion battery with USB-C charging. All firmware in C++.

`C++` `ESP32-C3` `PlatformIO` `I2C` `BME280`

</td>
<td width="50%">

<img src="assets/stellar-clock.png" width="100%"/>

</td>
</tr>

<tr>
<td width="50%">

<img src="assets/pocket-ai.png" width="100%"/>

</td>
<td width="50%" valign="top">

### [Pocket AI Voice Assistant v1.0](https://github.com/Vitalymt/Pocket-AI-Voice-Assistant)

**Palm-sized AI that listens, thinks, and speaks**

ESP32-S3 + Xiaozhi firmware. 45x30x16mm. Wi-Fi connected, OLED status display, cloud AI speech processing. All off-the-shelf modules, hand-soldered, transparent case showing every component.

`ESP32-S3` `Xiaozhi` `OLED SSD1306` `USB-C`

</td>
</tr>
</table>

---

## Software & AI

### [AnnonymizerForChrome](https://github.com/Vitalymt/AnnonymizerForChrome)
> Chrome extension (MV3) for **offline PII anonymization** in Russian text.

Processes everything locally in the browser — names, phones, INNs, passports, addresses, bank accounts. One-click restore via dictionary export/import. Supports PDF files.

`JavaScript` `Chrome Extension MV3` `PDF.js` `Regex` — ![20+ PII types](https://img.shields.io/badge/PII_types-20%2B-1f6feb?style=flat-square) ![69 tests](https://img.shields.io/badge/tests-69_passing-3fb950?style=flat-square) ![MIT](https://img.shields.io/badge/license-MIT-8b949e?style=flat-square)

---

### [HH-Job-Ranker](https://github.com/Vitalymt/HH-Job-Ranker)
> **Autonomous AI agent** for searching and evaluating vacancies on HH.ru.

Generates search queries, parses HH API, evaluates matches via LLM, displays ranked results in a web dashboard, and generates personalized cover letters.

`Python` `FastAPI` `APScheduler` `SQLite` `Docker` — ![AI-powered](https://img.shields.io/badge/AI-powered-8957e5?style=flat-square) ![~$0.0001/vacancy](https://img.shields.io/badge/cost-~$0.0001/vacancy-3fb950?style=flat-square) ![MIT](https://img.shields.io/badge/license-MIT-8b949e?style=flat-square)

---

### [Video Annotation Tool](https://github.com/Vitalymt/video-annotation-tool)
> Browser-based **frame-accurate video segment annotation** tool.

Open `index.html` — no server, no build step, no dependencies. Mark segments with `[` and `]`, assign labels, export structured JSON.

`HTML` `JavaScript` `Video API` — ![Zero deps](https://img.shields.io/badge/dependencies-None-3fb950?style=flat-square) ![MIT](https://img.shields.io/badge/license-MIT-8b949e?style=flat-square)

---

### [ProjectChat](https://github.com/Vitalymt/AI-project-chat-anonimaizer)
> **AI-powered project assistant** with document management and Obsidian integration.

Upload project docs, chat with AI in context, auto-anonymize PII, save analysis artifacts directly to Obsidian vault via WebDAV sync.

`Python` `FastAPI` `Vanilla JS` `SQLite` `Docker` `Obsidian` — ![SSE streaming](https://img.shields.io/badge/SSE-streaming-1f6feb?style=flat-square) ![MIT](https://img.shields.io/badge/license-MIT-8b949e?style=flat-square)

---

## GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com/?user=Vitalymt&theme=default&ring=58a6ff&fire=f0883e&currStreakLabel=1e293b&sideLabels=6b7280&border=cbd5e1&cb=3)](https://github.com/Vitalymt)

---

## Contact

[![Telegram](https://img.shields.io/badge/Telegram-@vitalymt-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/vitalymt)
[![Email](https://img.shields.io/badge/Email-to@v--mit.ru-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:to@v-mit.ru)
