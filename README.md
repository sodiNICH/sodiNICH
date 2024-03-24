## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> For starters...
```python
from textwrap import dedent
from dataclasses import dataclass

@dataclass
class Person:
    __instance = None

    name: str
    age: int
    role: str
    language: str

    def __new__(cls, *args, **kwargs):
        if cls.__instance is None:
            cls.__instance = super().__new__(cls)
        return cls.__instance

    def __str__(self) -> str:
        brief_description = dedent(
            f"""
            Hi, my name is {self.name} — I'm a {self.role} in {self.language}.
            I'm {self.age} years old and have been programming for over 1 year.
            Thank you for stopping by!
            """
        )
        return brief_description

def main() -> None:
    me = Person(name="Lev", age=17, role="Web developer", language="Python")
    print(me)


if __name__ == "__main__":
    main()
    # Hi, my name is Lev — I'm a Web developer in Python.
    # I'm 17 years old and have been programming for over 1 year.
    # Thank you for stopping by!
```
---
### 👨‍💻About me:
- ⚡ I like to write code
- 🔧 Creating my own projects
- 👍 Happy to have any real practice
- 🧐 Responsible, limited and very pedantic
- 😎 I am self-taught

---

### 💻 Technology Stack:
- #### Language and web frameworks
<div id="language-and-web-frameworks">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" title="Python"/> 
    <img src="https://img.shields.io/badge/Django-008000?style=for-the-badge&logo=django&logoColor=white" title="Django"/>
    <img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white" title="FastAPI"/><br>
    <img src="https://img.shields.io/badge/pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" title="Pydantic"/>
</div>

- #### Data bases / ORM
<div id="data-bases">
    <img src="https://img.shields.io/badge/postgresql-3f6bf0?style=for-the-badge&logo=postgresql&logoColor=white" title="PostreSQL"/>
    <img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=d1d1d1" title="MongoDB">
    <img src="https://img.shields.io/badge/redis-black?style=for-the-badge&logo=redis&logoColor=f93325" title="Redis"/><br>
    <img src="https://img.shields.io/badge/sqlalchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" title="PostreSQL"/>
</div>

<!-- - #### File storage
<div id="file-storage">
    <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" title="MinIO">
</div> -->

<!-- - #### Basic authorization method
<div id="auth">
    <img src="https://img.shields.io/badge/JSON Web tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=d1d1d1" title="JSON Web tokens"><br>
</div> -->
- #### Files storage
<div id="files-storage">
    <img src="https://img.shields.io/badge/minio-C72E49?style=for-the-badge&logo=minio&logoColor=d1d1d1" title="MinIO">
    <!-- <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" title="Amazon S3"> -->
</div>

- #### Message queue
<div id="message-queue">
    <img src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=d1d1d1" title="Celery">
    <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" title="RabbitMQ">
    <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" title="ApacheKafka">
</div>

<!-- - #### ELK stack
<div id="elk">
    <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" title="Elasticsearch">
    <img src="https://img.shields.io/badge/logstash-005571?style=for-the-badge&logo=logstash&logoColor=white" title="Logstash">
    <img src="https://img.shields.io/badge/kibana-005571?style=for-the-badge&logo=kibana&logoColor=white" title="Kibana">
    <img src="https://img.shields.io/badge/beats-005571?style=for-the-badge&logo=beats&logoColor=white" title="Beats"><br>
</div>

- #### Metric
<div id="metric">
    <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" title="Prometheus">
    <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" title="Grafana">
</div> -->

- #### Git
<div id="git">
    <img src="https://img.shields.io/badge/Git-black?style=for-the-badge&logo=git&logoColor=F05032" title="Git"/>
    <img src="https://img.shields.io/badge/Github-d1d1d1?style=for-the-badge&logo=github&logoColor=black" title="Github"/>
    <img src="https://img.shields.io/badge/Gitlab-d1d1d1?style=for-the-badge&logo=gitlab&logoColor=FC6D26" title="Gitlab"/>
</div>

- #### Deployment technologies
<div id="devops-technologies">
    <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" title="NGinx"/>
    <img src="https://img.shields.io/badge/gunicorn-d1d1d1?style=for-the-badge&logo=gunicorn&logoColor=499848" title="Gunicorn"><br>
    <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=d1d1d1" title="Docker">
    <img src="https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=d1d1d1" title="Kubernetes">
</div>

- #### Front-end technologies (basic)
<div id="frontend-technologies">
    <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" title="HTML"/> 
    <img src="https://img.shields.io/badge/CSS-2d6bdc?style=for-the-badge&logo=CSS3&logoColor=white" title="CSS"/>
    <img src="https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E" title="JS"/><br>
    <img src="https://img.shields.io/badge/jquery-2f8ccc?style=for-the-badge&logo=jquery&logoColor=white" title="Jquery"/>
    <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white" title="Bootstrap"/>
</div>

---

### OS and terminal
<div id="os-and-terminal">
    <img src="https://img.shields.io/badge/windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" title="Windows">
    <img src="https://img.shields.io/badge/linux-d1d1d1?style=for-the-badge&logo=linux&logoColor=black" title="Linux">
    <img src="https://img.shields.io/badge/ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" title="Ubuntu"><br>
    <img src="https://img.shields.io/badge/windows terminal-black?style=for-the-badge&logo=windowsterminal&logoColor=white" title="Windows terminal">
    <img src="https://img.shields.io/badge/gnome terminal-241F31?style=for-the-badge&logo=gnometerminal&logoColor=white" title="Windows terminal">
</div>

### ✍️ IDE:
<div id="ide">
  <img src="https://img.shields.io/badge/vs code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" title="Visual Studio code"/> 
  <img src="https://img.shields.io/badge/pycharm-000000?style=for-the-badge&logo=pycharm&logoColor=white" title="Pycharm"/>
</div>

---

### 📩 My contacts:
<div id="contacts">
  <a href="https://t.me/ya_kilka_ksta">
    <img src="https://img.shields.io/badge/Telegram-white?style=for-the-badge&logo=telegram&logoColor=26A5E4" title="Telegram"/>
  </a>
  <a href="mailto:liwanonika@gmail.com">
    <img src="https://img.shields.io/badge/gmail-white?style=for-the-badge&logo=gmail&logoColor=EA4335" title="Gmail"/>
  </a>
  <a href="https://discord.com/users/712922114600075295">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" title="Discord"/>
  </a>
</div>

---

### 🗂️ Highlight Projects
<a href="https://github.com/sodiNICH/Bulletin_boards">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=sodiNICH&repo=Bulletin_boards&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="DA-RNN" />
</a>

---

### ⚙️ GitHub statistics:
<table>
  <tr>
    <!-- <td>
      <img align="left" src="http://github-readme-streak-stats.herokuapp.com?user=sodiNICH&theme=dark&background=000000" alt="webDev's Github stats" />
    </td> -->
    <td>
      <img height="195px" align="right" alt="webDev's Github Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=sodiNICH&layout=compact&theme=vision-friendly-dark" />
    </td>
  </tr>
</table>

<!-- [![sodinich github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=sodinich&theme=high-contrast)](https://github.com/sodinich/github-readme-activity-graph) -->
