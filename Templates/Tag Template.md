---
type: MOC
topic: <% tp.file.title %>
aliases: []
---

# <% tp.file.title %> — Map of Content

A curated hub for all notes related to **<% tp.file.title %>**.
## 🧭 Purpose

Briefly describe what this topic represents.

- What is the concept?
    
- Why is it important?
    
- What kinds of notes should link here?
    

---

## 🔗 All Linked Permanent Notes (Auto-updating)

Notes that **link to this Map of Content** from the _Permanent Notes_ folder:

```dataview
LIST
FROM "Permanent Notes"
WHERE contains(file.outlinks, this.file.link) OR contains(file.outlinks, this.file.aliases)
SORT file.mtime DESC
```

---

## 🧩 Outgoing Links (Optional)


```dataview
LIST
FROM ""
WHERE contains(file.outlinks, this.file.link)

```

---

## 📌 Notes / Thoughts


---