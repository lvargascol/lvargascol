<!-- ### Hi there 👋 -->



```javascript
const lvargascol = {
  name: 'Leonardo Vargas',
  languages: ['JavaScript'],
  technologies: {
    frontEnd: ['HTML', 'CSS', 'React', 'TailWind'],
    backEnd: ['NodeJS', 'Express'],
    databases: ['PostgreSQL', 'mySQL'],
    tools: ['Git', 'GitHub'],
  },
  contact: {
    linkedin: 'lvargascol',
    github: 'lvargascol',
    mailTo: 'lvargascol@gmail.com',
  },
  doing: (now, currentDate) => {
    if (now < currentDate) {
      return 'working as an electrical engineer on projects for the mining industry';
    } else if (now === currentDate) {
      return 'learning everything that is needed to become a full software engineer';
    } else if (now > currentDate) {
      return 'work on projects that will reshape our world';
    } else {
      return 'When am i?';
    }
  },
};

console.log(
  `Hi there! I'm ${lvargascol.name}. I've been ${lvargascol.doing(2021,2023)}
  , and I'm currently ${lvargascol.doing(2023,2023)}
  so that in the future, I can ${lvargascol.doing(2024, 2023)}.`);

```



<!--
**lvargascol/lvargascol** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
