# MATH 105 Final Exam Review Lecture

An interactive, self-paced review for the MATH 105 (Topics for Mathematical Literacy) final exam at University of Maryland Global Campus, Asia.

The lecture covers all 24 topics on the ALEKS final exam. Each topic pairs a worked example with a practice problem that students solve and check in the browser.

**Live page:** `https://<your-username>.github.io/<repo-name>/MATH105_Final_Exam_Review_Lecture.html`

## What students do

Every topic page has three parts:

1. **Key idea.** A short explanation and the formula to use.
2. **Worked example.** A solved problem revealed one step at a time.
3. **Your turn.** The matching problem from the Final Exam Review Workbook, with answer boxes and instant checking.

The worked examples and the practice problems use different numbers. Students see the method, then do the math themselves.

## Features

- **Answer checking.** Each box is marked right or wrong separately. Money answers must match to the cent, percents to the tenth, and counts to the whole number.
- **Hints before solutions.** A wrong answer shows the formula as a hint. The full solution unlocks after two attempts or a correct answer.
- **Progress tracking.** The sidebar marks each topic green once it is correct and amber once it has been tried. A counter tracks progress out of 24.
- **Submission summary.** The last page generates a copyable report of each topic's status for students to submit as directed.
- **Keyboard and mobile support.** Arrow keys move between topics. On narrow screens the sidebar collapses into a Topics menu.
- **No dependencies.** One HTML file. No frameworks, no external requests, no tracking, no stored data.

## Topics covered

| Section | Module | Topics |
|---|---|---|
| A. Percents, Discounts & Simple Interest | Consumer Math 1 | 1–7 |
| B. Compound Interest, Annuities & Loans | Consumer Math 2 | 8–11 |
| C. Exponential Functions | Exponential & Logarithmic Functions | 12 |
| D. Statistics | Statistics | 13–20 |
| E. Counting & Probability | Probability | 21–24 |

## Companion materials

The lecture works alongside two files built from the same content:

- **Final Exam Review Workbook (.docx).** Students download it from LEO, type their work into it, and check it against the answer key at the end.
- **Final Exam Review deck (.pptx).** The in-class version of the lecture, with Try It Yourself breaks and answer slides.

All three use the same topic order and numbering. Workbook Problem 8 is Topic 8 in the lecture and Slide Topic 8 in the deck.

## Using it in LEO (D2L Brightspace)

Link to the GitHub Pages URL instead of uploading the file. D2L's HTML editor strips `<script>` and `<style>` blocks, and a linked page avoids that entirely.

1. In Content, open the module.
2. Choose **Upload / Create → Create a Link**.
3. Paste the GitHub Pages URL.
4. Check **Open as External Resource** so the page opens in a new tab.

To send students to one topic, add its number to the end of the URL:

```
...MATH105_Final_Exam_Review_Lecture.html#t17
```

Use `#intro` for the start page and `#wrap` for the formula sheet and summary.

## Publishing with GitHub Pages

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set the source to **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. The page goes live within a few minutes at the URL shown at the top of the Pages settings.

To make the lecture load at the site's root URL, rename the file to `index.html`.

## A note on answers

The correct answers are stored in the page's source code, so a student who views the source can find them. This is fine for an ungraded review. Do not reuse this checking method for graded work.

None of the problems come from the actual ALEKS final exam or the ALEKS exam review. All numbers and scenarios are original.

## Credits

Created by Cynthia McGinnis, Associate Professor of Mathematics and Computer Science, UMGC Asia, for MATH 105 at MCAS Iwakuni and Sasebo, Japan.
