### who_am_i.sh
```bash
#! /bin/bash

aboutme="
I’m Saurabh, a full-stack web developer from India, skilled in languages
like C, Python, JavaScript, TypeScript, and PHP. I specialize in frameworks such
as React, NextJS, Django, and FastAPI, and have hands-on experience with databases
including MySQL, PostgreSQL, and MongoDB.I’m passionate about problem-solving,
building scalable web applications, and constantly learning new technologies to
stay at the forefront of development.
"
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
  X: "https://x.com/yadav_saurabh_7"
  Website: "https://saurabh-yadav.vercel.app/"
```
### skills_and_tech_stack.py
```py
from Typing import Dict, List
from fastapi import FastAPI

skills = FastAPI()

stack: Dict[str, List[str]] = {
    "languages": ["C", "Python", "PHP", "JavaScript", "HTML", "CSS", "Java", "TypeScript"],
    "frameworks_libraries": ["Bootstrap", "React", "TailwindCSS", "NextJS", "Django", "FastAPI", "REST Framework"],
    "databases": ["MySQL", "SQL", "mongoDB", "PostgresSQL", "SQLite3", "Firebase", "MongoDBAtlas"],
    "tools": ["Adobe Photoshop", "Figma", "Git", "VisualStudioCode", "PyCharm", "Docker", "Kubernetes"],
    "testing": ["Jest"],
    "version_control": ["Github"],
    "miscellaneous": ["WebSockets", "GraphQL"]
}

@skills.get("/skills-and-tech-stack")
async def get_skills_and_tech_stack():
    return stack
```
### contact.js
```js
const contacts = {
  email: "sauraj.contact@gmail.com",
};

console.log(contacts);
```
### os_i_use.tsx
```ts
const systems: Record<string, Record<string | string[]>> = {
    "debian" : ["ubuntu", "kali", "parrot"],
    "windows" : ["windows 10", "windows 11"],
    "mac": "maxOSX",
};

console.log(systems)
```
