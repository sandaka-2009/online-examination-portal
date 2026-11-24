# online-examination-portal
# Online Examination Portal

A clean, responsive, single-page web application built for conducting online multiple-choice examinations. Designed as a college project, it simulates real-world computer-based testing (CBT) interfaces with student verification, live countdown timers, question status tracking, and instant automated grading.

---

## Features

- **Candidate Verification & Instructions**: Validates student details (Full Name, Roll Number, Department, and Subject) before starting the exam and displays clear rules and marking schemes.
- **Live Countdown Timer**: A `15:00` countdown timer that turns red and pulses when under 2 minutes remain, automatically submitting the test when time runs out.
- **Interactive Question Palette**: Color-coded navigation grid allowing students to jump to any question and track their progress (`Answered`, `Not Answered`, `Marked for Review`, `Not Visited`).
- **Exam Controls**: Supports saving answers, clearing selected options, flagging questions for review, and navigating sequentially.
- **Submission Summary Modal**: Displays a quick breakdown of answered, unanswered, and marked questions before final submission.
- **Instant Scorecard & Answer Key**: Calculates total score, percentage, and Pass/Fail status immediately upon submission, complete with a question-by-question review and explanations.
- **Print / PDF Export**: Built-in print styling allows students to save or print their final scorecard cleanly.

---

## Tech Stack

- **HTML5**: Semantic structure for the registration form, exam dashboard, modals, and result views.
- **CSS3 / Tailwind CSS**: Responsive layout, custom scrollbars, status badges, and print-friendly stylesheets.
- **Vanilla JavaScript (ES6+)**: State management, timer logic, dynamic question rendering, and automated evaluation without external backend dependencies.

---

## Project Structure

```text
online-examination-portal/
├── index.html      # Complete single-file application (HTML, CSS, and JS)
└── README.md       # Project documentation
