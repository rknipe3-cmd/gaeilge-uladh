Gaeilge Uladh — Ulster Irish Study Tool

A self-contained mobile web app for learning Ulster Irish (Gaeilge Uladh), the dialect spoken in Donegal and parts of Northern Ireland. Built as a single HTML file with no external dependencies — works fully offline after first load.
Features
📅 Week Plan
A structured 7-day study plan with daily session blocks covering flashcards, pronunciation, sentence building, listening, and written output. Each day has a specific pronunciation focus. Day 4 includes a reference lesson on Ulster vs standard Irish negatives.
🃏 Flashcards
12 decks across five groups:

Phrases — Greetings, Ulster Phrases
In Context — Everyday Life, People & Places, Food & Feelings, Time & Plans
Vocabulary — People & Family, Time & Numbers, Places, Food & Drink, Adjectives
Verbs — Core Verbs, Present Tense, Past Tense, Future Tense
Grammar — Prepositions (ag, ar, le, do conjugated forms)

Cards include literal translations where illuminating (e.g. Tá brón orm = "Sorrow is on me"). Supports Irish→English and English→Irish modes. Missed cards are automatically re-queued until answered correctly.
🔨 Sentence Builder
Seven grammatical patterns covering VSO word order, the tá sentence, the Irish "have" structure, emotion states, liking, past tense movement, and the future continuous.

Build mode — tap word options to assemble sentences and understand how patterns work
Quiz mode — type the Irish sentence from an English prompt with no options shown. Stays on the selected pattern and generates new vocabulary combinations each time.

🔊 Pronunciation
Interactive reference covering:

Long vowels (á é í ó ú) with Ulster-specific notes
Diphthongs and vowel combinations — including the key Ulster feature ao/aoi = "ee"
Consonant clusters (bh/mh, ch, th, ph, gh/dh, abh/amh, fh)
The broad vs slender consonant system with worked examples

Speak buttons link to Abair.ie using the Ulster (Tír Conaill/Donegal) voice.
✍️ Write
Typing exercises driven by English prompts. Available in two modes:

Vocab — practice any flashcard deck from memory
Sentences — type full Irish sentences from the builder patterns

Missed items are automatically repeated until correct. Character-level diff highlighting shows exactly where errors occurred.
Why Ulster Irish
This app targets Ulster Irish rather than the standard written form (Caighdeán). Key Ulster features covered:

ao/aoi = "ee" (not "ay" as in Connacht or Munster)
cha/chan negative particles instead of ní/níl
cha dtig liom ("I cannot") vs standard ní féidir liom
cluin for "hear" instead of clois
Strong palatalised l and n sounds
Stress on long vowels wherever they fall

Offline use
Fonts are embedded directly in the HTML. A service worker caches the page on first visit. After opening the app once on WiFi, everything works with no connection. The only feature requiring internet is the Abair.ie pronunciation link.
Roadmap
This app is actively being developed. Planned additions include new vocabulary decks, expanded grammar lessons, additional sentence patterns, and further Ulster-specific content. Updates are applied by replacing the index.html file in the repository — see the Updating section below.
