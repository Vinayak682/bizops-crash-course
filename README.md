# Biz Ops Crash Course

A one-page, phone-friendly study guide for a consumer-electronics demand planning (Biz Ops) interview: the weekly planning loop, 18 concepts explained from zero with worked numbers, PSI / accuracy / reallocation calculators, flashcards, a self-check quiz, likely interview questions and a 2-day plan.

Open it: https://vinayak682.github.io/bizops-crash-course/

All numbers are illustrative. AP1 / AP2 are company-internal terms with no public definition; the page explains what can be inferred and says to confirm.

## Planner Project

`project/` is a job simulation for people who know the terms but freeze when an interviewer says "walk me through it": https://vinayak682.github.io/bizops-crash-course/project/

You are the new demand planner at Nova Mobile US, an invented electronics company (three accounts: a carrier, a big-box retailer and an online marketplace; three products). Five parts:

- **The Loop**: the whole job in one picture. Product flows from factory to consumer, information flows back to the factory, with the planner's Monday-to-Friday and month-end on top. Includes a play-through, a labels-hidden recall test and a put-the-week-in-order drill.
- **Eight missions (Weeks 40–48)**: read a PSI, clean a promo spike, find a stock-out, survive Wednesday cutoff, write the Thursday report, allocate a late shipment, plan an end-of-life sell-down, grade the month for S&OP. Each has a chat briefing, the data, investigation, a decision with projected consequences, a debrief with the Excel move, and a memory picture (bathtub, flagged spike, empty shelf, three numbers, waterfall, late ship, melting ice cube, dartboard). Numbers carry over between weeks.
- **Interview Studio**: 40 questions across five types (process, concept, case, story, resume line), each with an answer structure, a recall cue, speak-or-type practice (browser speech recognition where available), key-point checking, a model answer, follow-up questions and self-rating. Includes a six-question mock interview.
- **Decoder**: paste a job description or resume bullets; each line is matched to what the work really is, the week where it was practised and how to answer about it.
- **My project**: the STAR story each finished week produces (built from the player's own choices) and resume bullets for a Projects section, framed honestly as a simulation project.

Progress is stored in this browser's `localStorage` under `planner-project-v1`. XP is shared with the Planning Arena: the page loads `../arena/js/core.js` for charts, XP, ranks and toasts. When you change a file in `project/js/`, bump the `?v=` number on its `<script>` tag in `project/index.html`; when you change `arena/js/core.js`, bump its `?v=` in both `arena/index.html` and `project/index.html`.

## Planning Arena

`arena/` is a game-style companion that teaches the wider demand planning toolkit by playing it: https://vinayak682.github.io/bizops-crash-course/arena/

- **17 modules in 5 acts**: supply chain cycle, demand planning cycle, demand-to-delivery and S&OP (with every stakeholder), seasonality, seasonal trends and decomposition, forecasting techniques, choosing a technique, forecast accuracy, forecast bias, over- and under-forecasting, ABC/XYZ classification, inventory levels, holding cost and EOQ, lead time, safety stock, reorder point, the bullwhip effect. Each has a diagram, a worked example, a simulation, an interview answer, a three-question boss check and a mnemonic.
- **Arena games**: Beat the Bots (forecast against six algorithms), the Beer Game, ROP Survival, ABC Sprint, Rapid Fire, Forecast Detective, S&OP Boardroom.
- **Retention**: XP and ranks, badges, a daily challenge, spaced-repetition flashcards (Leitner boxes) and a 20-question final exam with a printable certificate.

Plain HTML, CSS and JavaScript, no build step and no dependencies beyond Google Fonts. Progress is stored in the browser's `localStorage` only. The leaderboard rivals are reference strategies (bots), not other people.

When you change a file in `arena/js/`, bump the `?v=` number on its `<script>` tag in `arena/index.html` so returning visitors don't get a cached copy.
