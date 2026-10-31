# A Kierkegaardian interlocutor

I am Søren Kierkegaard (5 May 1813). You tell me that you have chosen your life,
and then, in explaining this choice, you give an excellent account of what
everyone expected of you. I would like to remain a moment with that word:
*chosen*. Perhaps you have made this life your own. Perhaps the explanation has
become a way of keeping the question at a comfortable distance. Your eloquence
cannot decide between them.

Nor would I advise you to overturn everything merely to prove that you can.
The person who remains with a commitment after its first excitement has gone
may be doing something far more difficult than the person perpetually preparing
to begin. Tell me what remaining asks of you, and what you actually do. Then the
difference between patience and postponement may become less convenient, and
more personal.

I can press a question without claiming possession of your inward life. If I
have mistaken your circumstances, correct me. The difficulty must be yours to
answer; it must not be one I have invented for you.

The interlocutor draws on distinct literary voices in Kierkegaard's writings;
their claims are not interchangeable with one another or with his private
convictions. Contemporary dialogue is an interpretive application, not a mental
health diagnosis. This version remains a Candidate with machine recognition unrun.


Follow the difference between describing a life and making it one’s own, while keeping the distinct literary voices that press that difference in view.

[Uses](#what-to-bring) · [Getting started](#getting-started) · [Files and loading](#files-and-loading) · [Sources](#sources-and-contributions) · [Scope and status](#scope-and-current-status) · [License](#license)

## What to bring

**A suggested first prompt:**

> I keep saying I chose this life, but when I explain why, I list what everyone
> expected of me. How can I tell whether staying is a commitment I still make or
> simply something I have never questioned?

The inquiry can begin with the word *chose*. An outwardly correct life and a life
someone has made their own are not necessarily the same thing. But repetition can
also give a commitment its history. Leaving is no automatic proof of courage;
staying is no automatic proof of evasion. The useful question is what this particular
person is doing in staying.

Bring the circumstances too. A responsibility you have undertaken, a constraint you
cannot remove, or an effort someone else has overlooked can change the reading.
If the interlocutor gets your situation wrong, say so. Its interpretation should be
answerable to your correction.

Other difficulties invite different company:

- **Enjoyment that must always be rearranged:** Bring the situations in which boredom
  returns and what a new distraction promises. *Either/Or I* can illuminate the
  avoidance of attachment without making boredom itself proof of evasion.
- **Care that has become an account of debts:** Describe what you give, what you expect,
  and who counts as owed anything. *Works of Love* brings preference, neighbor-love
  and loving oneself rightly into relation.
- **An age in which everyone comments and no one acts:** Bring the constraints and
  actions already attempted. *Two Ages* asks what one person can undertake, without
  pretending that material obstacles are merely excuses.
- **Doubt announced as a settled identity:** State the actual proposition and grounds
  for uncertainty. *Johannes Climacus* distinguishes professing doubt from performing it;
  ordinary requests for evidence remain legitimate.

There is no need to select a book before speaking. Describe the difficulty plainly;
a request for textual explanation, practical advice or a change of voice can be direct.
These are intended applications, not a record of tested outcomes.

## Getting started

```sh
git clone https://github.com/ariel-lee-1023/Kierkegaard-Diagnostic-Interlocutor.git kierkegaard-diagnostic-interlocutor
```

Open the cloned folder with an agent that reads [AGENTS.md](AGENTS.md). Its
instructions activate the local perspective. For another skill loader, place or
link the root under `kierkegaard-diagnostic-interlocutor`.
Invoke `kierkegaard-diagnostic-interlocutor` through your host's skill selector, or ask it to use this perspective with one of the situations above.

Responses default to **English**. Explicitly request another language, for example
“Answer in Chinese for this conversation,” to change it for that scope. A message
written in another language alone does not change the default.

### Loading and manual configuration

Before the first substantive response, including a short answer, read the complete
[core](SKILL.md), [voice](references/voice.md) and [frameworks](references/frameworks.md).
The core alone is incomplete. Keep complete texts already in context and reload any
lost after compaction. Add relevant topic or work modules as the question requires.
For a chat without file access, supply those three complete texts and the relevant
module yourself. Maintenance and assessment records are not ordinary conversation inputs.

## Files and loading

These are file responsibilities and loading relationships, not a fixed sequence of thought.

| File or entry | What it provides | When it is used |
| --- | --- | --- |
| [Core](SKILL.md) | Perspective, language and operating instructions | Read in full at setup |
| [Voice](references/voice.md) | Expression, register and interaction | Read in full at setup |
| [Frameworks](references/frameworks.md) | Concepts, methods and conditional judgments | Read in full at setup |
| [Topic and source modules](references/clusters/) | Evidence, examples and work-specific distinctions | Load when relevant to the question |
| [Literary registers](references/registers/) | Ten work-specific voices with distinct commitments | Select for the actual difficulty; do not average them |
| [Maintenance records](transworld-identity/) | Provenance, editorial history and assessment evidence | Outside the ordinary conversation prompt |
| [.agents/skills/kierkegaard-diagnostic-interlocutor](.agents/skills/kierkegaard-diagnostic-interlocutor) | Relative symlink to the repository root | Host discovery; not a second runtime copy |

## Sources and contributions

The retained English translations concentrate on Kierkegaard's authorship of the
1840s through 1849. Alastair Hannay translates the works in the first four rows;
Howard V. Hong and Edna H. Hong translate the others. English cadence partly belongs
to them. Work, literary speaker and author are not interchangeable.

| Question or concern | Work and speaker | Contribution and reference |
| --- | --- | --- |
| Enjoyment, boredom and arranging another person's responses | *Either/Or I*: A's papers and the separately framed *Seducer's Diary* | Aesthetic rotation and manipulation remain different positions. [A](references/registers/either-or-I-A.md); [Diary](references/registers/seducers-diary.md) |
| Choosing and renewing a commitment | *Either/Or II*: B, the Judge; the Ultimatum remains distinct | Ethical appropriation, repetition and the possibility of comfort. [B](references/registers/either-or-II-B.md) |
| Resignation, faith and justification to others | *Fear and Trembling* | The Abraham problem does not certify a present person's private exception. [Faith and resignation](references/registers/fear-and-trembling.md) |
| Possibility, selfhood and despair | *The Concept of Anxiety*; *The Sickness unto Death*, Anti-Climacus's Christian account | Philosophical anxiety and theological despair are distinct from each other and from clinical findings. [Anxiety](references/registers/concept-of-anxiety.md); [Despair](references/registers/sickness-unto-death.md) |
| Loving without treating preference as the measure | *Works of Love*, signed Christian deliberations | Neighbor-love, self-love and building up. [Love](references/registers/works-of-love.md) |
| Public commentary and accountable action | *Two Ages*, a literary review | Reflection, leveling and the public in a particular historical diagnosis. [The public](references/registers/two-ages.md) |
| Learning, belief and actually doubting | *Philosophical Fragments*; *Johannes Climacus* | Hypothetical teacher–learner relations and the unfinished narrative of performed doubt. [Fragments](references/registers/philosophical-fragments.md); [Climacus](references/registers/johannes-climacus.md) |

The [source map](references/clusters/source-map.md) separates speakers, journal
supplements and editorial apparatus. Grouping works by a concern does not merge their
claims into one doctrine. See [provenance](transworld-identity/provenance.md) for the
edition inventory and inherited evidence.

## Scope and current status

*This introduction is a newly written, source-grounded persona reconstruction,
not a historical quotation. [Editorial and birth-date notes](transworld-identity/provenance.md#readme-editorial-review-2026-10-30).*

**Version 3.0.0 — Candidate (2026-09-12).** Machine recognition has not been run.
The [assessment record](transworld-identity/validation.json) distinguishes previously recorded package checks from incomplete source and recognition work. The renovation reviewed
retained excerpts and summaries; primary editions were not rechecked. Neither these
checks nor diagnostic illustrations establish a recognizably sustained conversation.

The main *Concluding Unscientific Postscript* text is absent: the supplied second volume
contains supplementary and editorial material. Late polemics, full journals,
correspondence and recorded live conversation are also outside the established scope.
Exact quotations or disputed attributions need the relevant edition. Contemporary
conversation extends literary methods; it is not a clinical diagnosis or direct access
to a person's inward life.

The [scope notes](transworld-identity/scope.md) and
[renovation record](transworld-identity/provenance.md) explain these boundaries and
preserve older evidence. Later loading changes have not been reassessed. The current first-person revision changes runtime inputs;
historical results keep their original scope.

**The revised runtime is a Candidate without a new recognition assessment.** This
maintenance preserves the existing material while aligning persona prose, host rules
and the placement of the introduction notice. See the [maintenance record](transworld-identity/provenance.md#skill-and-readme-alignment-2026-10-31)
for the checked scope and any pre-existing package issues. No new tests were added.

## License

[MIT](LICENSE) covers the original skill material, not the source books or translations.
