🚀 Real-World Software Pipeline Simulation using Python Abstraction
A hands-on simulation of how real-world software, data engineering, and ML teams collaborate.

Demonstrates clean architecture, version control, and CI/CD practices through a multi-role development pipeline.

Built with Python, GitHub workflows, and modular principles — ideal for learning team-based software development.

🎯 Project Objectives

Structure code for multi-developer collaboration

Apply abstraction to ensure scalable and clean code

Simulate versioning and GitHub-based CI/CD pipelines

Build a user-friendly command-line interface (CLI)

Learn how real tech teams manage and scale projects

🛠️ Project Workflow

👨‍💻 Senior Developer
Designs the abstract base class (Version1.py)

👩‍💻 Junior Developer
Implements logic by extending the abstract class (Version2.py)

📦 Main Runner
Runs the full pipeline via CLI (main_version2.py)

🔁 Versioned Development Flow 

V1 – Senior developer creates abstract structure

V2 – Junior developer implements logic

V3 – Senior developer adds new abstract methods

V4 – Junior developer implements new features

💡 Technologies and Concepts Used 

Python OOP using abstract base classes (abc)

Modular and maintainable code structure

Command-line interface with argparse

Git and GitHub for version control and collaboration

Object detection using YOLOv8

Clean interface that hides internal logic from the user

⚙️ How to Run This Project
bash
Copy
Edit
# Clone the repository
git clone https://git@github.com:sailajacoder/cicd.git


# Install dependencies
pip install -r requirements.txt

# Run the pipeline

python main_version2.py --image_path="sample.jpg" --model_path="yolov8n.pt"
Make sure Python is installed

Download the required model file (yolov8n.pt) and provide the correct path

Output will be saved in the outputs/ folder

📁 Folder Structure

bash
Copy
Edit
cicd/
├── main_version2.py       # CLI entry point

├── Version1.py            # Abstract class (V1)

├── Version2.py            # Logic implementation (V2)

├── requirements.txt       # Dependencies

├── README.md              # Documentation


🧠 Learning Outcomes
Understand the power of abstraction in scalable software projects

Learn how real-world teams manage modular, versioned codebases

Gain experience with GitHub workflows, version control, and CLI development

Build confidence working on projects that simulate actual tech industry practices
