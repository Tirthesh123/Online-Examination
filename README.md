
# 📝 Online Examination System

## Objective

The **Online Examination System** is a Java Swing-based desktop application where:
- Users can log in with their credentials.
- They answer multiple-choice questions within a time limit.
- Scores are calculated automatically at the end.
- Admins can log in to add or manage questions (optional feature).

This project aims to automate quiz/exam processes with a timer and instant evaluation.

---

## Tools & Technologies

- **Programming Language:** Java (JDK 8+)
- **GUI:** Java Swing
- **IDE:** NetBeans or IntelliJ IDEA

---

## Steps Performed

1. **User Authentication:**
   - Created a login interface in Swing for students.

2. **Question Management:**
   - Stored questions and answers in Java arrays or lists.
   - Implemented methods to display one question at a time with options.

3. **Exam Timer:**
   - Integrated a countdown timer limiting total exam duration.
   - Automatically submitted answers if time expired.

4. **Navigation:**
   - Added "Next" buttons to move through questions.
   - Allowed reviewing previous questions if needed.

5. **Scoring:**
   - Calculated the final score based on correct answers.
   - Displayed results in a new window/dialog after submission.

6. **Validation:**
   - Handled unanswered questions and enforced single-choice selection.

---

## How to Run

1. **Compile the code:**
   ```bash
   javac OnlineExam.java
   ```

