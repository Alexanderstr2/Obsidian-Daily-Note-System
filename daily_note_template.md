---
created: <% tp.file.creation_date() %>
---
tags:: [[+Daily Notes]]

# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').subtract(1, 'd').format('YYYY-MM-DD-dddd') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').add(1, 'd').format('YYYY-MM-DD-dddd') %>|Tomorrow]] >>

---
### 📅 Daily Questions / Reflection

#### Rate the following (1/10)
**Mood**:: 
**Stress Level**:: 
**Creative Output and Ideation**:: 
**Health**:: 
**Explain**:: 

##### ❤️ One thing I am grateful for:
- 

##### 🌜 Last night, after school, I...
- 

##### 🙌 One thing I've excited about right now is...
- 

##### 🚀 One+ thing I plan to accomplish today is...
- [ ] 

##### 👎 One thing I'm struggling with today is...
- 

---
# 📝  Notes / Rambles / Ideas
- <% tp.file.cursor() %>


---
# 🏃Running Journal

**Activity_type**:: 
**Workout**:: 
**Distance**:: 
**Time**:: 
**Pace**:: 
**HR**:: 
**RPE**:: 
**Comments**:: 

---
# 📆 Calendar / What I did Today (Screenshot for now) 



**What I did**
- 
---
### Notes created today
```dataview
List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc
```

### Notes last touched today
```dataview
List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
```

### Clippings From Today
```dataview
List FROM "Clippings" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
```

