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
| Weekly practice | 309 questions | Each week follows a reviewed learning order: **Foundations → Apply the ideas → Combine the ideas → Written cases**, with optional work last. Multiple-choice, true/false and matching questions give immediate feedback |
| Learning stages | 45 foundations, 122 application, 84 synthesis questions | Start with direct concepts and familiar output, then practise methods and finally combine ideas. Question format does not determine difficulty. The 24 cross-week questions are part of these stages; the menu can also show only those. Three additional questions are optional |
| Written-answer cases | 11 cases, 55 parts | Write and save a draft for every part, then **Submit whole case** to reveal all reference answers. A note of uncertainty counts as an attempt. Compare the working and self-check each part; the page does not automatically grade prose |
| MCQ practice test | 16 questions in 48 minutes | Drawn from a pool of 229, at least one from every week, marked only after you submit. This tests multiple choice, not the written-answer portion of a full exam |

Topics by week: data and graphs, numerical summaries, normal curves, correlation and regression, probability, box models, the central limit theorem, interval estimation, Z-tests, one-sample t and bootstrap, two-sample tests, chi-squared tests, multiple regression, model selection, logistic regression.

## How to use it

1. Start from the **All weeks** tab and pick a week, or choose one in **Lecture**. A week you have not started opens on its **Overview** tab. Switch to **Practice** when ready, and open **Formulas** whenever you need them; your place in the questions is kept.
2. Follow **Learning order · All questions**, or select a stage. The sidebar uses stage dropdowns: click a heading to open its question list, or click it again to close it. One list opens at a time and scrolls independently, so all stage headings remain visible. Each heading shows your checked progress; opening a question reveals it in its stage. For choice questions, the page marks your answer and explains the working and distractors. For written cases, complete all parts before submitting; no individual answer is revealed early.
3. In a written case, use **Previous part** and **Next part** to move through your drafts. After submitting, compare your answer with the reference and select **My answer meets the key points** or **I need to review this part**. **Revise this case** hides all its answers again while keeping your drafts.
4. **Retry a missed question** cycles through everything you got wrong, across all weeks, with your earlier answer hidden.
5. **MCQ practice test** gives 16 questions against a 48-minute clock, without feedback. After you submit, it shows each solution and lists the weeks worth revisiting. Each new attempt draws a different paper. Practise the written cases separately as complete groups.

Keyboard: `A`–`D` or `1`–`4` to answer, `←` and `→` to move between questions. Use `Tab` to focus a stage heading and `Enter` or `Space` to expand or collapse it.

**Copy question for chat** copies the question and your answer for tutoring. An unsubmitted written case copies only your draft and asks for a hint; its reference answer is not included.

## Progress and privacy

Progress is stored in your own browser (`localStorage`), and there is no account. Your answers and progress are never sent anywhere. The only network request the page makes is to GitHub's public API, to show how many stars this repository has; offline, the count is simply left out. Progress does not follow you to another browser or device on its own.

- **Autosave to a file** (Chrome or Edge on a computer) writes your progress to a file of your choice after every answer, so it survives if the browser clears its site data. Next time, click **Resume autosave**; if the browser has lost your answers, the page offers to load them from the file.
- **Export progress** saves a file, `stat5002-progress.json`. **Import progress** on another device or browser loads it.
- **Reset all progress** clears everything, as does clearing the site's data in your browser.
- **Dark mode** is remembered separately on each device.
- Reordering keeps question IDs and saved progress. Revised questions keep earlier answers and drafts with a notice to check them against the current wording; an earlier answer is not automatically regraded as an answer to the new question. Written-case submissions, drafts and saved MCQ practice tests are included in progress exports; written results are self-assessments, not automatically marked answers.

## Offline use

The whole site is one file. Download `index.html` and open it in a current browser; no internet connection or installation is needed. Formulas use the browser's built-in MathML support, so use a recent version of Chrome, Edge, Firefox or Safari.

## About the content

- This is an unofficial study aid. It is not produced or endorsed by any university or teaching team.
- All questions, explanations and figures were written for this page. It contains no lecture slides, official exam papers or official solutions.
- Numerical answers and the R output shown in questions were computed in R.
- Written cases ask you to define parameters, construct the method, show working and justify a contextual conclusion. Raw summaries, quantiles and necessary R values remain available; later parts do not supply the answers to earlier parts. Synthesis questions focus on combining statistical ideas, with manageable arithmetic.
- A few questions go beyond what the lecture slides mark as examinable, or need a formula the exam would supply. They carry a label above the question and are left out of the practice exam.
- If you find a mistake, please [open an issue](https://github.com/cryus-2000/stat5002-revision/issues) with the week and question title.

## 中文简介

这是一个 STAT5002 统计入门课程的单页复习网站，覆盖第 1–15 周。打开上面的链接即可使用，也可以下载 `index.html` 离线打开。

- 首页是 15 周总览，显示每周进度和正确率。概览里有 8 个可以自己拖动的小演示（中心极限定理、置信区间覆盖率、t 分布与正态分布的对比等）。公式页里有一张"该用哪个检验"的流程图，从数据类型一路分支到 12 个检验，点开任一检验可以看到原假设、公式、算例和 R 写法。每周有概览、图示、术语解释和一到两道完整例题；公式表在单独的标签页里，下方附"什么情况用什么检验"和"R 输出怎么读"两张通用表，可一键打印。
- 共 309 题。每周按“基础 → 应用 → 综合 → 整组书面题”排列，选学题放最后；基础 45 题、应用 122 题、综合 84 题、选学 3 题，另有 55 个书面小问。按实际推理及前置知识复查排序，直接读取和应用在前，综合判断在后。
- 左侧阶段标题做成下拉菜单，一次展开一组，题目列表内部滚动；所有阶段标题始终可见，不需要先收起才保留。点击标题切换或收起列表，跳转到题目时自动展开所在组并显示当前题。
- 11 组书面题（55 小问）必须整组尝试并提交后才显示参考答案；草稿自动保存。提交后按参考写法自评，不再以选对选项代替书面能力。不会的小问可以写下尝试或疑问。
- 书面题要求自己定义参数、建式、解释及下结论；保留必要 R 输出，移除提前透露前面答案的计算提示。综合题减少不必要的反推、枚举和繁琐运算。修订题保留旧答案和草稿，并提示按当前题面复查。
- 选择题模拟从 229 题的题池随机抽 16 题，限时 48 分钟；它不包含整场考试的书面部分。24 道跨周题保留，题目 ID 不变，已有进度继续使用。
- 进度只保存在你自己的浏览器里，答题记录不会上传；页面唯一的联网请求是向 GitHub 公开接口读取本仓库的 star 数；可以导出成文件，在另一台设备上导入。
- 支持深色模式。页面内容为英文，题目和解析均为自编，不含课件和官方样卷。
