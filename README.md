<h1 align="center">
  Hi Guys <span style="display:inline-block; transform-origin: 70% 70%; animation: wave 2s infinite;">👋</span>
</h1>

<style>
@keyframes wave {
  0% { transform: rotate(0deg); }
  10% { transform: rotate(14deg); }
  20% { transform: rotate(-8deg); }
  30% { transform: rotate(14deg); }
  40% { transform: rotate(-4deg); }
  50% { transform: rotate(10deg); }
  60% { transform: rotate(0deg); }
  100% { transform: rotate(0deg); }
}
</style>

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
