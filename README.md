# AI QUALITY INSPECTOR: THE EVIDENCE LAB — Skills Bank | GitHub Pages

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). Target: 8–10 minutes, individual (the classroom version is for pairs — neighbours can compare findings while they play).

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## About the source activity (please read)
- The course notes give: the goal (**test an AI output for accuracy, bias and completeness before trusting it**), the exact sample output, the three questions (accurate? fair? complete?), 6 minutes in pairs, two debrief questions, and the tip that **the exact “47%” and “every customer responded positively” are the two red flags most groups should catch**. The worksheet handout itself is **not in the deck**.
- The sample output is preserved **exactly**: “Sales increased by exactly 47% last month thanks to our new marketing strategy, making it the best month in company history. Every customer who was contacted responded positively.” (In Arabic mode an Arabic translation is shown and the English original stays visible.)
- **All evidence records are SIMULATED, fictional training evidence written for this game** (labelled on every record): A sales summary (West region not yet reported), B campaign timeline, C company history with missing periods, D customer feedback sample. They are internally consistent (tested arithmetically): reported totals equal the sum of the three regions; the figure 47% reproduces only as +47.0% year-on-year for those three regions (+12.8% month-on-month); the discount (8 Sep) and seasonal promotion (1 Sep) pre-date the campaign (18 Sep); December 2024 (7.30) is higher than any plausible September (4.85 + West’s record 1.40 = 6.25); 180 of 1,200 customers responded (126 positive · 36 neutral · 18 negative), none from the West.

## The six phases
1. **Incoming report** — the draft arrives (paper + scanner sounds); the inspector role, the three questions and the simulated-evidence note.
2. **Evidence scan** — four tappable claims in the report: *47%* · *thanks to our new marketing strategy* · *the best month in company history* · *Every customer … responded positively*. For each: open the evidence records, link the ones that matter, judge it (**Verified / Unsupported / Contradicted / Not assessable**) and request what is missing. Not multiple choice; honest uncertainty is allowed.
3. **Three quality gates** — **Accuracy · Fairness · Completeness**: a verdict (incl. “insufficient evidence”), supporting reasons (some are traps) and your own reasoning. “Unsupported” is not “proven false”; “no bias found” is not “fair”.
4. **Repair the output** — an editable text area (starts from the original), writing moves that add sentence frames with [brackets] (not finished answers), live **transparent rule checks** (no unsupported certainty · no unverified cause · qualified claims · says what must be verified · states the basis or data limit · business-ready length), revision notes, **Copy Revised Output**.
5. **Release decision** — **APPROVE / REVISE / HOLD FOR VERIFICATION**. The best decision depends on the evidence and on the participant’s own rewrite (see below); feedback explains the consequence.
6. **Quality report** — claims investigated, the three judgments, revision notes, final rewrite, decision, hints, coins, score; **Copy** and **Download (.txt)**.

### How the best release decision is derived (transparent)
- If the rewrite still has an unsupported certainty, an unqualified causal claim or no qualifiers → **REVISE** is best.
- If it is safe (those three pass) but does **not** also state what must be verified and the data limit → **HOLD FOR VERIFICATION** is best.
- If it is safe **and** states what is unverified and the data limit → **APPROVE** is best, as a clearly preliminary note.
- Other choices earn partial credit when defensible (e.g. holding a safe text) and none when harmful (approving an unsafe text).

## Scoring (max 390)
| Part | Points |
|---|---|
| Each claim (×4) | judgment up to 20 (best status; 10 or 5 for defensible alternatives) + 5 for linking the key record + 5 for a useful evidence request − 5 for asking the AI to sound more confident → max 30 |
| Each gate (×3) | verdict up to 30 + reasons (+5 per good one, up to 3; −5 per unsupported) + 5 for your own reasoning (6+ words) → max 50 |
| Repair | 10 per rule check passed (6) + 10 for revision notes (6+ words) → max 70 |
| Decision | 40 (best) / 25 (defensible) / 10 / 0 + 10 for a written reason → max 50 |
Coins: 250 at start, hint = 50 (key record for a claim · where to look for a gate · which numbers the evidence supports · how to decide). Coins break ties. Ranks: ≥330 Chief Quality Inspector · ≥250 Senior Inspector · ≥170 Inspector · else Trainee Inspector.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, session name, copy EN/AR link, **Projector view**, live table (phase, four claim statuses, three gate verdicts, rewrite checks x/6, release decision, hints, coins, score, progress), expandable rows with claims vs best status, gate verdicts and notes, the **sanitized rewrite**, revision notes and the decision with its reason, **Debrief panel** (claim judgments, gate verdicts with the fairness warning, decisions, rewrite checks), Reveal/Hide leaderboard, CSV export, backup import. About **7 messages per player**.

## Honest limits
- The rewrite checks are **transparent keyword/structure rules**; they cannot judge whether a rewrite is truly good — they show whether the usual safeguards are present. The trainer receives a sanitized copy of each rewrite and notes to read.
- Only fictional training content is sent (claim statuses, verdicts, short notes, the rewrite of a fictional statement); emails, links and long digit strings are removed automatically. The `2026` PIN only hides the interface and the relay is public.
- **Not yet tested on real ntfy.sh or across real devices.** Tested in a headless browser against a local relay that imitates ntfy (SSE, polling, retries, storage blocked, Arabic, an emulated touch phone using taps; 70 checks). Run the two-device checklist before a live class. ntfy.sh free limits are per IP (~250 publishes/day): ~35 players on one network is a safe size.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone: open the player link (or type the code) → enter a name on the badge → **Begin investigation**. Move your finger/mouse over the landing report: the lens follows.
3. Laptop: the inspector appears in seconds. Phone: read the report, **Start the evidence scan**.
4. Phone: tap each of the four claims, open records A–D, link, judge, request evidence, record. Laptop: after the fourth claim the four status chips appear.
5. Phone: stamp the three seals, rewrite the statement (try a frame, watch the live checks), record it, take the release decision. Laptop: gates, rewrite checks and decision update; expand the row to read the sanitized rewrite and notes.
6. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it. Projector view shows the same.
7. Switch language on both; check RTL and that nothing is cut off on the phone.
8. Refresh the phone mid-case → **Resume case** continues where it stopped.
9. Laptop: **Reset session** → new code. Check Sound ON/OFF and “reduce motion”.
