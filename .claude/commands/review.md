Review and score my most recent quiz answers.

Steps:

1. Find the latest quiz file in `quizzes/` that doesn't have a review yet
2. Read my answers from the quiz file
3. Score each answer 0-10 with detailed feedback:
   - What was correct
   - What was missing or wrong
   - The complete/ideal answer
   - Practical tips or resources if I struggled
4. Calculate topic averages and update `progress/skill-levels.json`
   using weighted formula: new = (old *0.6) + (quiz* 0.4)
5. Update `progress/session-history.json` with this session
6. Save the review as `quizzes/session-NNN-review.md`
7. Show me a summary table:
   | Topic | Previous Score | This Session | New Score | Trend |
8. Highlight areas that need the most work
9. Suggest what to study before the next session
