## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> For starters...
```python
from textwrap import dedent
from dataclasses import dataclass

@dataclass
class Person:
    __instance = None

    name: str
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
            Thank you for stopping by!
            """
        )
        return brief_description

def main() -> None:
    me = Person(name="Lev",role="Web developer", language="Python")
    print(me)


if __name__ == "__main__":
    main()
    # Hi, my name is Lev — I'm a Web developer in Python.
    # Thank you for stopping by!
```
---
### 👨‍💻About me:
- ⚡ I like to write code
- 🔧 Creating my own projects
- 👍 Happy to have any real practice
- 🧐 Responsible, limited and very pedantic
- 😎 I am self-taught
- 📓 I follow the basic principles of programming: DRY, KISS, YAGNI, SOLID

---

### 💻 Technology Stack:
<div id="language-and-web-frameworks">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" title="Python"/> 
    <img src="https://img.shields.io/badge/Django-008000?style=for-the-badge&logo=django&logoColor=white" title="Django"/>
    <img src="https://img.shields.io/badge/DRF-7f2d2d?style=for-the-badge" title="Django REST Framework"/>
</div>
<div id="data-bases">
    <img src="https://img.shields.io/badge/postgresql-3f6bf0?style=for-the-badge&logo=postgresql&logoColor=white" title="PostreSQL"/>
    <img src="https://img.shields.io/badge/ELK-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" title="ELK">
    <img src="https://img.shields.io/badge/redis-black?style=for-the-badge&logo=redis&logoColor=f93325" title="Redis"/>
    <img src="https://img.shields.io/badge/Django ORM-008000?style=for-the-badge" title="Django ORM"/>
</div>
<div id="message-queue">
    <img src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=d1d1d1" title="Celery">
    <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" title="RabbitMQ">
</div>

---

### 📩 My contacts:
<div id="contacts">
  <a href="https://t.me/pythonist_lev">
    <img src="https://img.shields.io/badge/Telegram-white?style=for-the-badge&logo=telegram&logoColor=26A5E4" title="Telegram"/>
  </a>
  <a href="mailto:ionatan_it@proton.me">
    <img src="https://img.shields.io/badge/mail-white?style=for-the-badge&logo=Proton&logoColor=6c4afe" title="Proton"/>
  </a>
</div>
