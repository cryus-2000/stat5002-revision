# STAT5002 Interactive Revision

A single-page revision site for an introductory statistics course, covering Weeks 1–15 from graphical summaries to logistic regression.

**Open it here: <https://cryus-2000.github.io/stat5002-revision/>**

It is written so that someone who missed a lecture can still follow each question, and so that a lucky guess still ends with the method explained.

## What is inside

| Part | Amount | Notes |
|---|---|---|
| Weeks dashboard | 1 | Progress and accuracy for all 15 weeks at a glance, with the weakest weeks pointed out |
| Weekly overviews | 15 | A short summary written in plain lecture English, one chart, key terms and one or two worked examples |
| Interactive demos | 8 | Small charts you can adjust yourself: the central limit theorem, the law of averages, confidence-interval coverage, normal areas and p-values, correlation, the t and chi-squared curves against the normal curve, and the logistic curve |
| Formula sheets | 15 | One per week, in their own tab, every formula on a named row, with a button to print all of them. Two course-wide reference tables sit underneath: which test to use when, and how to read R output |
| Which-test flowchart | 12 tests | On the Formulas tab. Follow the branches from the kind of data (counts, measurements, a fitted model) to the test. Every branch has an example, and selecting a test shows its null hypothesis, statistic, a worked example and the R call |
| Weekly practice | 348 questions | Multiple choice, true/false and matching, with instant feedback. Each question is labelled **Warm-up** (one step, to check a definition or a formula) or **Exam level**. Questions that describe a dataset show a few rows of it |
| Exam-level questions | 173 of the 348 | Every week has at least nine, written to the standard of the sample exam: several steps, options that are close to each other, and R output that prints more than you need. Several ask you to read a histogram or boxplot |
| Written-answer cases | 10 cases, 49 parts | Proportion, paired, two-sample and one-sample tests, both chi-squared tests, simple and multiple regression, model comparison and logistic regression. Write your own answer first, then check it against the options and a model written answer |
| Practice exam | 16 questions in 48 minutes | Drawn at random from the exam-level questions (a pool of 182), at least one from every week, marked only after you submit |

Topics by week: data and graphs, numerical summaries, normal curves, correlation and regression, probability, box models, the central limit theorem, interval estimation, Z-tests, one-sample t and bootstrap, two-sample tests, chi-squared tests, multiple regression, model selection, logistic regression.

## How to use it

1. Start from the **All weeks** tab and pick a week, or choose one in **Lecture**. A week you have not started opens on its **Overview** tab. Switch to **Practice** when ready, and open **Formulas** whenever you need them; your place in the questions is kept.
2. Answer a question. The page marks your choice and the correct answer, explains the working, and says why each of the other options fails. Explanations appear whether you were right or wrong.
3. Use **Practice set** to narrow the list to one kind of question, for example *Exam-style multiple choice* or *Written-answer cases*.
4. **Retry a missed question** cycles through everything you got wrong, across all weeks, with your earlier answer hidden.
5. **Practice exam** gives 16 questions against a 48-minute clock, without feedback. After you submit, it shows each solution and lists the weeks worth revisiting. Each new attempt draws a different paper.

Keyboard: `A`–`D` or `1`–`4` to answer, `←` and `→` to move between questions.

**Copy question for chat** copies the question, your answer and the page's explanation, so you can paste it into an AI assistant and ask for a hint or a similar question.

## Progress and privacy

Progress is stored in your own browser (`localStorage`), and there is no account. Your answers and progress are never sent anywhere. The only network request the page makes is to GitHub's public API, to show how many stars this repository has; offline, the count is simply left out. Progress does not follow you to another browser or device on its own.

- **Export progress** saves a file, `stat5002-progress.json`. **Import progress** on another device or browser loads it.
- **Reset all progress** clears everything, as does clearing the site's data in your browser.
- **Dark mode** is remembered separately on each device.

## Offline use

The whole site is one file. Download `index.html` and open it in a current browser; no internet connection or installation is needed. Formulas use the browser's built-in MathML support, so use a recent version of Chrome, Edge, Firefox or Safari.

## About the content

- This is an unofficial study aid. It is not produced or endorsed by any university or teaching team.
- All questions, explanations and figures were written for this page. It contains no lecture slides, official exam papers or official solutions.
- Numerical answers and the R output shown in questions were computed in R.
- A few questions go beyond what the lecture slides mark as examinable, or need a formula the exam would supply. They carry a label above the question and are left out of the practice exam.
- If you find a mistake, please [open an issue](https://github.com/cryus-2000/stat5002-revision/issues) with the week and question title.

## 中文简介

这是一个 STAT5002 统计入门课程的单页复习网站，覆盖第 1–15 周。打开上面的链接即可使用，也可以下载 `index.html` 离线打开。

- 首页是 15 周总览，显示每周进度和正确率。概览里有 8 个可以自己拖动的小演示（中心极限定理、置信区间覆盖率、t 分布与正态分布的对比等）。公式页里有一张"该用哪个检验"的流程图，从数据类型一路分支到 12 个检验，点开任一检验可以看到原假设、公式、算例和 R 写法。每周有概览、图示、术语解释和一到两道完整例题；公式表在单独的标签页里，下方附"什么情况用什么检验"和"R 输出怎么读"两张通用表，可一键打印。
- 348 道即时反馈的练习题，答对答错都给出解法，并说明其他选项错在哪。每道题标明是“热身”（一步，检查定义或公式）还是“考试难度”。
- 每周都有考试难度的选择题（共 173 道，多步计算、选项接近、R 输出里有用不到的值），另有 10 组大题练习（49 小问）：先自己写答案，再对照选项和参考写法。
- 模拟卷每次从考试难度的题（182 题的题库）里随机抽 16 题，限时 48 分钟，交卷后逐题讲解并列出需要重看的周。
- 进度只保存在你自己的浏览器里，答题记录不会上传；页面唯一的联网请求是向 GitHub 公开接口读取本仓库的 star 数；可以导出成文件，在另一台设备上导入。
- 支持深色模式。页面内容为英文，题目和解析均为自编，不含课件和官方样卷。
