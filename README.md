<div align="center">
  
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=800&size=30&duration=1200&pause=148&center=true&vCenter=true&width=435&lines=I+am+Rayyan+Ashraf;Interested+in+Field+of%2C;Data+Science%2C;Artificial+Intelligence%2C;or+Machine+Learning+%3F;I'm+Eager+to+Connect+!)](https://git.io/typing-svg)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=etsryn&theme=dark&hide_border=true)](https://git.io/streak-stats)
  
  <br />
  
<pre style="text-align: left;">
```python
from functools import reduce
from itertools import cycle
from collections import deque

class RayyanMeta(type):
    def __new__(cls, name, bases, dct):
        dct['__all__'] = (
            "passions", "languages", "current_focus", "life_philosophy",
            "architecture", "learning", "challenge", "ambition"
        )
        return super().__new__(cls, name, bases, dct)

class Rayyan(metaclass=RayyanMeta):
    passions = tuple(map(str.upper, [
        "AI/ML", "Data Science", "Clean Code", 
        "Problem Solving", "Islamic NLP", "Innovation"
    ]))
    
    languages = {
        lang: len(lang) for lang in [
            "Python", "C++", "Java", "JavaScript", "SQL"
        ]
    }

    current_focus = (
        lambda: f"Crafting intelligent solutions at scale for real-world impact"
    )()

    life_philosophy = (
        lambda: reduce(lambda x, y: x + " | " + y, [
            "Write code for clarity", "Think like a minimalist", 
            "Code with empathy for future me"
        ])
    )()

    architecture = deque([
        "Modular Design", "REST APIs", "Hybrid NLP-CNN Architectures", "Cloud-Optimized Workflows"
    ])

    learning = frozenset([
        "Blockchain Consensus (PoW vs PoS)", 
        "Arabic (Najdi Dialect)", 
        "Advanced DL + Transformers", 
        "Google Cloud"
    ])

    challenge = cycle([
        "Building scalable, interpretable AI",
        "Creating systems that speak to the future"
    ])

    ambition = lambda: (
        f"M.Tech @ IIT Bombay | GATE 2026 Aspirant | "
        f"Tech Educator in the Making | Innovator for the next decade"
    )()
    
    @property
    def architectural_focus(self):
        return [*self.architecture, next(self.challenge)]

    def __str__(self):
        return f"Rayyan({', '.join(self.__dict__.keys())})"
</pre>

</div>

<img align="right" width="38%" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzM5bndzNjFnNDMxbGdid2E0ejIzejZkaWZ3ZjRpZWlseTJ0cWc5MCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" />

## 💫 About Me

I'm Rayyan Ashraf, a curious and passionate developer driven by a love for clean code, deep thinking, and elegant problem-solving. As a 3rd-year B.Tech CSE student, I'm constantly exploring the frontiers of AI, Machine Learning, Data Science, and Software Engineering — with a deep interest in building systems that are both intelligent and impactful.

I'm on a focused path toward mastering core CS concepts, preparing for GATE 2026, and aiming to pursue M.Tech at IIT Bombay. I believe in writing code that not only works but communicates, scales, and stands the test of time.

> Illuminate confusion with clarity, and chaos with clean logic.

<details>
<summary>⚡ More about me</summary>
<br />

- 📘 Currently preparing for **GATE 2026** with eyes on **IIT Bombay – Data Science & AI**
- 🔍 Always exploring the depths of **AI, NLP, and Machine Learning**
- 🧠 I believe in building intelligent systems with **clarity, impact, and clean code**
- 🌐 Passionate about curating **clean datasets** and creating **open-source resources**
- 💬 I love talking about **DSA, AI architectures, research ideas**, or anything tech!

> "Code is not just instructions to a machine — it's a conversation with the future." – Me

</details>

<br clear="right"/>

## 🌟 Featured Projects

<div align="center">
  <a href="https://github.com/etsryn/Linear-Regression">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=krikera&repo=python-shell-exp&theme=tokyonight&hide_border=true&icon_color=6A5ACD&title_color=9370DB&bg_color=0D1117&text_color=8A8D93" width="49%" />
  </a>
  <a href="https://github.com/etsryn/Specialized-Python">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=krikera&repo=FinViz-Dashboard&theme=tokyonight&hide_border=true&icon_color=6A5ACD&title_color=9370DB&bg_color=0D1117&text_color=8A8D93" width="49%" />
  </a>
</div>

<div align="center">
  <p>
    <a href="https://github.com/krikera/python-shell-exp/">
      <img src="https://img.shields.io/badge/Python%20Shell-333333?style=for-the-badge&logo=python&logoColor=white&labelColor=4B0082" alt="Python Shell"/>
    </a>
    <a href="https://github.com/krikera/FinViz-Dashboard/">
      <img src="https://img.shields.io/badge/FinViz%20Dashboard-4A90E2?style=for-the-badge&logo=streamlit&logoColor=white&labelColor=4B0082" alt="FinViz Dashboard"/>
    </a>
  </p>
</div>


## 🛠️ Tech Arsenal

<div align="center">
  <table border="none">
    <tr>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="65" height="65" />
        </a>
        <br>JavaScript
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="TypeScript" width="65" height="65" />
        </a>
        <br>TypeScript
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="65" height="65" />
        </a>
        <br>Python
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="C++" width="65" height="65" />
        </a>
        <br>C++
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="65" height="65" />
        </a>
        <br>React
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="AWS" width="65" height="65" />
        </a>
        <br>AWS
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="GitHub" width="65" height="65" />
        </a>
        <br>GitHub
      </td>
    </tr>
    <tr>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="Docker" width="65" height="65" />
        </a>
        <br>Docker
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="Nginx" width="65" height="65" />
        </a>
        <br>Nginx
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL" width="65" height="65" />
        </a>
        <br>MySQL
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://user-images.githubusercontent.com/25181517/117201156-9a724800-adec-11eb-9a9d-3cd0f67da4bc.png" alt="Java" width="65" height="65" />
        </a>
        <br>Java
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png" alt="Git" width="65" height="65" />
        </a>
        <br>Git
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png" alt="GitHub" width="65" height="65" />
        </a>
        <br>GitHub
      </td>
      <td align="center" width="96">
        <a href="#">
          <img src="https://user-images.githubusercontent.com/25181517/192107858-fe19f043-c502-4009-8c47-476fc89718ad.png" alt="REST" width="65" height="65" />
        </a>
        <br>REST
      </td>
    </tr>
  </table>
</div>

<details>
  <summary><b>🔠 Languages</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white&labelColor=4B0082" />
  </p>
</details>

<details>
  <summary><b>🌐 Frontend</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white&labelColor=4B0082" />
  </p>
</details>

<details>
  <summary><b>⚙️ Backend</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=4B0082" />
  </p>
</details>

<details>
  <summary><b>🗄️ Databases</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&labelColor=4B0082" />
  </p>
</details>

<details>
  <summary><b>☁️ Cloud & DevOps</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=4B0082" />
  </p>
</details>

<details>
  <summary><b>🧪 Data Science</b></summary>
  <br />
  <p align="center">
    <img src="https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white&labelColor=4B0082" />
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black&labelColor=4B0082" />
  </p>
</details>

## 📊 GitHub Metrics

<div align="center">
  <a href="https://github.com/krikera">
    <img alt="3D Contribution Chart" src="https://raw.githubusercontent.com/krikera/krikera/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%"/>
  </a>
</div>
 
<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=krikera&show_icons=true&theme=transparent&title_color=9370DB&text_color=A8A8A8&icon_color=6A5ACD&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=krikera&layout=compact&theme=transparent&title_color=9370DB&text_color=A8A8A8&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

<div align="center">
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=krikera&theme=discord&no-frame=true&column=7" alt="Trophy" />
</div>

## 🌎 Visitor Map

<div align="center">
  <img src="https://hits.sh/github.com/krikera.svg?view=today-total&style=for-the-badge&label=visitors&color=6A5ACD" alt="Visitor Map" />
</div>

## 🔮 Weekly Development Breakdown

<div align="center">
  
```text
JavaScript   ████████████▓░░░░  40.25% ⬆️ 
TypeScript   ██████████▓░░░░░░  30.12% ⬆️
Python       ██████▓░░░░░░░░░░  15.45% ⬇️
HTML/CSS     ████▓░░░░░░░░░░░░  10.38% ⬌
Other        █▓░░░░░░░░░░░░░░░   3.80% ⬇️
```
  
</div>

## 📫 Let's Connect

<div align="center">
  <a href="https://www.linkedin.com/in/krishnaketanrai" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=4B0082" alt="LinkedIn"/>
  </a>
  <a href="mailto:prafulrai522@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=4B0082" alt="Gmail"/>
  </a>
  <a href="https://krikera.hashnode.dev/" target="_blank">
    <img src="https://img.shields.io/badge/Blog-2962FF?style=for-the-badge&logo=hashnode&logoColor=white&labelColor=4B0082" alt="Hashnode"/>
  </a>
</div>

<div align="center">
  <br/>
  <a href="https://www.buymeacoffee.com/krikera" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black&labelColor=6A5ACD" alt="Buy Me A Coffee" />
  </a>
</div>

<!-- GitHub Activity Graph -->
<br/>
<div align="center">
  <a href="https://github.com/krikera">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=krikera&bg_color=0D1117&color=6A5ACD&line=9370DB&point=A020F0&area=true&hide_border=true" width="100%"/>
  </a>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&animation=twinkling&fontAlignY=35&text=Thanks%20for%20visiting!&fontSize=30&fontColor=FFFFFF&customColorList=24" width="100%" />
</div>



<div align="center">
  <a href="https://komarev.com/ghpvc/?username=krikera">
    <img src="https://komarev.com/ghpvc/?username=krikera&color=blueviolet&style=for-the-badge" alt="Profile Views" />
  </a>
</div>
