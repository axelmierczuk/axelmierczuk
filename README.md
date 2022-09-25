<center> <h1>Hey, I'm Axel 🤘</h1> </center>

```python
#!/usr/bin/env python3

class AboutMe:
    def __init__(self):
        self.name = "Axel Mierczuk"
        self.occupation = "Cyber Threat Hunter @ RBC"
        self.education = "MS Cyber Security @ NYU"
        self.interets = {
            "Security": [
                "Offensive Security",
                "Machine Learning Research",
                "Vulnerability Research"
            ],
            "Programming": [
                "Python",
                "Java",
                "TypeScript",
                "JavaScript",
                "Node.js",
                "React.js",
                "SQL",
                "Go",
                "Rust"
            ]
        }
    
    def say_hello(self, name: str):
        print(f"Hello, {name}!")

if __name__ == "__main__":
    axel_mierczuk = AboutMe()
    axel_mierczuk.say_hello("world")
```

## Current Project

### _Fentanyl_

- IDAPython plugin
- Reverse engineering
- Malware analysis
