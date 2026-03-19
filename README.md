# Courses: Agentic AI [ Deep Learning.ai ]

[Course](https://learn.deeplearning.ai/courses/agentic-ai)

Author: Andrew

## Syllabus
1. Module 1: Introduction to Agentic Workflows
2. Module 2: Reflection Design Pattern
3. Module 3: Tool Use
4. Module 4: Practical Tips for Buidling Agentic AI
5. Module 5: Patterns for Highly Autonomous Agents

## Module 1: Introduction to Agentic Workflows
Following topics are covered
1. Breakdown task to steps
2. Building blocks of Agent (Tools, RAG, Memory, Database, Multimodal)
- Models
- Tools
3. Design Patterns
- Reflection (Worker-Evaluator/Critic)
- Tool Use
- Multi-agent collaboration
4. Evals
- Function: Check expected relevent keywords. Check if any unexpected keywords
- LLM Model: Give score/rating for the response based on its achieved objective (less popular)

## Lab 1
[Lab Setup](https://learn.deeplearning.ai/courses/agentic-ai/lesson/bvuwky83/optional%3A-set-up-your-local-environment-for-the-ungraded-labs)
1. virtual environment
```bash
python -m venv venv
source venv/bin/activate # On windows > venv/Scripts/activate
```
2. requirements [requirements.txt]
```
# === Agent + LLM Tools ===
aisuite==0.1.11
anthropic
docstring-parser
markdown
mistralai
openai
qrcode
tavily-python>=0.7.12
textstat
vertexai

# === Web Framework + API ===
fastapi
pydantic
pydantic[email]
python-dotenv
python-multipart
requests
sqlalchemy
uvicorn

# === Notebook Experience ===
ipywidgets
jupyter_server
nbclassic
notebook

# === Data Analysis / Display (Optional Enhancements) ===
duckdb
matplotlib
pandas
seaborn
tabulate
tinydb

# === Machine Learning / NLP (Optional Enhancements) ===
jinja2
psycopg2-binary
scikit-learn
Wikipedia
```
3. install requirements
```bash
pip install -r requirements.txt
```
4. **[Optional]** Link Lab environment to IDE or Jupyter Notebook
```bash
python -m ipykernel install --user --name=venv
```

##  Module 2: Reflection Design Pattern
