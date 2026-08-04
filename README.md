# GenAI in Workshops — Presentation Slides

Quarto [reveal.js](https://quarto.org/docs/presentations/revealjs/) slide decks covering every episode of The Carpentries lesson
**[GenAI in Workshops: Instructor Training Bonus Module](https://carpentries.github.io/instructor-training-genai/)**.

## Decks

| File | Deck |
|:--|:--|
| `index.qmd` | Overview & Setup (objectives, prerequisites, schedule, learner profile) |
| `01-welcome.qmd` | Welcome |
| `02-landscape.qmd` | The GenAI Landscape |
| `03-practice.qmd` | Building Skill with Practice |
| `04-expertise.qmd` | Expertise and Instruction |
| `05-memory.qmd` | Memory and Cognitive Load |
| `06-feedback.qmd` | Building Skill with Feedback |
| `07-wrong.qmd` | How Not to be Wrong About AI |
| `08-wrap-up.qmd` | Wrap-up |
| `09-references.qmd` | Reference (full citation list) |

Each episode deck carries the lesson's questions, objectives, narrative content, exercises/discussions
(with their solutions on following slides), and key points. Trainer guidance from the lesson appears as
reveal.js **speaker notes** — press `S` during a presentation to open the notes window.

## Rendering

```bash
quarto render          # builds all decks into _slides/
quarto preview         # live preview while editing
```

Open `_slides/index.html` in a browser to start. Deck-to-deck links (schedule table, citation links)
work once everything has been rendered.

### Presenting

- `S` — speaker notes
- `F` — fullscreen, `O` — slide overview
- `B` — chalkboard, `C` — pen (drawing tools are enabled)
- `E` then print to PDF — export a deck to PDF (or append `?print-pdf` to the URL)

## Images

All figures from the lesson are included in `images/`:

| File | Source |
|:--|:--|
| `cr_intro_chatbot.png` | Lesson `episodes/fig/` — adapted from [Code Refinery](https://coderefinery.github.io/coding-with-ai/introduction/) (CC BY 4.0) |
| `cr_intro_ide_integ.png` | Lesson `episodes/fig/` — adapted from Code Refinery (CC BY 4.0) |
| `cr_intro_agentic.png` | Lesson `episodes/fig/` — adapted from Code Refinery (CC BY 4.0) |
| `skill-level.svg` | Referenced by the Expertise episode from [The Carpentries Instructor Training](https://carpentries.github.io/instructor-training/) |

Each image keeps the alt text supplied by the lesson.

## Notes

- The lesson's `motivation.md` episode ("Motivation and Demotivation") is commented out of the lesson's
  `config.yaml` and is still a TODO stub upstream, so it has no deck here.
- The "How Much Expertise Do You Need?" exercise in `03-practice.qmd` refers to a shared chart. Upstream
  this is a `FIXME` awaiting a tldraw link — prepare a shared whiteboard with two axes (task complexity ×
  expertise required) before delivering that exercise.
- Styling lives in `custom.scss`; shared format options are in `_quarto.yml`.

## Licence and attribution

Content is adapted from *GenAI in Workshops: Instructor Training Bonus Module* by The Carpentries,
licensed **CC BY 4.0**. Lesson source: <https://github.com/carpentries/instructor-training-genai>.
