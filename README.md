### who_am_i.sh
```bash
printf "Hello, Devs! I'm Saurabh, a passionate full-stack web developer from India 🌏.\n"
```
### about_me.json
```json
{
  "profession": "Full-Stack Web Developer",
  "location": "India",
  "traits": ["Problem Solver", "Team Player", "Quick Learner"]
}
```
### socials.py
```py
from typing import Dict

socials: Dict[str, str] = {
    "Instagram": "https://instagram.com/this.is.saurabh.official",
    "LinkedIn": "https://linkedin.com/in/saurabhyadav07",
    "Twitter": "https://twitter.com/yadav_saurabh_7"
}
```
### tech_stack.yaml
```yaml
techStack:
  languages: [C, Python, PHP, JavaScript, HTML, CSS, Java, TypeScript]
  frameworksLibraries: [Bootstrap, React, TailwindCSS, NextJS, Django, FastAPI, REST Framework]
  databases: [MySQL, SQL, mongoDB, PostgresSQL, SQLlite3, firebase, MongoDBAtlas]
  tools: [Adobe Photoshop, Figma, Git, VisualStudioCode, PyCharm, Docker, Kubernetes]
  testing: [Jest]
  versionControl: [Github]
  mscellaneous: [WebSockets, GraphQL]
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
