# Exam 1 — what to expect and how to prepare

**Monday, October 5, in class.**

## Logistics

- **75 minutes**, built to take about 60. Closed book — no notes, no internet,
  no AI.
- **You get a printed copy of the exam** and type your answers into a **Canvas
  quiz** in the Respondus LockDown Browser. Only what's in Canvas is graded; the
  paper is yours to write and think on.
- **Install LockDown Browser and open the practice quiz before exam day.** If it
  won't install or launch, tell me early — not at 9am on the 5th. Bring a
  charged laptop and adapter.
- **You'll type code as text**, with no autocomplete, no syntax highlighting,
  and no way to run it — another reason to know which function you want rather
  than how RStudio finishes the line.
- **No packages to load.** Assume `tidyverse` is available.

## How your code is graded

**Syntax is graded leniently. Choosing the wrong function is not.**

## What it covers

**Days 1–8**, R fundamentals through feature engineering
- **R fundamentals** — data types; what a logical comparison returns
- **Wrangling** — keeping and dropping rows and columns; grouping, and the
  difference between collapsing a group to one row and adding a column that
  respects the group; sorting; chaining steps into a pipeline
- **Reshaping and combining** — wide and long layouts; combining two tables:
  which rows survive, how many come out, which columns you end up with
- **Visualization** — reading `ggplot2` code and predicting the figure; reading
  a figure and identifying its code; spotting why a plot isn't what its author
  intended
- **Data quality** — inconsistent date formats and what goes wrong parsing them;
  pulling a piece out of a text field; missing values and the cost of dropping
  rows that have them
- **Exploratory analysis** — reading a correlation matrix, and what it doesn't
  tell you; outlier rules, their trade-offs, where outliers come from, and what
  to do with one
- **Feature engineering** — why transform a variable; interactions; encoding
  categorical variables

Weight is uneven: **wrangling is the largest block.** If time is short, start
there.

## How to study

1. **Re-do the activities cold** — by far the highest-value thing you can do.
   Work from the prompt in a blank file, *then* compare to your old answers. If
   you can do all eight, you're ready.
2. **Re-do the problem sets the same way** — prompt first, old answer second.
3. **Predict before you run.** Take a chunk from the slides and say what it
   returns, rows and columns included, before executing it. Several questions
   ask you to read code rather than write it.
4. **For each function, finish:** "I use this when I want to ..." / "It changes
   the number of **rows** / **columns** / neither" / "The thing people mix it up
   with is ..."
5. **Explain your choices out loud.** That's what the short-answer questions ask
   for, and it exposes what you only half-know.

**Skip** flashcards of argument names, memorising slides, and passive
re-reading. If you aren't producing or predicting something, you probably aren't
learning.

## Short answers

Two or three sentences is plenty — length isn't rewarded. Answer what was asked:
if it wants two reasons, give two; if it asks what you'd *do*, say so. Be
specific. "The data might be biased" scores below "the dropped rows aren't a
random subset, so the remaining sample isn't representative."

## Anything else

**Accommodations:** if you have them on file and haven't arranged this exam,
contact me **before Wednesday, September 30**.

**Questions:** class, office hours (Mo/We 1:00–2:00, Bauer 216), or a tutor
session. If something here is unclear, ask — you won't be the only one.
