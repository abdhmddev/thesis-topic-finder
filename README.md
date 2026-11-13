# 🎓 Thesis Topic Finder

A Claude skill that takes any graduate student (MSc, MPhil or PhD, any field) on a **guided tour** to a strong, defensible thesis topic.

```
1 Interview → 2 Research → 3 Candidates → 4 Council → 5 Fact-check → 6 Verdict → 7 Proposal core → 8 Pitch kit
```

1. **Interview.** Claude asks short rounds of questions about your degree, background, skills, limits, goals, supervisors and your university's judging rules.
2. **Research.** It looks up your supervisors (roles, papers, open "future work") and the field (what changed recently, open problems, traps to avoid).
3. **Candidates.** It builds 4–6 real candidate topics, each with evidence, contribution, feasibility and risks.
4. **Council.** Seven advisors (an external examiner, a novelty checker, a supervisor-fit strategist, a lab engineer, a career pathfinder, a student advocate and an outsider) argue it out. Then they peer-review each other anonymously.
5. **Fact-check.** An independent check of every "nobody has done this" claim, with sources.
6. **Verdict.** A chairman picks one topic, narrows it until it is defensible, and names a fallback and the first step.
7. **Proposal core.** A comparison matrix of the closest papers, the research gap, the problem statement, research questions with H0/H1, and the method.
8. **Pitch kit.** A concept note, a supervisor pitch deck and a proposal draft.

It teaches as it goes, so you can defend every line at your viva.

---

## Install

### Option A: Claude.ai or the Claude desktop app (easiest)
1. Download **[thesis-topic-finder.zip](https://github.com/abdhmddev/thesis-topic-finder/raw/main/dist/thesis-topic-finder.zip)** (or zip the folder `skills/thesis-topic-finder` yourself).
2. In Claude, open **Settings → Capabilities → Skills** and click **Upload skill**.
3. Choose the zip. Make sure **Code execution** is on.

### Option B: Claude Code (as a plugin)
```
/plugin marketplace add abdhmddev/thesis-topic-finder
/plugin install thesis-topic-finder@thesis-topic-finder
```

### Option C: Claude Code (as a plain skill)
Copy `skills/thesis-topic-finder` into `~/.claude/skills/`.

## Use
Just say, in any language:
> "Help me find my thesis topic."
> "ساعدني لاقي موضوع thesis."

Claude starts the tour and asks you the first questions.

**Works best with** web search turned on. If you can, give it your supervisors' names and university, plus your course outline or proposal template.

## Repository layout
```
.claude-plugin/
  plugin.json
  marketplace.json
skills/thesis-topic-finder/
  SKILL.md                      ← the tour
  references/
    intake-questions.md         ← the interview
    council.md                  ← advisors, review, fact-check, chairman
    templates.md                ← cards, matrix, problem statement, proposal, deck
```

## Honesty rules built in
- No invented citations; anything unverified is marked "to confirm".
- No novelty claim survives without a fact-check.
- The student writes graded work in their own words, with an AI-use declaration if the university asks for one.

---

### بالعربي
مهارة لـ Claude بتاخد أي طالب ماجستير أو دكتوراه بجولة خطوة بخطوة. بتسألك أسئلة، وبتبحث عن الدكتور والمجال، وبتطلع ٤–٦ مواضيع. بعدين مجلس من ٧ مستشارين بيتناقش فيها، وفي تحقق مستقل من المراجع، وبالآخر بتطلعلك موضوع قوي ومرتّب مع proposal وعرض للدكتور.

**التنزيل:** نزّل [thesis-topic-finder.zip](https://github.com/abdhmddev/thesis-topic-finder/raw/main/dist/thesis-topic-finder.zip)، وبـ Claude روح على Settings ← Capabilities ← Skills ← Upload skill.

MIT License · Made by Abdelrahman Hammoud
