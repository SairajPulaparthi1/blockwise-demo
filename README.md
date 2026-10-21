# Blockwise

**A personal scheduler that ranks work by priority and time needed, not just due dates, and explains why every block landed where it did.**

**[▶ Try the live demo](https://sairajpulaparthi1.github.io/blockwise-demo/)** (my real UF class schedule and routine, with sample assignments; your changes stay in your browser)

## The idea

Calendars show when things are due, not when to do them. Blockwise takes a student's classes, routines and deadlines and builds the plan for them:

- **Ranks work by priority × hours left ÷ days left**, so a big project due in two weeks can outrank a small task due tomorrow.
- **Protects the routine first.** Classes (with buffers), exams, gym, recurring activities like basketball and pickleball, meals and downtime after 8pm are placed before any work.
- **Splits work into stages.** Group meetings are booked as their own blocks, and the stages after them wait until the meeting happens.
- **Connects study to exams.** Every exam automatically gets a study plan starting ten days out, and assignments that cover its material feed into it. Move the exam and the plan moves with it.
- **Explains itself.** Every block says why it's there, and the Today screen shows open time, top priority and what slips if you skip today's block.
- **Watches the load.** A pressure meter compares the next 7 days of work with realistic focus time (green, yellow, orange, red), and flags anything that won't fit before its due date.
- **Learns from check-ins.** Mark blocks Done, Different time or Skipped; completed tasks record estimate vs. actual by course and type.

## Built for daily use

- **Today, at a glance:** one "Up next" card with **▶ Start focus** (a countdown ring that logs the time when you finish) and **✓ Mark done**, then a one-line-per-item timeline of the rest of the day, what's due soon, and the week's load.
- **Add a task in one line:** press **N** (or **+ Add task**) and type *"SQL homework 4210 due fri 2h"*. It picks out the course, due date, time needed and type, and shows a preview before you press Enter.
- **Quick check-ins:** past blocks ask Done / Other time / Skipped, and anything unfinished moves to a later slot on its own.
- **Me:** your name, classes, gym, weekly activities (basketball, pickleball), meals, sleep, a backup download and restore, and the full "how it decides" rules.

Four screens: **Today · Week · Tasks · Me**, in a dark, futuristic theme with University of Florida blue and orange as neon accents.

## About this demo

A single HTML file with plain JavaScript and no build step or server. The demo uses my own Fall 2026 schedule at the University of Florida: ISM half-semester modules on Mondays and Wednesdays, two online courses, gym around 2pm, basketball and pickleball. The assignments and exam dates are samples. Dates move with the calendar, so the plan always starts today. Use **Reset** (bottom left) to start over.
