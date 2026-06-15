class Celestian:
    def __init__(self):
        self.name            = "Celestian A"
        self.location        = "Chennai, Tamil Nadu, India 🇮🇳"
        self.degree          = "B.Tech – Artificial Intelligence & Data Science (2026)"
        self.college         = "Nehru Institute of Engineering and Technology (Anna University)"
        self.cgpa            = "82%"

        self.stack = [
            "Python", "SQL", "TensorFlow", "PyTorch", "LangChain",
            "OpenCV", "Scikit-learn", "Pandas", "NumPy", "FastAPI",
            "Flask", "Docker", "AWS", "Power BI"
        ]

        self.currently_learning = [
            "Advanced RAG Pipelines",
            "LLM Fine-Tuning",
            "dbt + Modern Data Stack",
            "Meta Data Analyst Certification (in progress)"
        ]

        self.fun_fact = "I built a real-time deepfake detector that runs at 150–300 ms latency 🎭"

    def motto(self):
        return "Build AI that matters. Analyse data that speaks. Ship systems that scale. 🚀"

me = Celestian()
print(me.motto())
