## :wave: Welcome to my GitHub profile! :pushpin:

```python
class Kudamii:
    def __init__(self) -> None:
        self.name: str = "Nguyen Anh Duc"
        self.alias: str = "Kudamii"
        self.introduce()

    def introduce(self) -> None:
        self._about: str = f"""
        Hi, I'm {self.name} (aka {self.alias}).

        💡 Passionate about Python, Algorithms, and exploring mysteries.  
        ⚡ Skilled in solving complex problems & building creative solutions.  
        🚀 Always curious about the unknown!  
        """

        self._tech: list[str] = [
            "🐍 Python",
            "☕ Java",
            "🌐 JavaScript",
            "🐹 GoLang"
        ]

        self._contact: dict[str, str] = {
            "📧 Email": "ducna1462@gmail.com",
            "📱 Phone": "+1 385 560 2124",
            "📸 Instagram": "https://www.instagram.com/_.kudamine._/"
        }

    def __repr__(self) -> str:
        return f"<Anh Duc alias={self.alias} stack={', '.join(self._tech)}>"

    def __call__(self) -> str:
        return self._about
