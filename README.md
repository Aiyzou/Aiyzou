class Riza:
    def __init__(self):
        self.name = "Riza"
        self.age = 14
        self.interests = ["coding", "gaming", "learning", "football"]
        self.skills = ["Python", "JavaScript", "C++", "C#"]

    def __str__(self):
        return f"👋 Hey, I'm {self.name}!\n\n I'm {self.age} years old and passionate about {', '.join(self.interests)}.\n\n💻 My skills include {', '.join(self.skills)}.\n\nLet's connect and build something amazing together!"

riza = Riza()

print(riza)