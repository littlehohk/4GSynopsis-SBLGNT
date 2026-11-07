# Synopsis of the Four Gospels in Greek (SBLGNT)

A free, browser-based synopsis of the four Gospels in Greek. The pericopes are arranged and numbered after Kurt Aland’s *Synopsis Quattuor Evangeliorum*, the Greek text is the SBL Greek New Testament, and every word can be clicked for its parsing and meaning.

**Open the synopsis:** https://littlehohk.github.io/4GSynopsis-SBLGNT/

No account or installation is needed. The page also works offline: download `index.html` and open it in any browser.

## Features

### Arrangement
- **367 sections** in the order and numbering of Aland’s synopsis (e.g. § 93 = Mt 9:9–13 // Mk 2:13–17 // Lk 5:27–32), grouped under the 18 major divisions.
- **Contents page** listing every section with its Matthew, Mark, Luke and John references. A **bold** reference marks the Gospel whose own sequence the section follows.
- **Cross-references:** a parallel repeated from elsewhere carries a link (→ §) to the section where it stands in its own sequence.
- **Direct links** to any section by adding its number to the address, e.g. `…/4GSynopsis-SBLGNT/#s93`, or `#contents` for the contents page.

### Synoptic layout
- **Parallel columns** in canonical order (Mt, Mk, Lk, Jn), showing only the Gospels present in each section.
- **Aligned layout:** parallel wording is set on the same line across the columns, with blank space where a Gospel lacks wording found in the others, after the manner of Aland’s synopsis. Hovering over a line highlights the whole row.
- **Running text:** an alternative layout showing each column as continuous prose.

### Word study
- **Click any word** to see its lexical form, an English gloss, a fuller definition, and its full parsing (e.g. “verb, present active imperative, 2nd person singular”).
- **Same-lemma highlighting:** clicking a word also highlights every form of the same lemma across all columns of the section, making shared and differing vocabulary easy to see.

### Tools
- **Search** by title word or by passage (e.g. “Lk 5:27” lists every section containing that verse).
- **Text size** in three steps, and automatic light and dark themes.
- **Print / Save as PDF** any range of sections, one landscape page per section.
- **Import your own text:** users with a licensed digital NA28 (or any other edition) can paste it in, one verse per line (`Mt 9:9 Καὶ παράγων …`). Imported text is stored only in that user’s browser and is never uploaded. Verses not imported fall back to SBLGNT and are marked †.

## How to use

1. Open the contents page and select a section, or type a section number in the box at the top.
2. Use ‹ and › (or the left and right arrow keys) to move between sections.
3. Click a word for its parsing and meaning; press Esc or click elsewhere to close the panel.
4. Use the toolbar to switch between **Aligned** and **Running text**, change the text size, or print.

## Limitations

- **Alignment is automatic, not editorial.** The text is divided into short phrases at punctuation and verse boundaries (and before καί in long clauses), and phrases are matched across the Gospels by shared vocabulary. It works well where the wording is close; where parallels are loose or the order differs widely, some lines may pair imperfectly or sit a row apart. Alignment is by phrase, not word by word.
- **Word study applies to the SBLGNT text only.** Words from an imported text are not clickable, because the parsing data is keyed to SBLGNT word by word.
- **Glosses** come from a concise lexicon; about 140 of the roughly 2,900 lemmas in the Gospels (mostly proper names and rare words) have parsing but no gloss.
- Half-verse references (e.g. 1:14a) display the whole verse.
- No critical apparatus, Gospel of Thomas, or patristic parallels.
- Verses absent from the critical text (e.g. Mt 18:11) are shown as “—”.

## Sources and licences

- **Greek text:** *The Greek New Testament: SBL Edition*, edited by Michael W. Holmes. © 2010 Society of Biblical Literature and Logos Bible Software. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Source: https://github.com/LogosBible/SBLGNT
- **Parsing and lemmas:** MorphGNT SBLGNT morphology by James K. Tauber and contributors, licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Source: https://github.com/morphgnt/sblgnt
- **Glosses and definitions:** John Jeffrey Dodson, *A Greek–English Lexicon of the New Testament*, dedicated to the public domain ([CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)). Source: https://github.com/biblicalhumanities/Dodson-Greek-Lexicon
- **Section arrangement:** follows the pericope numbering of Kurt Aland, *Synopsis Quattuor Evangeliorum* (Stuttgart: Deutsche Bibelgesellschaft), as tabulated at https://bible-researcher.com/parallels.html. This project is independent and is not affiliated with or endorsed by the Deutsche Bibelgesellschaft.
- Because the parsing data is CC BY-SA 3.0, the morphological data embedded in `index.html` remains under that licence and may be reused only on the same terms.
- The Nestle-Aland (NA28) text is copyrighted and is **not** included in this repository.
