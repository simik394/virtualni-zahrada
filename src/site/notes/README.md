---
{"dg-publish":true,"permalink":"/README/","tags":["gardenEntry"],"created":"2025-07-25T02:06:54.124+02:00","updated":"2025-07-25T03:03:29.368+02:00"}
---

# Digital Obsidian Garden
This is the template to be used together with the [Digital Garden Obsidian Plugin](https://github.com/oleeskild/Obsidian-Digital-Garden). 
See the README in the plugin repo for information on how to set it up.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/oleeskild/digitalgarden)

---
## Docs
Docs are available at [dg-docs.ole.dev](https://dg-docs.ole.dev/)
- [ ] if p
- [x] gg
- [ ] g

{ .block-language-dataview}


```dataview
CALENDAR file.day
FLATTEN all(map(file.tasks, (x) => x.completed)) AS "allCompleted"
WHERE !allCompleted
``