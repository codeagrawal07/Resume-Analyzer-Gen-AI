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

```
{
  "skills": ["Python", "Machine Learning", "YOLOv8", "Decision Trees", "Git", "VS Code"],
  "strengths": "Hands-on project experience, good grasp of ML concepts, practical coding ability.",
  "improvement_areas": "Improve communication skills and deepen knowledge in model evaluation metrics.",
  "suggested_roles": ["Machine Learning Intern", "Computer Vision Developer", "Data Analyst"],
  "linkedin_headline": "Aspiring ML Engineer | Python Enthusiast | Computer Vision Projects"
}
```
🧪 How to Use
1. Clone the Repo

```   
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
```
2. Install Dependencies
```
pip install google-generativeai
```
3. Set Up Gemini API
   -Get your API key from Google AI Studio
   -Add your key in the code:
```
genai.configure(api_key="your_api_key_here")
```
4. Run the Notebook
   -Open resume_analyzer.ipynb in VS Code or Jupyter and run all cells.
---
## 🧠 Prompt Engineering Techniques Used

| Technique           | Purpose                                 |
| ------------------- | --------------------------------------- |
| Role Prompting      | Treat Gemini as a senior HR expert      |
| Format Prompting    | Forces output in a parsable JSON format |
| Chain-of-Thought    | Helps the model reason before answering |
| Temperature Control | Keeps output creative yet consistent    |

## 📌 Future Improvements
  - 📄 Upload and parse actual resume PDFs
  - 🌐 Add a Streamlit UI to make it web-based
  - 📊 Visualize skill-matching scores with job roles
  - 🧑‍🏫 Suggest upskilling courses using LLM
## 🙋‍♂️ Author
- Abhishek Agarwal
- 💼 Beginner in Generative AI & Prompt Engineering
- 🌐 LinkedIn https://www.linkedin.com/in/abhishek07122002/
  
