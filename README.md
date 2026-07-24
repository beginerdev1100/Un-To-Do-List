# The Un-To-Do List

**Live app:** https://beginerdev1100.github.io/Un-To-Do-List/

A to-do app built around one contrarian idea: **deciding what you're *not* doing today is as important as deciding what you are.**

Every other to-do app punishes you with an ever-growing list of guilt. The Un-To-Do List gives you a second column — *Not doing today* — where you deliberately set tasks aside, guilt-free. When you're ready, you pull them back and get rewarded for it.

## How it works

- **Today's tasks** — your normal list. Add tasks, optionally give them a due date, check them off.
- **Not doing today** — the guilt-free zone. Setting something aside gets you an affirming note ("Later is a valid answer."), not a red overdue badge.
- **Points** turn follow-through into a game:
  | Action | Points |
  |---|---|
  | Complete a task | **+10** |
  | Pick a task back up from *Not doing today* | **+5** |
  | Clean sweep — finish everything, including every task you'd set aside | **+20 bonus** |
- **Daily goal** — default 50 pts, tap the goal chip to change it. The progress ring turns gold when you hit it.
- **Due dates always win** — anything set aside that hits its due date automatically jumps back into Today's tasks. You can't procrastinate a deadline into the guilt-free pile.
- **Day summary** — a receipt-style breakdown of your day: what you did, what you let go, and your score.
- **Next day** — one click rolls the day over: finished tasks clear out, unfinished ones move to *Not doing today*, and a morning planner asks which set-asides you're ready to take on.
- **Export / Import** — your data is yours. It lives in your browser, and you can move it between devices as a small JSON file.

## Tech

- Single self-contained `index.html` — vanilla HTML/CSS/JS, zero dependencies, zero build step
- Data persists in `localStorage`; no account, no server, no tracking
- Responsive: two-column desktop layout that collapses on mobile
- Hardened against malformed imports and script injection in task text

## Run it locally

Download `index.html` and open it in a browser. That's the whole app.
