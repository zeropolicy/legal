---
title: "Privacy Policy — 20 Arcade Club"
permalink: /arcade-club/privacy-policy/
---

# Privacy Policy — 20 Arcade Club

**Last updated: October 26, 2026**

## Overview

20 Arcade Club is a collection of 20 classic arcade, puzzle, word and two-player games. We are committed to protecting your privacy. This policy explains what data the app collects, how it is used, and your rights.

## Data We Collect

### Data stored locally on your device

The app stores the following data **only on your device** using local storage (AsyncStorage on Android and iOS, the browser's local storage on the web version). This data is never sent to us or to any third party:

- Player profiles (name, chosen avatar emoji)
- Game scores, personal bests, badges and milestones for each player
- Game settings (sound, volume, music, control style and size, content language)
- In-progress game saves (so you can resume where you left off)
- A cache of downloaded trivia questions and crossword clues (so those games also work offline)

### Data we do NOT collect

- We do not collect your name, email address, or any personal information
- We do not create user accounts
- We do not track your location
- We do not use analytics or advertising SDKs
- We do not share any data with third parties

## Third-Party Services

Two games connect to the following external services solely to retrieve game content. Every request is fetch-only: it asks for questions or a clue and contains no profile, score, device identifier or other personal data. As with any connection over the internet, the server you connect to technically receives your IP address; we have no access to it and none of these services receives anything else from the app.

### Trivia Quiz (English) — opentdb.com
- **What it does:** Fetches English trivia questions
- **Website:** https://opentdb.com
- **Data sent:** Only a request for questions (number of questions, difficulty) — no user data
- **Their privacy policy:** https://opentdb.com/privacypolicy.php

### Trivia Quiz (German) — api.opentrivia.de
- **What it does:** Fetches German trivia questions
- **Website:** https://opentrivia.de
- **Data sent:** Only a request for questions (number of questions) — no user data

### Web version only: German trivia via the public proxy api.codetabs.com
opentrivia.de does not allow direct requests from web pages, so **when you play the German Trivia Quiz in a web browser** (https://20arcadeclub.netlify.app), the request is passed through the public CORS proxy **api.codetabs.com** (`https://api.codetabs.com/v1/proxy`), which forwards it to api.opentrivia.de and returns the questions.
- **What the proxy sees:** your IP address, the usual information a browser sends with any request (such as the browser type), and the requested address (api.opentrivia.de with the number of questions) — no profile, score or other personal data
- **Website:** https://codetabs.com
- The **Android and iOS apps do not use this proxy** — they connect to api.opentrivia.de directly. English, Italian and Spanish trivia never use it.

### Crossword — Wikipedia REST API (wikipedia.org)
- **What it does:** Fetches short word clues for the Crossword game, from the English, German, Italian or Spanish Wikipedia
- **Website:** https://www.wikipedia.org
- **Data sent:** Only a request for a specific article summary — no user data. The request carries an app identifier with our developer contact address, as Wikimedia's policy asks; it contains nothing about you.
- **Their privacy policy:** https://foundation.wikimedia.org/wiki/Policy:Privacy_policy

Italian and Spanish trivia questions are built into the app and need no connection.

## Credits & Licences

The app shows third-party content under these licences (also listed in the app under About → CREDITS & LICENCES):

- **English trivia questions:** Open Trivia Database (https://opentdb.com) — licensed under CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/)
- **German trivia questions:** opentrivia.de (https://opentrivia.de)
- **Crossword clues:** Wikipedia contributors — licensed under CC BY-SA 4.0
- **Italian word list:** paroleitaliane by napolux (https://github.com/napolux/paroleitaliane) — MIT License, Copyright (c) napolux
- **English, German and Spanish word check:** Letterpress word list — CC0 (public domain)
- **Other word lists:** as credited in the source header of each dictionary
- Italian and Spanish trivia questions, and all art, sound and code, are made for this app.

## Children's Privacy

20 Arcade Club does not knowingly collect any data from children under 13 — or from anyone. The app contains no advertising, no in-app purchases, and no social features. All player data remains local to the device.

## Data Deletion

Since all data is stored locally on your device, you can delete it at any time by uninstalling the app (or, on the web version, by clearing the site data in your browser). There is no account to delete and no data on our servers.

## Changes to This Policy

We may update this policy when new features are added. Changes will be reflected by updating the "Last updated" date above. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact

If you have questions about this privacy policy, contact us at:

**Email:** kontakt@zeropolicy.de  
**Developer and responsible person:** Mehdi Fadaei  
**Brand:** ZEROPOLICY is the brand of the IT department of Ariel Omidi Holding GmbH; the app itself is published by Mehdi Fadaei personally.  
**Website:** https://www.zeropolicy.de
