## Developer Info API

```js
// Developer Info API Response
const developerInfo = {
  name: "Ehsan Jalili",
  title: "Back-end Developer",
  skills: {
    languages: ["JavaScript (Node.js)", "HTML", "CSS"],
    frameworks: ["Express.js"],
    databases: ["MongoDB", "PostgreSQL", "Redis"],
  },
  currentlyLearning: "Learning Nest.js",
  contact: {
    github: "https://github.com/ehsunjalili",
    email: "ehsunjalili@gmail.com"
  },
  hobbies: ["Coding", "Problem Solving", "Learning new technologies"]
};

console.log(JSON.stringify(developerInfo, null, 2));
