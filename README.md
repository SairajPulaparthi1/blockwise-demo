# Blockwise

**A personal scheduler that ranks work by priority and time needed, not just due dates, and explains why every block landed where it did.**

**[▶ Try the live demo](https://sairajpulaparthi1.github.io/blockwise-demo/)** (a sample student; your changes stay in your browser)

## The idea

Calendars show when things are due, not when to do them. Blockwise takes a student's classes, routines, deadlines and recruiting pipeline and builds the plan for them:

- **Ranks work by priority × hours left ÷ days left**, so a big project due in two weeks can outrank a small task due tomorrow.
- **Protects the routine first.** Classes (with buffers), exams, interviews, gym, a weekly club, meals and downtime after 8pm are placed before any work.
- **Splits work into stages.** Group meetings are booked as their own blocks, and the stages after them wait until the meeting happens.
- **Connects prep to events.** An interview automatically gets a tailored prep task (research, "why us", STAR stories, mock interview); an exam gets a study plan starting ten days out. Move the event and the prep moves with it.
- **Explains itself.** Every block says why it's there, and the Today screen shows open time, top priority and what slips if you skip today's block.
- **Watches the load.** A pressure meter compares the next 7 days of work with realistic focus time (green, yellow, orange, red), and flags anything that won't fit before its due date.
- **Learns from check-ins.** Mark blocks Done, Different time or Skipped; completed tasks record estimate vs. actual by course and type.

## Screens

**Today** (briefing and check-ins) · **Week** (time grid with daily load) · **Tasks** (ranking, stages and connections) · **Recruiting** (pipeline, interviews, thank-you notes) · **Routine** (classes, gym, meals, weekly goals) · **How it decides** (the rules, written out)

## About this demo

A single HTML file with plain JavaScript and no build step or server. The demo student, their courses and the companies are all made up, and dates move with the calendar, so the plan always starts today. Use **Reset** (bottom left) to start over.
