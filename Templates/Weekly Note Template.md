# 🗓️ Week <% tp.date.now("YYYY [W]WW") %> (Starting <% tp.date.weekday("YYYY-MM-DD",0) %>)


## 🔄 Weekly Review

- ✅ What did I accomplish this week?
- ❌ What could have gone better?
- 🎯 What are my top priorities for next week?

---

## 🧠 Weekly Focus

- [ ] Focus Area 1
- [ ] Focus Area 2
- [ ] Personal Development Goal

---
## 📆 Daily Notes

```dataview
list
from ""
where contains(file.path,"/Daily/")
	and(
		file.ctime >= date(now) - dur(date(now).weekday + " days")
	   or file.mtime >= date(now) - dur(date(now).weekday + " days")
	)
sort file.mtime desc
```
