### who_am_i.sh
```bash
#!/bin/bash

$aboutme = "I’m Saurabh, a full-stack web developer from India, skilled in languages\n
  like C, Python, JavaScript, TypeScript, and PHP.\nI specialize in frameworks such\n
  as React, NextJS, Django, and FastAPI, and have hands-on experience with databases\n
  including MySQL, PostgreSQL, and MongoDB.\nI’m passionate about problem-solving,\n
  building scalable web applications, and constantly learning new technologies to\n
  stay at the forefront of development."

echo -e "$aboutme"
```
### about_me.json
```json
{
  "profession": "Full-Stack Web Developer",
  "location": "India",
  "traits": ["Problem Solver", "Team Player", "Quick Learner"]
}
```
### socials.yaml
```yaml
socials:
  Instagram: "https://instagram.com/this.is.saurabh.official"
  LinkedIn: "https://linkedin.com/in/saurabhyadav07"
  Twitter: "https://twitter.com/yadav_saurabh_7"
```
### tech_stack.py
```py
from fastapi import FastAPI

app = FastAPI()

tech_stack = {
    "languages": ["C", "Python", "PHP", "JavaScript", "HTML", "CSS", "Java", "TypeScript"],
    "frameworks_libraries": ["Bootstrap", "React", "TailwindCSS", "NextJS", "Django", "FastAPI", "REST Framework"],
    "databases": ["MySQL", "SQL", "mongoDB", "PostgresSQL", "SQLite3", "Firebase", "MongoDBAtlas"],
    "tools": ["Adobe Photoshop", "Figma", "Git", "VisualStudioCode", "PyCharm", "Docker", "Kubernetes"],
    "testing": ["Jest"],
    "version_control": ["Github"],
    "miscellaneous": ["WebSockets", "GraphQL"]
}

@app.get("/tech-stack")
async def get_tech_stack():
    return tech_stack
```

### contact.js
```js
const email = "sauraj.contact@gmail.com";
```
### os_i_use.tsx
```ts
const system: Record<string, Record<string | string[]>> = {
    "debian" : ["ubuntu", "kali", "parrot"],
    "windows" : ["windows 10", "windows 11"],
    "mac": "maxOSX",
}
```
