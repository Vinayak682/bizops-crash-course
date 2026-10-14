# Biz Ops Crash Course

A one-page, phone-friendly study guide for a consumer-electronics demand planning (Biz Ops) interview: the weekly planning loop, 18 concepts explained from zero with worked numbers, PSI / accuracy / reallocation calculators, flashcards, a self-check quiz, likely interview questions and a 2-day plan.

Open it: https://vinayak682.github.io/bizops-crash-course/

All numbers are illustrative. AP1 / AP2 are company-internal terms with no public definition; the page explains what can be inferred and says to confirm.

## Planning Arena

`arena/` is a game-style companion that teaches the wider demand planning toolkit by playing it: https://vinayak682.github.io/bizops-crash-course/arena/

- **17 modules in 5 acts**: supply chain cycle, demand planning cycle, demand-to-delivery and S&OP (with every stakeholder), seasonality, seasonal trends and decomposition, forecasting techniques, choosing a technique, forecast accuracy, forecast bias, over- and under-forecasting, ABC/XYZ classification, inventory levels, holding cost and EOQ, lead time, safety stock, reorder point, the bullwhip effect. Each has a diagram, a worked example, a simulation, an interview answer, a three-question boss check and a mnemonic.
- **Arena games**: Beat the Bots (forecast against six algorithms), the Beer Game, ROP Survival, ABC Sprint, Rapid Fire, Forecast Detective, S&OP Boardroom.
- **Retention**: XP and ranks, badges, a daily challenge, spaced-repetition flashcards (Leitner boxes) and a 20-question final exam with a printable certificate.

Plain HTML, CSS and JavaScript, no build step and no dependencies beyond Google Fonts. Progress is stored in the browser's `localStorage` only. The leaderboard rivals are reference strategies (bots), not other people.

When you change a file in `arena/js/`, bump the `?v=` number on its `<script>` tag in `arena/index.html` so returning visitors don't get a cached copy.
