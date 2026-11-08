# Moon Base Pals 1.1.4

A guided Moon outpost adventure with hands-on science practice and simple resource choices, designed for ages 6–9. Help Jade, care for the base, and earn a project certificate.

Created by **Sun Zeyi · Team Little Hero** for **Build a Junior Astronaut Mission Trainer**, NASA Space Apps Challenge 2026.

## Start playing

1. Extract the entire ZIP into one folder. Keep `index.html` beside the `assets` folder.
2. Open `index.html` in a recent browser. Click **Let's play** to begin.
3. Click **Listen** for instructions. Use the menu to pause, change sound settings, or practise a mission. Progress is saved in this browser when storage is available.

Direct double-click launch is a convenience path, not a promise of compatibility with every browser. If browser restrictions affect opening files, saving progress, audio, or exporting the certificate, use the local server below.

### Optional local server

With Python 3 installed, open a terminal in the extracted folder and run:

```text
python serve.py
```

Open `http://127.0.0.1:8799/index.html` in your browser. Stop the server with **Ctrl+C**. If port 8799 is in use, run `python serve.py --port 8800` and open the printed address. The server listens only on this computer; it does not publish the game to the Internet.

## Offline use and saved progress

Images, fonts and recorded voice assets are included. Core gameplay does not require an account or a live NASA feed. Links to NASA sources and the challenge website require Internet access. The current journey uses locally bundled Ana neural speech: a stock American English synthetic child voice, not a recording of a child performer. Outcomes and celebrations use complete recorded paragraphs. If a clip cannot play, the game offers a retry instead of switching to a system voice. The earlier journey retains its earlier narration.

The application stores the chosen name, settings and progress locally in browser storage. It does not upload gameplay or names to a project server. A nickname is enough. Private browsing, blocked storage, clearing browser data, changing browsers, or switching between direct-file and local-server addresses can prevent an old save from appearing. The game does not provide cloud backup. A certificate you save or print is a file under your control.

`journey-v5.html` preserves the earlier journey for existing players. It is separate from the new journey and uses its earlier save data. Start with `index.html` for this release.

## Learning and certificates

The Moon base, supplies, growth times and equipment are simplified story models. Fresh vegetables supplement a prepared meal. Water needs treatment and checks. Shade needs stored power. Thermal insulation and radiation shielding are different functions.

Badges recognise completed activities in this game. **The certificate is issued by Team Little Hero, not NASA.** It is not an astronaut qualification, a formal assessment, or a NASA endorsement. The game has not yet been validated in a study with children. Read-aloud, hints, retries and adult help are welcome.

Package CRC and SHA-256 checks verify the delivered files; they do not establish compatibility with every browser or prove learning outcomes. Browser, double-click, offline, touch-device and assistive-technology coverage must be assessed separately. No cross-browser or child-tested claim is made by this package.

## Included files

- `index.html`: current game.
- `journey-v5.html`: earlier journey compatibility page.
- `assets/`: local game pictures, fonts and sound files.
- `serve.py`: optional loopback-only static server.
- `SHA256SUMS.txt`: SHA-256 hashes of every other packaged file.

Keep all files together. The personal file `commander_cloud_drawing.jpg`, development scripts, review evidence and unrelated projects are excluded. Public release metadata is generated beside the ZIP as `release.json`; version-specific metadata is retained by the project team.

## Science sources

- [NASA: water recovery and checks](https://www.nasa.gov/missions/station/nasa-achieves-water-recovery-milestone-on-international-space-station/)
- [NASA: growing plants in space](https://www.nasa.gov/exploration-research-and-technology/growing-plants-in-space/)
- [NASA: radiation protection at the Moon](https://science.nasa.gov/science-research/heliophysics/how-nasa-will-protect-astronauts-from-space-radiation-at-the-moon/)
- [NASA Space Place: spacecraft power](https://spaceplace.nasa.gov/what-powers-a-spacecraft/en/)
- [NASA: lunar dust technology](https://www.nasa.gov/centers-and-facilities/kennedy/nasa-technology-helps-guard-against-lunar-dust/)
- [Team Little Hero](https://www.spaceappschallenge.org/2026/find-a-team/little-hero)
- [User-confirmed challenge](https://www.spaceappschallenge.org/2026/challenges/build-a-junior-astronaut-mission-trainer/)
