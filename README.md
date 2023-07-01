```python
class Person:
    _inctance = None

    def __new__(cls):
        if cls._inctance is None:
            cls._instance = super().__new__(cls)
        return cls._instance

    def __init__(self):
        self.name = "Lev"
        self.age = 17
        self.role = "Web developer"
        self.language = 'Python'
        self.language_spoken = ["ru_RU", "en_US"]

    @property
    def greetings(self):
        return f'''
                Hi, my name is {self.name} — I'm a {self.role} in {self.language}.
                I'm {self.age} years old and have been programming for over 1 year.
                Thank you for stopping by!
                '''


me = Person()
print(me.greetings)
```
### 👨‍💻About me:
- ⚡ I like to write code
- 🔧 Creating my own projects
- 👍 Happy to have any real practice
- 👨‍💻 Responsible and quite pedantic
- 😎 I am self-taught

### 💻 Languages and tools:
<div id="technologies">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" title="Python"/> 
  <img src="https://img.shields.io/badge/Django-008000?style=for-the-badge&logo=django&logoColor=white" title="Django"/><br>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" title="HTML"/> 
  <img src="https://img.shields.io/badge/CSS-2d6bdc?style=for-the-badge&logo=CSS3&logoColor=white" title="CSS"/>  
  <img src="https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E" title="JS"/> 
  <img src="https://img.shields.io/badge/jquery-2f8ccc?style=for-the-badge&logo=jquery&logoColor=white" title="Jquery"/><br>
  <img src="https://img.shields.io/badge/postgresql-3f6bf0?style=for-the-badge&logo=postgresql&logoColor=white" title="PostreSQL"/> 
  <img src="https://img.shields.io/badge/redis-black?style=for-the-badge&logo=redis&logoColor=f93325" title="Redis"/><br>
  <img src="https://img.shields.io/badge/Git-black?style=for-the-badge&logo=git&logoColor=F05032" title="Git"/> 
  <img src="https://img.shields.io/badge/Github-d1d1d1?style=for-the-badge&logo=github&logoColor=black" title="Github"/>
</div>

### ✍️ IDE:
<div id="technologies">
  <img src="https://img.shields.io/badge/vs code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" title="Visual Studio code"/> 
  <img src="https://img.shields.io/badge/pycharm-000000?style=for-the-badge&logo=pycharm&logoColor=white" title="Pycharm"/>
</div>

### 📩 My contacts:
<div id="contacts">
  <a href="https://t.me/ya_gay_ksta">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" title="Telegram"/>
  </a>
  <a href="mailto:liwanonika@gmail.com">
    <img src="https://img.shields.io/badge/gmail-d1d1d1?style=for-the-badge&logo=gmail&logoColor=EA4335" title="Gmail"/>
  </a>
  <a href="https://discord.com/users/712922114600075295">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" title="Discord"/>
  </a>
</div>

### 🗂️ Highlight Projects

<a href="https://github.com/sodiNICH/Shop">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=sodiNICH&repo=Shop&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="DA-RNN" />
</a>

### ⚙️ GitHub statistics:
<table>
  <tr>
    <td>
      <img align="left" src="http://github-readme-streak-stats.herokuapp.com?user=sodiNICH&theme=dark&background=000000" alt="webDev's Github stats" />
    </td>
    <td>
      <img height="195px" align="right" alt="webDev's Github Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=sodiNICH&layout=compact&theme=vision-friendly-dark" />
    </td>
  </tr>
</table>

<!-- [![sodinich github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=sodinich&theme=high-contrast)](https://github.com/sodinich/github-readme-activity-graph) -->
