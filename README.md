# 🤱 Mama & Baby Wellness — Product Roadmap

A living document tracking every feature idea for the Mama & Baby Wellness app.  
Built live with Shameen's first baby (due May 17, 2026) → future product for new moms everywhere.

**Live app:** https://higneyintl.github.io/shameen-wellness/  
**App repo:** https://github.com/higneyintl/shameen-wellness

---

## ✅ Already Built

- [x] 🤰 Pregnancy tab — daily wellness tracking (renamed from Stretch)
- [x] 💊 Prenatal vitamins — one-tap daily check-off
- [x] 💧 Water intake — tap-glass tracker (goal: 8/day)
- [x] 😴 Sleep — +/- counter (goal: 7+ hours)
- [x] 🚶 Movement / Walk — one-tap done
- [x] 🥩 Protein Goal — one-tap done
- [x] 👶 Kick Counts — tap + counter with progress bar (28+ weeks)
- [x] 🙏 Rest & Prayer — one-tap done
- [x] Daily Stretches — trimester-appropriate exercises with timers & rep counters
- [x] Progress ring — reflects ALL daily items combined
- [x] 📊 Summary tab — weekly bar chart, 35-day heatmap, all-time stats
- [x] 8-item daily glance in Summary (vitamins, stretches, water, sleep, movement, protein, rest, points)
- [x] 👶 Baby Guide tab — unlocks at birth date, daily activity + EC tip + development note
- [x] 🍼 Feed Log tab — breast/pump timer, oz input, diaper log, daily summary, 30-entry history
- [x] ⬅️ ➡️ Day navigation on all tabs (Pregnancy, Feed, Summary)
- [x] Past days fully editable — retroactive logging for exercises, QC, vitamins, feeds
- [x] Achievement badges (8 total)
- [x] Streak + points system
- [x] Confetti on daily completion

---

## 🏗️ In Progress / Next Up

### Onboarding & Settings
- [ ] **Onboarding questionnaire** — runs on first launch, sets all preferences
- [ ] **Settings screen** — all preferences editable at any time (nothing locked in from onboarding)
- [ ] Preference: Diapering (Traditional / EC / Combination)
- [ ] Preference: Faith / Mindfulness (Christian / General spiritual / Secular affirmations)
- [ ] Preference: Feeding approach (Breast / Pump / Formula / Combo)
- [ ] Preference: Early childhood method (Montessori / RIE / Waldorf / Attachment / Flexible)
- [ ] Preference: Parenting style (Natural-crunchy / Mainstream / Flexible)
- [ ] App language + labels adapt instantly when preference changes
- [ ] "Rest & Prayer" → "Rest & Affirmations" or "Rest & Meditation" based on faith pref
- [ ] EC features toggle on/off based on diapering preference

### Exercise Library & Customization
- [ ] **Browse & add exercises** — larger library to pick from beyond the baseline set
- [ ] **Remove exercises** from daily routine (hide, not delete — can re-add)
- [ ] **Reorder exercises** in routine
- [ ] **Create custom exercises** — name, type (timer/reps), duration, emoji icon
- [ ] Routine persists per-user in localStorage (`userRoutine[]`)
- [ ] Library includes: pelvic tilts, butterfly stretch, wall squats, hip flexor lunge, clamshells, figure-4, birth ball exercises, ankle circles, supported bridge, and more
- [ ] Custom exercise points value (editable)

### Week-by-Week Progression (from conception → postpartum)
- [ ] **Week 4–12 (Early pregnancy):** Minimal checks — vitamins, first OB appointment, cut caffeine
- [ ] **Week 10–12:** NIPT/genetic screening reminder, first ultrasound
- [ ] **Week 13–26 (Second trimester):** Anatomy scan, glucose test prep, kick counts unlock at 28 wks
- [ ] **Week 27–36 (Third trimester):** Full daily checks (current build)
- [ ] **Week 37–40 (Late term):** Hospital bag checklist, weekly OB reminder, birth prep focus
- [ ] **Postpartum (Day 0+):** Auto-switch to recovery mode — feed log, EC, personal recovery checks
- [ ] Stage unlocking — early pregnancy UI is intentionally simple and grows over time

### Baby Activity Library (for Baby Guide tab)
- [ ] **Montessori activities** by week of life — black & white cards, treasure baskets, mirror play, wooden toys
- [ ] **RIE activities** — uninterrupted floor time, observe-before-intervening approach
- [ ] **Waldorf activities** — natural materials, rhythm, simple dolls, oral storytelling
- [ ] Activities update as baby ages (Day 1–30 ≠ Day 60–90)
- [ ] Milestone badge when new activity type unlocks
- [ ] Activity shown adapts to chosen childhood approach from settings

---

## 💡 Future Features (Backlog)

### Tracking & Health
- [ ] Weight tracking chart
- [ ] Blood pressure log
- [ ] Glucose tracking (gestational diabetes)
- [ ] Mood tracker
- [ ] Sleep quality rating (not just hours)
- [ ] Custom reminders / notes per day
- [ ] Milestone markers (first kick, first ultrasound, etc.)
- [ ] First trimester symptom log (nausea, fatigue, spotting)
- [ ] Appointment log / next OB visit countdown

### Postpartum
- [ ] Postpartum recovery mode — auto-activates at birth date
- [ ] Mom's own recovery checks (bleeding, soreness, mood, pelvic floor)
- [ ] Baby weight tracking (weigh-ins)
- [ ] Growth chart

### Social & Sharing
- [ ] Partner view — share daily progress with spouse/support person
- [ ] Export weekly report (PDF)
- [ ] Share a day's summary as image

### Technical
- [ ] Cloud sync / backup (currently localStorage only — single device)
- [ ] PWA (installable on phone home screen without app store)
- [ ] Push notifications for daily reminders (requires PWA or native)
- [ ] App store launch (iOS / Android)
- [ ] User accounts / login

### Content
- [ ] Hospital bag checklist (unlocks ~35 weeks)
- [ ] Birth plan builder
- [ ] Postpartum meal ideas (nutrition for recovery + breastfeeding)
- [ ] Sleep guidance by baby age (age-appropriate expectations, not sleep training)

---

## 🎯 Product Vision

**The gap this fills:**  
Existing apps (What to Expect, BabyCenter) are information-heavy. Most moms use them just to see how many weeks they are. Real information comes from Instagram, videos, and AI. What's missing is a simple daily action guide — *not articles, just: what do I do today?*

**Core value:** "I don't need more information. I need to track what I'm actually doing each day."

**Key principles:**
- Progressive — starts simple in early pregnancy, grows with you
- Adaptive — preferences update any time, nothing locked in
- Action-first — daily tasks, not articles
- Inclusive — works for crunchy moms, mainstream moms, Christian moms, secular moms
- Accessible — makes Montessori, EC, and intentional parenting approachable without expensive schools

**The deeper principle:**  
*The app meets you where you are today, not where you were when you downloaded it.*

---

*Updated: 2026-03-14 | Built by Ava + Shameen*
