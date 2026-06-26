# XQuiz - Java Quiz Application

XQuiz is a Java-based console quiz application built using Gradle. The project demonstrates object-oriented programming concepts and unit testing using **JUnit 5** for quiz and question management functionalities.

## Project Structure

```
XQuiz
│
├── app
│   ├── src
│   │   ├── main
│   │   │   └── java
│   │   │       └── com/crio/xquiz
│   │   │           ├── Question.java
│   │   │           ├── Quiz.java
│   │   │           └── Main.java
│   │   │
│   │   └── test
│   │       └── java
│   │           └── com/crio/xquiz
│   │               ├── QuestionTest.java
│   │               └── QuizTest.java
│
├── gradle
├── gradlew
├── gradlew.bat
├── settings.gradle
└── README.md
```

---

## Features

### Question Management

- Create quiz questions
- Store multiple answer choices
- Validate whether the correct answer exists in the choices
- Check user answers
- Retrieve question details

### Quiz Management

- Create quizzes
- Add multiple questions
- Attempt quizzes
- Calculate final score
- Reveal answer key
- Retrieve quiz information

---

## Test Coverage

### QuestionTest

Location:

```
app/src/test/java/com/crio/xquiz/QuestionTest.java
```

Tests Included:

- Constructor validation when the correct answer is missing from choices
- Correct answer validation
- Incorrect answer validation
- Retrieve answer choices
- Retrieve correct answer
- Retrieve question text

---

### QuizTest

Location:

```
app/src/test/java/com/crio/xquiz/QuizTest.java
```

Tests Included:

- Adding questions to a quiz
- Revealing the answer key
- Retrieving the list of questions
- Calculating the final quiz score
- Retrieving the quiz name

---

## Technologies Used

- Java
- Gradle
- JUnit 5

---

## Running the Tests

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd XQuiz
```

Run all tests:

### Windows

```bash
gradlew test
```

### Linux / macOS

```bash
./gradlew test
```

---

## Test Summary

| Component | Functionalities Tested |
|-----------|------------------------|
| Question | Constructor Validation, Answer Checking, Getters |
| Quiz | Add Question, Reveal Answer Key, Final Score, Getters |

---

## Future Improvements

- Multiple quiz categories
- Timed quizzes
- Randomized questions
- Difficulty levels
- Score leaderboard
- Persistent quiz storage
- Exception handling
- Parameterized JUnit tests
- Code coverage using JaCoCo

---

## Author

**Tejaswini Sruthi**

__GitHub: https://github.com/TejaswiniSruthi__
