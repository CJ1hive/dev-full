[[JS Start.]]
# 🧭 Obsidian Features Showcase
> A single note demonstrating the core and advanced features of **Obsidian.md**

---

## 🪶 Basic Markdown

**Bold** text, *italic* text, ***bold italic*** text, and `inline code`.

### Lists

- Bullet list item
- Nested list:
  - Second level
    - Third level

1. Numbered list item
2. Another one

---

## 📌 Headings

# H1
## H2
### H3
#### H4

---

## 🗂 Links

- **Internal link:** [[Another Note]]
- **External link:** [Obsidian Website](https://obsidian.md)
- **Block reference:** [[Another Note#^block-id]]
- **Header link:** [[Another Note#Section Title]]

---

## 🏷 Tags

#obsidian #markdown #productivity #example

---

## 💬 Callouts

> [!note] Note
> You can include info like this in callouts.

> [!info] Info
> Use this for additional context.

> [!tip] Tip
> This is helpful information.

> [!warning] Warning
> Be careful with something!

> [!quote] Quote
> “The quieter you become, the more you hear.”

---

## ✅ Tasks

- [ ] Completed task
- [ ] Incomplete task
- [ ] Task with a due date 📅 2025-10-22
- [ ] Task with a link to another note [[Task Management]]

---

## 🗓 Dataview Example (Requires Plugin)

```dataview
table status, due
from "Tasks"
where status != "done"
sort due asc
