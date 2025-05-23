# 🍒 Cherrypicked_cursor_rules

A curated set of templates and rules for using Cursor AI effectively.  
We **cherrypicked** the best ideas from [awesome-cursorrules](https://github.com/anysphere/awesome-cursorrules) and added our own practices based on real-world usage at Cherrypick.

Use this repo as a foundation to set up rule systems tailored to your project, team, or personal workflow.

---

## 📁 Rules Structure

All rules are located in the `rules/` directory, organized by purpose:

- `📁 generic` — universal rules that fit any tech stack  
- `📁 must-have` — essential rules shared across all company projects  
- `📁 optional` — nice-to-have rules you can apply as needed  
- `📁 specific` — tech stack-specific rule examples  
- `📁 project-rules` — samples of custom rules scoped to individual projects  
- `📁 user-rules` — personal rules that apply globally to your Cursor environment  

---

## ✍️ Prompt Templates

The `prompt-templates/` directory includes ready-to-use prompts for interacting with Cursor:

- `📁 rules` — prompts to help generate, modify, and apply rules  
- `📁 documentation` — prompts for creating technical documentation  
- `📁 other` — misc prompts for improving your workflow  

**How to use:**

1. Copy a prompt  
2. Replace placeholders like `[your tech stack]` with real data  
3. Tweak as needed — they’re just starting points  

---

## ⚡ Quick Start

1. Copy `generic/must-have` rules into your project’s `.cursor/rules` directory  
2. Add anything useful from `generic/optional` and `specific`  
3. Customize the rules:  
   - `must-have` rules can be edited, but their core principles should be preserved  
   - `optional` and `specific` rules can be changed freely  
4. Ask Cursor to adapt the rules for your project  
5. Use `project-rules` as inspiration  
6. Set up personal rules via `user-rules` (found in Cursor → Settings → Rules → User rules)

---

## 💬 Prompt Examples

**→ Understanding rules**  
Read everything in `.cursor/rules`, summarize each rule in your own words, and confirm you'll follow them.

### Adapting rules for a project
Update rules in `.cursor/rules/{rule}` for our project: [project description].  
Tech stack: [stack]. Team: [team].  
Keep the spirit of must-have rules.

### Writing custom project rules
- Tech stack: `[your stack]`  
- Architecture: `[how the app is structured]`  
- Problems: `[what issues you’re solving]`  
- Code values: `[clarity, DRY, testability, etc.]`  
- Task style: `[how you approach problems]`

### Writing personal rules
- I prefer `[your coding style]`  
- I use `[frameworks/libraries]`  
- Code must be `[readable, tested, fast, etc.]`  
- I often struggle with `[X]`  
- Never do `[bad practices]`

## 📘 Writing Great READMEs
Use the included template to create clean, professional README files with:
- Clear project summary  
- Problem solved  
- Features  
- Stack  
- Install steps  
- Usage examples  
- Folder structure  
- Config info  
- Contributing  
- License  
- Credits  

## 🧠 Tips for Effective Rule Management
- Keep rules short and meaningful (ideally <100 lines)  
- Avoid contradictions  
- Use `Rule type: Always` only for critical rules  
- Ask Cursor to review and summarize rules before you begin  
- If rules are ignored, simplify or reduce them

**Found a better way to write rules?**  
Open a PR — we’d love to learn from it ❤️
