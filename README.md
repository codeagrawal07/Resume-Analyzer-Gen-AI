# 🤖 AI Resume Analyzer using Generative AI (Gemini API)

This project uses Google’s **Gemini Pro LLM** to analyze a candidate's resume summary and extract meaningful insights — such as key skills, strengths, areas of improvement, suggested job roles, and a LinkedIn headline — using **Prompt Engineering** techniques like role prompting, format control, and chain-of-thought reasoning.

---

## 🚀 Features

- ✅ Extracts technical and soft skills from a free-form resume summary
- ✅ Identifies strengths and areas for improvement
- ✅ Suggests role-fit options (e.g., Data Scientist, ML Engineer)
- ✅ Generates a LinkedIn-ready headline
- ✅ Outputs structured data in JSON format for integration

---

## 🛠 Tech Stack

- 🧠 **Google Generative AI (Gemini Pro)**
- 🐍 **Python 3.x**
- 📦 `google-generativeai`
- 💻 Jupyter Notebook / VS Code

---

## 📸 Demo Output (JSON)

```json
{
  "skills": ["Python", "Machine Learning", "YOLOv8", "Decision Trees", "Git", "VS Code"],
  "strengths": "Hands-on project experience, good grasp of ML concepts, practical coding ability.",
  "improvement_areas": "Improve communication skills and deepen knowledge in model evaluation metrics.",
  "suggested_roles": ["Machine Learning Intern", "Computer Vision Developer", "Data Analyst"],
  "linkedin_headline": "Aspiring ML Engineer | Python Enthusiast | Computer Vision Projects"
}
