## Developer Info API

```js
// Developer Info API Response
const developerInfo = {
  name: "Ehsan Jalili",
  title: "Back-end Developer",
  education: "B.Sc. in Computer Engineering (Software)",
  skills: {
    languages: ["JavaScript (Node.js)", "HTML", "CSS"],
    frameworks: ["Express.js", "Nest.js"],
    databases: ["MongoDB", "PostgreSQL"],
    tools: ["Git", "Docker", "Linux"],
  },
  currentlyLearning: "Advanced Node.js concepts",
  contact: {
    github: "https://github.com/ehsunjalili",
    email: "youremail@example.com"
  },
  hobbies: ["Coding", "Problem Solving", "Learning new technologies"]
};

console.log(JSON.stringify(developerInfo, null, 2));
