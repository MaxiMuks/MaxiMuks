### Hi there 👋

![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)
<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90" />
const { checkReversal } = require('../../src/util');

const render = (reversal, color, height) => {    
    reversal = checkReversal(reversal);

    return `<path d="" fill="${color}" opacity="0.4" ${reversal}>
                <animate attributeName="d" dur="20s" repeatCount="indefinite" keyTimes="0;0.333;0.667;1" calcmod="spline" keySplines="0.2 0 0.2 1;0.2 0 0.2 1;0.2 0 0.2 1" begin="0s" values="M0 0L 0 ${height - 80}Q 213.5 ${height - 40} 427 ${height - 70}T 854 ${height - 45}L 854 0 Z;M0 0L 0 ${height - 55}Q 213.5 ${height - 40} 427 ${height - 60}T 854 ${height - 70}L 854 0 Z;M0 0L 0 ${height - 35}Q 213.5 ${height - 65} 427 ${height - 35}T 854 ${height - 70}L 854 0 Z;M0 0L 0 ${height - 80}Q 213.5 ${height - 40} 427 ${height - 70}T 854 ${height - 45}L 854 0 Z"></animate>
            </path>
            <path d="" fill="${color}" opacity="0.4" ${reversal}>
                <animate attributeName="d" dur="20s" repeatCount="indefinite" keyTimes="0;0.333;0.667;1" calcmod="spline" keySplines="0.2 0 0.2 1;0.2 0 0.2 1;0.2 0 0.2 1" begin="-10s" values="M0 0L 0 ${height - 65}Q 213.5 ${height - 20} 427 ${height - 50}T 854 ${height - 40}L 854 0 Z;M0 0L 0 ${height - 50}Q 213.5 ${height - 80} 427 ${height - 80}T 854 ${height - 60}L 854 0 Z;M0 0L 0 ${height - 55}Q 213.5 ${height - 75} 427 ${height - 50}T 854 ${height - 35}L 854 0 Z;M0 0L 0 ${height - 65}Q 213.5 ${height - 20} 427 ${height - 50}T 854 ${height - 40}L 854 0 Z"></animate>
            </path>`;
}

module.exports = { render };
<img src="https://img.shields.io/badge/리액트-61DAFB?style=flat&logo=React&logoColor=white"/>
<a href="클릭시 이동할 링크" target="_blank"><img src="https://img.shields.io/badge/문자-색코드?style=flat-square&logo=이미지 이름&logoColor=white"/></a>








































<!--
**MaxiMuks/MaxiMuks** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
