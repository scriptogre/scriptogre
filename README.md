```python
from typing import Dict, List


class FullStackDeveloper:
    """Forgive me for this, but it was fun to do."""
    def __init__(self):
        # About
        self.name: str = "Tanul Christian"
        self.role: str = "Full-Stack Python Developer (Django)"
        self.email: str = "tanulchristian@gmail.com"
        self.years_of_experience: int = 5
        self.hard_skills: Dict[str, str] = {
            "Python": "Fairly advanced having worked with it for 5 years for web development, data science, and automation",
            "Django": "Immersed in Django for 10 daily hours over the last 2 years, working solo on a passionate project.",
            "JavaScript frameworks": "After trialing React and Vue.JS, favored HTMX and Hyperscript for superior Django integration.",
            "Docker": "Used Docker and Docker Compose for all my projects to ensure consistency across environments",
            "Git": "Used Git for all my projects and have a good understanding of the Git workflow",
            "Linux": "Deployed all my projects on Linux servers and have a good understanding of the Linux ecosystem",
        }
        self.soft_skills: Dict[str, str] = {
            "Communication": "I'm a naturally extroverted person and I enjoy communicating with others",
            "Self-Management": "I'm a self-motivated person and I enjoy working on my own although I'm also a good team player",
            "Problem-solving": "I enjoy solving problems and I'm good at it",
            "Adaptability": "I'm a quick learner and I'm able to adapt to new situations easily",
            "Work Ethic": "I'm willing to put in the hours to get the job done and I'm not afraid of hard work",
        }
        self.languages: List[str] = ["English", "Spanish (A2)", "Romanian"]
        
        # Education
        self.bachelors_degree = None  # I'm self-taught
        
        # Projects
        self.work_projects: Dict[str, str] = {
            "ERP Systems": "A Django-based ERP system for a Clinical Research Organization",
            "Home Assistant": "A custom Home Assistant implementation for a client with solar panels",
        }
        self.personal_projects: Dict[str, str] = {
                "Audio Transcription Tool": "An audio transcript summarization tool using OpenAI API and Whisper model",
                "Raspbery Pi Assistant": "A Raspberry Pi assistant powered by the GPT API and MicroPython",
                "Bible App": "A GPT-powered app designed to simplify interaction with the Bible",
        }

	
        # Interests
        self.topics_of_interest: Dict[str, str] = {
            "LLMs": "Large Language Models (LLMs) and Prompt Engineering",
            "GPT-4": "Productivity & workflow optimization using GPT-4 API & automation",
            "Nutrition": "Understanding the science behind healthy eating habits and optimizing for performance",
            "Fitness": "Exploring different fitness regimens for health, longevity, and performance",
            "Tech": "Staying on top of emerging trends and technologies, particularly in AI and Web Development",
            "Biology": "Delving into genetics, microbiome, and neuroscience to understand the human body and mind",
            # "Ultimate Frisbee": "Not that good yet, though",
        }
        self.inspired_by: Dict[str, str] = {
            "Elon Musk": "For his relentless pursuit of innovation and his ability to think big",
            "Andrew Huberman": "For his ability to explain complex topics in a simple manner",
            "Jordan Peterson": "For his ability to articulate his thoughts and his emphasis on personal responsibility",
            "Alex Hormozi": "For his good work ethic and his emphasis on giving to others and helping them grow",
            "Lex Fridman": "For his humility and his ability to ask the right questions",
        }

        # Volunteering
        self.event_participation: Dict[str, str] = {
            "EuroPython 2023": "Volunteering for the first time at a Python conference.",
        }
```