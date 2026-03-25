# Elon Musk — Claude Code Skills

> 16 actionable skills distilled from the mindset, methods, and philosophy of Elon Musk — built for Claude Code.

**Free and open source.** No account, no subscription, no API key required beyond your existing Claude Code setup.

---

## Installation

Choose the method that works best for your platform. All methods are free.

---

### Method 1 — Git Clone (All Platforms)

**macOS / Linux / WSL:**

```bash
git clone https://github.com/vibeailabs-tech/elon-musk-skills.git ~/.claude/plugins/elon-musk-skills
```

**Windows (PowerShell):**

```powershell
git clone https://github.com/vibeailabs-tech/elon-musk-skills.git "$env:USERPROFILE\.claude\plugins\elon-musk-skills"
```

Then register the plugin in Claude Code:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Method 2 — curl One-Liner (macOS / Linux / WSL)

Download and extract in a single command — no Git required:

```bash
curl -L https://github.com/vibeailabs-tech/elon-musk-skills/archive/refs/heads/main.tar.gz \
  | tar -xz --strip-components=1 -C ~/.claude/plugins/elon-musk-skills \
  --transform 's|^elon-musk-skills-main/||' \
  2>/dev/null || \
  (mkdir -p ~/.claude/plugins/elon-musk-skills && \
   curl -L https://github.com/vibeailabs-tech/elon-musk-skills/archive/refs/heads/main.tar.gz \
   | tar -xz -C ~/.claude/plugins/elon-musk-skills --strip-components=1)
```

Or the simpler two-step version:

```bash
mkdir -p ~/.claude/plugins/elon-musk-skills
curl -L https://github.com/vibeailabs-tech/elon-musk-skills/archive/refs/heads/main.tar.gz \
  | tar -xz --strip-components=1 -C ~/.claude/plugins/elon-musk-skills
```

Then register:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Method 3 — wget (Linux)

```bash
mkdir -p ~/.claude/plugins/elon-musk-skills
wget -qO- https://github.com/vibeailabs-tech/elon-musk-skills/archive/refs/heads/main.tar.gz \
  | tar -xz --strip-components=1 -C ~/.claude/plugins/elon-musk-skills
```

Then register:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Method 4 — Manual Download (All Platforms, No CLI Required)

1. Go to: [https://github.com/vibeailabs-tech/elon-musk-skills](https://github.com/vibeailabs-tech/elon-musk-skills)
2. Click **Code → Download ZIP**
3. Extract the ZIP
4. Move the extracted folder to:
   - **macOS / Linux:** `~/.claude/plugins/elon-musk-skills`
   - **Windows:** `C:\Users\YourName\.claude\plugins\elon-musk-skills`
5. In Claude Code, run:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Method 5 — Windows PowerShell (No WSL)

```powershell
# Create the plugins directory if it doesn't exist
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.claude\plugins\elon-musk-skills"

# Download and extract
Invoke-WebRequest -Uri "https://github.com/vibeailabs-tech/elon-musk-skills/archive/refs/heads/main.zip" `
  -OutFile "$env:TEMP\elon-musk-skills.zip"

Expand-Archive -Path "$env:TEMP\elon-musk-skills.zip" `
  -DestinationPath "$env:TEMP\elon-musk-skills-extract" -Force

Copy-Item -Recurse -Force `
  "$env:TEMP\elon-musk-skills-extract\elon-musk-skills-main\*" `
  "$env:USERPROFILE\.claude\plugins\elon-musk-skills"
```

Then in Claude Code:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Method 6 — GitHub CLI (`gh`)

If you have the [GitHub CLI](https://cli.github.com/) installed:

```bash
gh repo clone vibeailabs-tech/elon-musk-skills ~/.claude/plugins/elon-musk-skills
```

Then register:

```
/plugin install ~/.claude/plugins/elon-musk-skills
```

---

### Keeping Skills Up to Date

To update to the latest version at any time:

**macOS / Linux / WSL:**

```bash
cd ~/.claude/plugins/elon-musk-skills && git pull
```

**Windows (PowerShell):**

```powershell
cd "$env:USERPROFILE\.claude\plugins\elon-musk-skills"; git pull
```

---

## Requirements

- [Claude Code](https://claude.ai/code) — free to install
- That's it. No API keys, no paid subscriptions, no extra setup.

---

## Skills

### Part I — Pursue Purpose

| Skill                  | When to Use                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
| `be-useful`            | Evaluate whether any project, idea, or job is worth doing. Utility = Scale × Depth. |
| `physics-thinking`     | Pressure-test ideas, eliminate wishful thinking, reason from truth.                  |
| `knowledge-tree`       | Learn any new domain fast — trunk before leaves, broad then deep.                    |
| `long-game`            | Find purpose, think at decade scale, align work to what actually matters.            |

### Part II — Ultra Hardcore Work

| Skill                  | When to Use                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
| `hardcore-work`        | Apply The Algorithm. Cut bloat. Move faster. Build processes that work.              |
| `frontline-leadership` | Lead from where the work happens. Earn deep understanding.                           |
| `feedback-culture`     | Build teams where truth flows up and hard feedback is the norm.                      |
| `the-factory`          | Manufacturing as moat. Attack the constraint. The factory is the product.            |

### Part III — Building Companies

| Skill                  | When to Use                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
| `first-principles`     | Break any problem to fundamentals. Challenge assumptions. Find counterintuitive solutions. |
| `build-company`        | Hire exceptionally. Build culture. Design orgs that produce great products.          |
| `sequenced-strategy`   | Enter premium, fund mass market. Tesla's product ladder applied to any business.     |
| `going-all-in`         | When to bet everything. The logic and psychology of maximum commitment.               |
| `elon-decide`          | Make better decisions. Cut through noise. Prioritize ruthlessly. Own outcomes.       |

### Part IV — On Behalf of Humanity

| Skill                      | When to Use                                                                      |
|----------------------------|----------------------------------------------------------------------------------|
| `existential-risks`        | Map civilizational risks. Prioritize what actually matters long-term.            |
| `companies-as-philanthropy`| Building great companies as the highest form of contribution.                    |

### Bonus

| Skill          | When to Use                                                                              |
|----------------|------------------------------------------------------------------------------------------|
| `musk-methods` | Quick-reference to all 69 core Musk methods as a decision filter.                        |

---

## Example Prompts

Once installed, try prompts like:

- *"Use first principles to figure out why our costs are so high"*
- *"Run The Algorithm on our onboarding process"*
- *"Help me build a feedback culture on my team"*
- *"I have three options — help me decide like Elon would"*
- *"Is what I'm building actually useful at scale?"*
- *"Should I go all in on this or pull back?"*
- *"What's the sequenced strategy for our product?"*
- *"Give me a quick Musk methods check on this plan"*

---

## Source

Based on *The Book of Elon: A Guide to Purpose and Success* by Eric Jorgenson (2026).

---

Built by [Vibe AI Labs](https://github.com/vibeailabs-tech).
