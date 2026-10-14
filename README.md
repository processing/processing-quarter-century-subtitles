# A Quarter Century of Processing — Subtitles

*A Quarter Century of Processing* is a presentation celebrating 25 years of open-source innovation and the community behind Processing. It reflects on how Processing has empowered a generation of artists, educators, and tool builders, and how it continues to shape creative expression, learning, and technological experimentation.

The presentation traces the histories of Processing and p5.js, announces Processing 5, thanks the contributor community, and introduces the Processing Foundation's Maintenance and Development Funds.

**[Watch the source video on YouTube](https://www.youtube.com/watch?v=5Z8N9tghPRE).**

This repository contains the presentation's subtitles. Help make it accessible to more people by reviewing translations in your native language and fixing mistakes, awkward phrasing, and anything that doesn't sound natural.

Even a correction to a single subtitle is welcome. You don't need to be a programmer or review the entire video to contribute.

## Available subtitles

All subtitle files are in the [`subtitles/`](subtitles/) folder in SubRip (`.srt`) format.

The English file is the reference transcript, edited by the presenters. The translations were drafted with AI assistance (see the [AI disclosure](#ai-disclosure)) and **have not yet been reviewed by native speakers**. Every language needs a reviewer, so pick any one you speak.

| Language | File | Status |
| --- | --- | --- |
| English | [EN](subtitles/A_Quarter_Century_of_Processing_EN.srt) | Reference transcript |
| Chinese (Simplified) | [ZH](subtitles/A_Quarter_Century_of_Processing_ZH.srt) | ✅ Reviewed |
| Chinese (Traditional, Taiwan) | [ZH-TW](subtitles/A_Quarter_Century_of_Processing_ZH-TW.srt) | ☑️ Needs review |
| French | [FR](subtitles/A_Quarter_Century_of_Processing_FR.srt) | ✅ Reviewed |
| German | [DE](subtitles/A_Quarter_Century_of_Processing_DE.srt) | ☑️ Needs review |
| Hindi | [HI](subtitles/A_Quarter_Century_of_Processing_HI.srt) | ☑️ Needs review |
| Japanese | [JA](subtitles/A_Quarter_Century_of_Processing_JA.srt) | ☑️ Needs review |
| Korean | [KO](subtitles/A_Quarter_Century_of_Processing_KO.srt) | ☑️ Needs review |
| Persian | [FA](subtitles/A_Quarter_Century_of_Processing_FA.srt) | ☑️ Needs review |
| Portuguese (Brazil) | [PT-BR](subtitles/A_Quarter_Century_of_Processing_PT-BR.srt) | ☑️ Needs review |
| Spanish (South American) | [ES](subtitles/A_Quarter_Century_of_Processing_ES.srt) | ✅ Reviewed |
| Turkish | [TR](subtitles/A_Quarter_Century_of_Processing_TR.srt) | ✅ Reviewed |

When you've reviewed a whole file, change its status to **Reviewed** in your pull request. If you reviewed only part of it, write which subtitle numbers you covered, for example "Reviewed 1–103".

## How to help

1. Open the subtitle file for a language you speak natively.
2. Watch the relevant part of the video for context. Use the [English subtitles](subtitles/A_Quarter_Century_of_Processing_EN.srt) as a reference, and check the audio when the meaning is unclear.
3. Correct the translation. Focus on accuracy, natural phrasing, spelling, punctuation, and readability at the video's pace.
4. Submit a pull request describing the language and the corrections you made. Mention any wording you're unsure about so others can help review it.

You can make small edits directly on GitHub: open the file, select the pencil icon to edit it, and follow GitHub's prompts to propose your changes and create a pull request. A GitHub account is required; no local setup is needed.

If you'd rather suggest a correction without editing a file, [open an issue](https://github.com/processing/processing-quarter-century-subtitles/issues). Include the language, timestamp or subtitle number, current text, and your suggested replacement. A brief explanation helps reviewers understand the change.

## Find your way around the video

Every subtitle file has the same 221 numbered entries with the same timestamps, so subtitle 140 in Korean matches subtitle 140 in English. Use the numbers to find a section and to point to a line in your pull request.

| Time | Subtitles | Chapter | Speakers |
| --- | --- | --- | --- |
| [00:00](https://www.youtube.com/watch?v=5Z8N9tghPRE) | 1–12 | Intro | Xin |
| [01:03](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=63s) | 13–87 | Processing History | Cassie (13–40), Moon (41–56), Raphaël (57–69), Cassie (70–87) |
| [06:41](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=401s) | 88–139 | p5.js History | Cassie (88–103), Q (104–126), Raphaël (127–139) |
| [10:32](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=632s) | 140–171 | Processing 5 Announcement | Moon |
| [12:45](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=765s) | 172–186 | A Heartfelt Thank You to the Contributor Community | Raphaël |
| [13:43](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=823s) | 187–197 | Processing Foundation Maintenance Fund | Xin |
| [14:36](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=876s) | 198–206 | Processing Foundation Development Fund | Xin |
| [15:12](https://www.youtube.com/watch?v=5Z8N9tghPRE&t=912s) | 207–221 | Closing | Cassie, then everyone |

Each subtitle file marks a change of speaker by starting that subtitle with the speaker's name, for example `MOON:`.

## People and pronouns

In languages where verbs, adjectives, or articles change with gender (for example French, Spanish, Portuguese, German, and Hindi), use the forms that match each person's pronouns.

| Person | Pronouns | Role in the video |
| --- | --- | --- |
| Cassie Tarakajian | they/them | Presenter |
| Moon Davé | she/her | Presenter |
| Qianqian Ye (Q) | she/her | Presenter |
| Raphaël de Courville | he/him | Presenter |
| Xin Xin | they/them | Presenter |
| Stef Tervelde | he/him | Mentioned in subtitles 135–136 |

For people who use they/them, rephrase so the sentence doesn't need a gendered form rather than using inclusive markers like *·e* or *-x*. For example, in French, "j'ai assisté à une présentation" avoids choosing between *allé* and *allée*.

## Glossary

These terms come back throughout the talk. Keeping them consistent within a file makes the talk easier to follow.

| English | Guidance |
| --- | --- |
| loom, thread, tapestry | The talk is built on a weaving metaphor. Use your language's real weaving vocabulary rather than a literal translation. |
| warp / weft | Weaving terms for the threads that stay fixed (warp) and the thread that passes across them (weft). The talk compares them to `setup` and `draw`. |
| `setup`, `draw` | Function names in Processing code. Keep them in English. |
| low floors, wide walls, high ceilings | A known phrase from creative-computing education: easy to start, many directions to explore, no limit on ambition. Translate the image, not word for word. |
| sketch | What Processing users call a program. Many languages keep it in English. |
| contributor, steward, maintainer | Roles in the p5.js community, from newest to most responsible. Use the terms your language's open-source community uses. Leaving "steward" in English is fine if there's no good equivalent. |
| Maintenance Fund, Development Fund, Processing Foundation | The Processing Foundation's two new funds, and the foundation itself. You can translate these names (the French, Japanese, Korean, Chinese, and Persian files translate "Foundation") or keep them in English, but be consistent. |
| free software | Free as in freedom, not only free of charge. Use your language's established term (for example *logiciel libre*, *software libre*). Subtitle 209 is an exception; see [Open questions](#open-questions). |
| Processing, p5.js, Processing Community Day, Deep Space | Names. Don't translate them. |

## Editing guidelines

- Preserve the speaker's meaning and tone while using phrasing that feels natural in your language.
- Keep names and project names, such as Processing and p5.js, accurate and consistent.
- Keep subtitles concise and use line breaks that are easy to read on screen.
- Retain speaker labels and sound cues such as `[music]` and `[applause]`, translating them where appropriate.
- For translation fixes, keep subtitle numbers and timestamps unchanged. If you spot a timing problem, describe it in your pull request or an issue.
- Save files as UTF-8 and preserve the `.srt` structure: a subtitle number, a timestamp line, the subtitle text, and a blank line before the next entry.

For example:

```srt
9
00:00:48,800 --> 00:00:51,590
Tonight we are here
to celebrate Processing.

```

### Readability

Viewers need time to read each subtitle before the next one appears. As a rough guide:

- **Use at most two lines per subtitle.**
- **Keep lines short.** About 42 characters for languages written in the Latin alphabet, Cyrillic, Devanagari, or Arabic script. About 16–20 characters for Chinese and Japanese, and about 20 for Korean.
- **Don't rush the viewer.** If a subtitle shows for only a second or two, shorten it, even if that means dropping a filler word. Condensing is normal in subtitling, as long as the meaning stays.
- **Split a sentence across subtitles where the speaker pauses**, not in the middle of a name or a phrase.

### Language-specific notes

- **Persian (FA):** Each text line starts with an invisible right-to-left mark (U+200F). It keeps lines that begin with a Latin word, such as a speaker label or "Processing", displaying right-to-left. Don't delete it. If your editor makes this hard, describe your changes in an issue instead.
- **Chinese and Japanese:** Following common subtitling practice, line-final commas and full stops are replaced with spaces or line breaks. Question marks, exclamation marks, and quotation marks stay.
- **Chinese (Traditional, Taiwan):** The file uses Taiwan vocabulary (軟體, 程式碼, 專案). If you want a Hong Kong variant, add it as a new language with the code `ZH-HK`.
- **Spanish (ES):** The file uses Spain Spanish (*vosotros*, *ordenador*). A Latin American variant would be welcome as a separate file, `ES-419`.

## Open questions

These lines were hard to translate or check without a native speaker. They're a good place to start.

- **All languages, subtitles 162 and 175:** The speaker interjects ("Yes, that's right", "Yeah"). If you hear a different person speaking in the video, say so in an issue.
- **Hindi, subtitle 98:** "People of color" is translated as *अश्वेत और अल्पसंख्यक लोग*. Hindi has no settled equivalent, so suggestions are welcome.
- **All languages, subtitle 129:** "A well-loved family home" is a polite way of saying worn or showing its age, with affection. A literal "well-loved" can lose the wear and just repeat "loved by millions" from the previous subtitle. In French, *bien aimée* was a poor fit, and the file now uses *vieille maison de famille*. Subtitle 130 ("started to show their age") continues the image.
- **All languages, subtitles 173–174:** The "dog years" joke ("the same questionable mathematics we use for dogs"). Processing is 25 years old, which the speaker converts to 250 "software years" by multiplying by ten, a looser version of the idea that a dog ages seven years for each human year. Not every language has this idea. If yours doesn't, keep the joke understandable, or replace it with a comparable expression of your own, as long as the 25 to 250 arithmetic still works.
- **All languages, subtitle 209:** "Free software is expensive to make" plays on *free* meaning both "libre" and "gratis". Most files use the established term for free software, which loses the contrast with "expensive". The French file uses *gratuit* here, since the previous subtitle already says *distribué gratuitement*. The Hindi and Japanese files already lean toward "free of charge". Check whether your language needs the same adjustment.
- **All languages, subtitle 4:** The French, Spanish, and Portuguese files say "before the pixel, there was the stitch" (*le point*, *el punto*, *o ponto*) instead of "threads", because the word also means a dot, which echoes the pixel. This is a deliberate adaptation. In your language, use it only if one word covers both stitch and dot or pixel-sized unit. Otherwise keep "threads".
- **Japanese, Korean, Persian, subtitle 135:** "Tervelde", the Dutch surname of Stef Tervelde, is transliterated by ear. Please check the spelling and the pronunciation (roughly *ter-VEL-duh*).
- **Chinese (Simplified), subtitles 113–116:** "Steward" is translated as 管理员, which is a loose fit.

Before submitting, reread your changes alongside the video and check that you haven't accidentally changed the timing or removed an entry. Keep each pull request focused on one language when possible.

## Add a language

New translations are welcome too. Copy the English subtitle file as a starting point, keep its numbering and timestamps, and translate the text.

- **Filename:** `A_Quarter_Century_of_Processing_<LANGUAGE-CODE>.srt`, using a [BCP 47 language code](https://en.wikipedia.org/wiki/IETF_language_tag), for example `IT`, `PT-PT`, or `ES-419`.
- **Files:** Add the file to `subtitles/`, and add a row to the table under [Available subtitles](#available-subtitles).
- **Pull request:** Include the language and any regional variant in the description.

Before you start, [open an issue](https://github.com/processing/processing-quarter-century-subtitles/issues) saying which language you're working on, so two people don't translate the same one.

## AI disclosure

The initial translations, as well as this README, were produced with LLM assistance (GPT 6.1 and Opus 5.5), under the supervision of Raphaël de Courville ([@sableraf](https://github.com/sableraf)), who takes responsibility for its content. If you find an error in it, [open an issue](https://github.com/processing/processing-quarter-century-subtitles/issues).

## Video credits

- **Producer:** Xin Xin
- **Presenters:** Cassie Tarakajian, Moon Davé, Qianqian Ye, Raphaël de Courville, and Xin Xin
- **Software and artwork:** Charlotte McElwain
- **Title card:** Kiel Danger Mutschelknaus
- **DoP, edit, sound design:** Elisa Unger
- **2nd AC, sound:** Jens Vetter

Special thanks to the Ars Electronica’s Deep Space 8K team.
