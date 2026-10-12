# Xyla 成长周记 · 爷爷奶奶版 💛

Simplified-Chinese-only site for Xyla’s grandparents. Live: https://melodylovepug.github.io/xyla-weekly-zh/
Melody’s English site: https://github.com/melodylovepug/xyla-weekly (https://melodylovepug.github.io/xyla-weekly/).

## Audience and voice
- Readers: grandparents who haven’t read parenting books. Address them as **您**, warm, respectful, never preachy. Acknowledge their experience first, then share “a new idea.” No “错误/必须/千万不要” lectures.
- Write in natural native Mandarin from the meaning. **Never translate the English site line by line.** Content is written for grandparents, not for Melody: what *you* (grandparent) can do, say, and avoid.
- Every week must actually teach the space-and-independence philosophy in practice (Montessori, Reggio Emilia, RIE/Pikler respect): observe first, don’t interrupt focus, don’t over-help (wait 5 s, help one small step), let her struggle a bit, let her get messy, don’t chase-feed or carry her when she can do it herself, describe instead of “真棒”, tell her before you handle her. Gently explain why older habits (追着喂、一直抱、怕脏、什么都夸、马上帮) can get in her way, always with the loving intention behind them. Safety stays non-negotiable (楼梯、插座、马路、水、小物件).
- Concrete grandparent do’s/don’ts and **scripts in Chinese** (`scripts`) every week.

## Structure
- `philosophy.html` + `weeks/philosophy.json`: standing intro page “给爷爷奶奶的话” (week-style page). Listed first in `topics/topics.json` and linked from every week (add the week id to its `weeks`).
- `week-XX.html` + `weeks/week-XX.json` with a **`zh` block only**. Same field shape as the English site (`bigThree`, `cards`, `daily`, `todos`, `quiz`, `plays`, `scripts`, `timeline`, `details`, `watch`, `sources`). Starts at Week 4.
- `topics/milk-at-one.json`, `topics/daycare-first-day.json`: Chinese only, no videos.
- `assets/`: copied unchanged from the English repo. Every HTML stub has `<html lang="zh-Hans" data-site-lang="zh" ...>`, which locks Chinese and hides the language toggle. Home texts come from `data-site-title`, `data-site-sub`, `data-site-how`.
- Bump `?v=` on every HTML after any asset/JSON change (same sed as the English README).

## Weekly rules (same as Melody’s site)
- **每页只管一周：** each week page covers exactly 7 days (Week 4 = 10月18日–24日). Don’t write “这两周”. Past pages keep their dates.
- Order: where she is now → do & don’t with why → what’s next → plays. Big 3 = actionable this week, each with **什么时候 / 怎么做 / 可以说**.
- Feelings: describe her real current phase and the next cycle.
- **Plays carry over:** review earlier weeks’ plays; keep the ones that still fit (or a harder version), drop outgrown ones (Ditty Bird, give-and-take, leave-and-come-back peekaboo, etc.).
- Videos: how-to only, Chinese-language, verified with YouTube oEmbed; if there’s no good Chinese one, skip it. Why-topics get text links.
- Compact fonts (shared CSS). Privacy: public repo, first name only, no birth date, photos, daycare name/details.
- Formula-fed only, already gets vitamin D daily.

一般信息，不是医疗建议；有疑问请问儿科医生。
