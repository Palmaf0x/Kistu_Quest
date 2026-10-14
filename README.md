# Kitsu Quest 🦊

> **Level up your real life.** Kitsu Quest is a gamified life-progress tracker that turns your goals, habits and career path into quests, stats and a roadmap you can actually see yourself climb.

**Platforms (target):** iOS · Android · Windows · macOS · Linux
**Status:** Day 1, vision & planning. No framework chosen yet (see [`docs/LEARNING_PATH.md`](docs/LEARNING_PATH.md)).

---

## 1. Vision

Most productivity apps feel like chores. Kitsu Quest treats your life like an RPG: you are the main character, your goals are the main storyline, and every day is a set of quests that move your stats forward.

The app should make people **want** to open it every day. It works because it is:

- **Personal.** Every quest, goal and roadmap is written by the user. The app ships with no fixed idea of what "success" means.
- **Visible.** Progress is never hidden in a list. It shows up as stats, levels, streaks and a roadmap that fills in as you advance.
- **Yours to style.** Themes, icons and layout can be changed so the app feels like your own space.
- **Everywhere.** The same account and the same progress on phone and desktop.

## 2. Objectives

| # | Objective | What success looks like |
|---|-----------|-------------------------|
| O1 | Help users define a long-term direction | A user can build a roadmap from "where I am" to "where I want to be" (career, goals, life areas) |
| O2 | Turn that direction into daily action | Daily, weekly and monthly quests tie back to roadmap milestones |
| O3 | Make progress measurable and motivating | Stat sheet across life categories, XP, levels, streaks |
| O4 | Build the habit of planning ahead | A "Plan Tomorrow" space used the evening before |
| O5 | Give the user full ownership of the experience | Everything is user-defined and the look is fully customizable |
| O6 | Work across mobile and desktop | One account, synced progress, native-feeling app on each platform |

## 3. Core features

### 3.1 Roadmap: the path to greatness
- A personal roadmap toward goals and career (e.g. "Land a software engineering internship", "Run a half-marathon").
- Broken into **milestones**. Each milestone can be linked to quests.
- Visual progression (path or skill-tree style), with completed milestones unlocked and future ones visible ahead.
- Several roadmaps at once (career, health, finances, personal).

### 3.2 Quests
All quests are **created by the user**. Nothing is forced.

| Type | Resets | Example |
|------|--------|---------|
| **Daily quests** | Every day | "Study 1h", "Drink 2L of water", "Gym" |
| **Weekly quests** | Every week | "Finish 1 project feature", "3 cardio sessions" |
| **Monthly quests** | Every month | "Read 2 books", "Save $300" |

Each quest can carry:
- A **category** (which stat it levels up)
- An **XP reward** / difficulty
- An optional link to a **roadmap milestone**
- An optional reminder time

### 3.3 Plan Tomorrow
- A dedicated space to set up the next day the evening before: tasks, goals, intentions, time blocks.
- Tomorrow's plan becomes "Today" automatically at the start of the day.
- Unfinished items can be rolled over or dropped.

### 3.4 Stat sheet: your character
A character-sheet view showing progress in every area of life. Default categories (renamable and extendable by the user):

| Stat | Covers |
|------|--------|
| 🔥 **Ambition** | Career, projects, discipline |
| 🔮 **Future** | Planning, finances, long-term investments |
| 🧠 **Brain** | Learning, studying, reading, skills |
| 💪 **Physical / Body** | Training, sleep, nutrition, health |
| ✨ *Custom...* | Social, creativity, spirituality, anything the user wants |

Completing quests earns XP in the matching stat. Stats level up over time, and history and trends show how each area is growing.

### 3.5 Gamification layer
- XP, levels (overall and per stat)
- Streaks for daily and weekly consistency
- Achievements and badges for milestones
- Progress feedback: animations, sounds and haptics when a quest is completed

### 3.6 Deep customization
- **Themes:** a wide range of visual themes (colors, typography, backgrounds, mood). *Theme set to be supplied by the project owner.*
- **Icons:** custom icons for quests, stats and categories.
- **Content:** user-defined quests, categories, stats, roadmaps and reward values.
- Light and dark variants for every theme.

## 4. Target users

- Students and young professionals who want structure toward a career goal.
- Self-improvement and fitness-minded people who already like gamification.
- Anyone who wants a single place to see "am I actually progressing in life?"

## 5. Guiding principles

1. **User-defined over prescribed.** The app gives structure, the user gives meaning.
2. **Motivating, not guilt-inducing.** Missed days should not feel like punishment.
3. **Fast daily use.** Checking off a quest should take one tap.
4. **Offline-first.** Works without internet and syncs when back online.
5. **Privacy.** Life goals are personal data and are treated that way.
6. **Consistent everywhere.** Same experience on phone and desktop.

## 6. Roles on this project

| Area | Owner |
|------|-------|
| Vision, UI/UX design, themes, user feedback | Palma |
| Code implementation, architecture | Claude (AI pair) |
| Final decisions (framework, stack, scope) | Palma |

## 7. Roadmap (project)

- [x] **Phase 0:** Vision & objectives (this README)
- [ ] **Phase 1:** Learn the fundamentals and choose the stack ([`docs/LEARNING_PATH.md`](docs/LEARNING_PATH.md))
- [ ] **Phase 2:** UI/UX design: screens, user flows, first themes
- [ ] **Phase 3:** MVP: quests (daily/weekly/monthly), Plan Tomorrow, basic stat sheet, local storage
- [ ] **Phase 4:** Accounts and cloud sync across devices
- [ ] **Phase 5:** Roadmap builder, achievements, full theme and icon customization
- [ ] **Phase 6:** Beta testing, then store release (App Store, Google Play, desktop)

## 8. Tech stack

**To be decided.** The comparison of frameworks, languages and backends, with trade-offs, lives in [`docs/LEARNING_PATH.md`](docs/LEARNING_PATH.md).

---

*Kitsu Quest: every day is a quest.*
