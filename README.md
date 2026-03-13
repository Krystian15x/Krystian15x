<h1 align="center">Hey there 👋, I'm Krystian!</h1>
<p align="center">
    Interested in Linux, self-hosting and web technologies.
</p>

```py
class AboutMe:
    def __init__(self):
        self.username = "Krystian15x"
        self.pronouns = ["he", "him"]
        self.location = "Poland"
        self.status = "Looking for Work"
        self.age = 23
        self.hobbies = ["Homelab", "Linux", "SDR", "Astronomy", "Human neurobiology"]
        self.skills = {
            "frontend": ["HTML", "CSS", "JavaScript"],
            "backend": ["Python", "PHP", "REST APIs"],
            "databases": ["SQL", "MySQL"],
            "devops": ["Linux", "Bash", "Docker", "Docker Compose", "Proxmox"],
            "cms": ["WordPress"],
            "tools": ["Git", "GitHub", "VS Code"]
        }
        self.how_it_started = "I got into tech at a young age and started coding when I was around 12-13"

if __name__ == "__main__":
    me = AboutMe()
