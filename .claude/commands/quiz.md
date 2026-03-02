Generate a new quiz session for me.

Steps:

1. Read `skills/topics-list.md` for the full topic list
2. Read `progress/skill-levels.json` for my current levels
3. Read `progress/session-history.json` to check what was recently tested
4. Select 3-5 topics based on:
   - Priority to untested or low-scoring topics
   - Include 1-2 spaced repetition topics if due
   - Balance between different sections of the curriculum
5. Generate 8-12 questions adapted to my level per topic
6. Save the quiz as `quizzes/session-NNN.md` (increment session number)
7. Tell me which topics are covered and why you chose them
8. Remind me to answer in the quiz file and then run /review

Question format in the markdown:

- Number each question
- Show the topic tag in brackets, e.g. [Transformers]
- Show the difficulty level, e.g. (Level: 5/10)
- Leave space for my answer with `**Your Answer:**`
