# 4 Friends legal documents

The Impressum (legal notice, DDG), Datenschutzerklärung (privacy policy,
DSGVO/GDPR) and Nutzungsbedingungen (terms of use) for 4 Friends, the
multiplayer running game, in German and English. The German terms of use are
the binding version. This repo is the only copy: the website's footer links
here, and so will the game and its store listings.

It follows the same layout as TrackPrint's
([trackprint-legal-docs](https://github.com/TrackPrint-Music-Posters/trackprint-legal-docs))
and Lectio's
([lectio-legal-docs](https://github.com/Lectio-Study-Planner/lectio-legal-docs)).

## Published at

GitHub Pages serves `main` from the repo root:
<https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/>

| Document | German | English |
|---|---|---|
| Impressum | [impressum.de.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/impressum.de.html) | [impressum.en.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/impressum.en.html) |
| Datenschutzerklärung | [datenschutzerklaerung.de.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/datenschutzerklaerung.de.html) | [datenschutzerklaerung.en.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/datenschutzerklaerung.en.html) |
| Nutzungsbedingungen | [nutzungsbedingungen.de.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/nutzungsbedingungen.de.html) | [nutzungsbedingungen.en.html](https://4-friends-multiplayer-running-game.github.io/4-friends-legal-docs/nutzungsbedingungen.en.html) |

The game will open the English pages. Keep their addresses in one place in
the game's code (see CLAUDE.md in
[4-friends](https://github.com/4-Friends-Multiplayer-Running-Game/4-friends)).
If a file is renamed or the site moves, change that place in the same
release, and the footer links in
[4-friends-webpage](https://github.com/4-Friends-Multiplayer-Running-Game/4-friends-webpage).

## Editing

- **Keep both languages in sync.** Any sentence changed in one language
  changes in the other in the same commit, and the sections stay in the same
  order.
- Update the "Stand" / "Last updated" date in both files of a document when
  its content changes.
- **The game is still in development.** The privacy policy covers only the
  website, these pages, email and the feedback form, and its "The Game" /
  "Das Spiel" section says so. **Before the first release**, replace that
  section with what the game really does: every server, multiplayer or
  matchmaking service, account, analytics or crash reporter, store purchase
  and value kept on the device, each with its provider, data, purpose,
  retention and legal basis, as TrackPrint's policy does for its app.
- **The terms of use carry a version number** ("Version 1" next to the date).
  Once the game asks players to agree to them, a change that affects
  players' rights or duties bumps the version in both files and the game's
  own terms version in the same release, so the game asks again. Keep the
  version it replaces as an archive copy, `nutzungsbedingungen-v<N>.de.html`
  and `nutzungsbedingungen-v<N>.en.html`, so what a player agreed to stays
  readable. Typos and pure clarifications keep the version.
- **Keep the documents true to the game.** The privacy policy names every
  place data leaves the device. A release that adds a service, a request or
  a stored value updates the policy before it ships, together with the store
  privacy labels.
- Each file is a standalone page: a short shared header (charset, viewport,
  `style.css`, language switch) around the document text. Edit only the text
  between the language switch and `</main>`.
- The privacy policy is adapted from text made with Datenschutz-Generator.de
  (Dr. Thomas Schwenke) and the Impressum follows eRecht24. Keep the generator
  attribution at the end of the privacy policy; the free generator licence
  requires it. For that reason this repo has no open-source licence.
- `.nojekyll` makes Pages serve the files exactly as committed.
