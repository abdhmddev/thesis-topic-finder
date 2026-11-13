# Install prompt

Copy everything inside the box below and paste it into a new Claude chat (Claude.ai, the desktop app, or Claude Code).

```
Please install the "Thesis Topic Finder" skill for me, then start it with me.

The skill lives in this public GitHub repo: https://github.com/abdhmddev/thesis-topic-finder

Its files (read all four, in full):
- https://raw.githubusercontent.com/abdhmddev/thesis-topic-finder/main/skills/thesis-topic-finder/SKILL.md
- https://raw.githubusercontent.com/abdhmddev/thesis-topic-finder/main/skills/thesis-topic-finder/references/intake-questions.md
- https://raw.githubusercontent.com/abdhmddev/thesis-topic-finder/main/skills/thesis-topic-finder/references/council.md
- https://raw.githubusercontent.com/abdhmddev/thesis-topic-finder/main/skills/thesis-topic-finder/references/templates.md

Install it the best way this app allows:
1. If you have a tool to save or propose a skill (a skill card I can approve), use it: name "thesis-topic-finder", the SKILL.md as its instructions, and the three reference files included (append them at the end of the instructions under clear headings if the tool takes only one file).
2. If you have a shell (for example Claude Code), install it as a skill:
   mkdir -p ~/.claude/skills && git clone --depth 1 https://github.com/abdhmddev/thesis-topic-finder /tmp/ttf && cp -r /tmp/ttf/skills/thesis-topic-finder ~/.claude/skills/
   Then tell me it is ready, and that I can also add it as a plugin with:
   /plugin marketplace add abdhmddev/thesis-topic-finder
3. If you can do neither, tell me in one line how to upload it myself (download https://github.com/abdhmddev/thesis-topic-finder/raw/main/dist/thesis-topic-finder.zip, then Settings → Capabilities → Skills → Upload skill), and meanwhile follow the four files above directly in this chat.

When it is installed, tell me in 2–3 lines what the skill does and show its 8-stage map. Then ask me: "Ready to start the tour?" When I say yes, begin Stage 1 (the interview) exactly as the skill says: short rounds of questions, in my language.

If web search is off, remind me to turn it on, because the research and fact-check stages need it.
```

---

### بالعربي
انسخ كل شي جوّا المربّع وحطّو بمحادثة جديدة مع Claude. هو بيقرأ الملفات من GitHub، وبيركّب المهارة بالطريقة اللي بيقدر عليها، وبعدين بيسألك إذا جاهز تبلّش.
