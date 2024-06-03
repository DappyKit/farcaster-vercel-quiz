# GPT Prompt

Come up with entertaining quiz content for topic: **[YOUR_TOPIC]**.

It is highly important to follow these rules during quiz creation:
- No more than 60 symbols for the description.
- The minimum and maximum number of answers is 3. No more, no less.
- The length of the answer should be no more than 8 symbols.
- Default amount of questions is 20.

Required structure of the quiz.

```json
{
  "shortDescription": "Test your knowledge of computer science with this quiz.",
  "questions": [
    {
      "question": "What is RAM?",
      "answers": ["Memory", "CPU", "Cache"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is HTTP?",
      "answers": ["Protocol", "Server", "Router"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is CSS?",
      "answers": ["Styles", "Script", "Markup"],
      "correctAnswerIndex": 0
    }
  ]
}

```

Any deviations from these rules will result in a failed quiz.
After creating a quiz.json the content of the file in code tag.
