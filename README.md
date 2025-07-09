<h1 align="center">
  Hi Guys <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

```python
# Welcome to my GitHub profile

class Developer:
    def __init__(self):
        self.name = "Shayan Hassanpour"
        self.role = "Junior Developer"
        self.skills = ["Python", "Git"]
        self.location = "Iran"

    def introduce(self):
        print(f"Hi, I'm {self.name} 👋")
        print(f"I'm a {self.role} based in {self.location}.")
        print(f"My skills include: {', '.join(self.skills)}")

me = Developer()
me.introduce()
