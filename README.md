# Baltimore Catechism No. 2 JSON

## Introduction

The **Baltimore Catechism** is a classic Catholic religious instruction text introduced in 1885 and used throughout Catholic schools in the United States until the 1960s. Published in four volumes, it served as the standard for teaching the fundamentals of the Catholic Faith to generations of students.

**Baltimore Catechism No. 2** specifically presents the essentials of Catholic doctrine in 37 lessons and 421 questions, designed for sixth through ninth graders and those preparing for Confirmation. Each lesson consists of clear, concise questions and answers, making it a classic resource for catechesis and religious education.

## JSON Structure Outline

The JSON file is structured as follows:

```json
{
  "title": "Baltimore Catechism No. 2",
  "lessons": [
    {
      "lesson_number": <int>,
      "lesson_title": <string>,
      "questions": [
        {
          "number": <int>,
          "question": <string>,
          "answer": <string>
        },
        ...
      ]
    },
    ...
  ]
}
```

- **title**: The title of the catechism volume.
- **lessons**: List of all 37 lessons.
  - **lesson_number**: Sequential lesson number (1–37).
  - **lesson_title**: Full lesson heading as found in the text.
  - **questions**: List of question/answer pairs for the lesson.
    - **number**: Question number within the catechism (1–421).
    - **question**: The question text.
    - **answer**: The answer text (may span multiple lines in the original).

---
