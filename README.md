## AI Tutor

A personal AI tutor powered by Claude Code. It uses adaptive quizzing with spaced repetition to help you systematically master the specified topics, adjusting question difficulty to your skill level, tracking progress across sessions, and giving honest, detailed feedback on every answer. Just clone the repo, customize the topic list to your goals, and start quizzing. No app, no setup, just your terminal and a structured path from beginner to job-ready.

## Start learning

```bash
claude   # open Claude Code in the project directory
```

Then use the commands:

| Command | What it does |
|---------|--------------|
| `/quiz` | Generate a new adaptive quiz |
| `/review` | Score your answered quiz |
| `/status` | See your full skill overview |
| `/plan` | Get study recommendations |
| `/deep-dive` | Interactive tutoring on one topic |

---

## Folder Structure

```
ai-tutor/
├── CLAUDE.md                    # Claude's "brain" — role, rules, behavior
├── .claude/
│   └── commands/
│       ├── quiz.md              # /quiz — generate a new quiz session
│       ├── review.md            # /review — score answered quiz
│       ├── status.md            # /status — show skill overview
│       ├── plan.md              # /plan — suggest next study focus
│       └── deep-dive.md         # /deep-dive — deep-dive into a topic
├── skills/
│   └── topics-list.md           # Master topic list (you edit this)
├── progress/
│   ├── skill-levels.json        # Auto-updated skill scores per topic
│   └── session-history.json     # Log of all past sessions
├── quizzes/
│   ├── session-001.md           # Generated quiz (you answer here)
│   ├── session-001-review.md    # Claude's scored review
│   ├── session-002.md
│   └── ...
└── resources/
    └── study-notes.md           # Optional: your personal notes
```

---

## Typical Workflow

```
1. /quiz          → Claude generates session-005.md
2. Open quizzes/session-005.md in your editor, write your answers
3. /review        → Claude scores it, creates session-005-review.md,
                     updates your skill levels
4. /status        → See where you stand
5. /plan          → Get recommendations for what to study next
6. Study the recommended topics
7. /deep-dive     → Optional: get tutored on a weak area
8. Repeat from 1
```

---

## Customization Tips

**Adjust the topic list**: The `skills/topics-list.md` file is yours. Add topics
you encounter in job postings, remove ones not relevant to your target roles.

**Adjust difficulty curve**: Edit the level descriptions in `CLAUDE.md` if the
progression feels too fast or slow.

**Add domain-specific sections**: If you're targeting specific industries, add a dedicated topic section.

**Track time spent**: You can add a field to session-history.json for study hours
to correlate effort with improvement.
