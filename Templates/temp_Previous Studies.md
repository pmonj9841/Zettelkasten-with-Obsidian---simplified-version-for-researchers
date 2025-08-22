---
created: 2025-07-14T12:26
updated: 2025-08-22T11:36
---
```dataview
table without id 
	file.link as Name, 
	authors,
	year,
	category,
	purpose,
	methodology,
	result,
	gap
FROM "2_Literature Notes"
WHERE contains(file.tags, "project/")
SORT year desc, category asc
```

