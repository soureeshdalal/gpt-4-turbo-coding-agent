# 🚀 O3-Mini Coding Assistant

A powerful AI-driven coding assistant that utilizes **GPT-4 Turbo**, **Gemini**, and **E2B sandbox environments** to generate and execute optimized Python solutions for coding problems. The assistant efficiently handles **code generation, execution, and debugging** within a secure sandbox.

---

## 🛠️ Features

- **🧠 GPT-4 Turbo Integration**: Generates optimal Python solutions for coding problems.
- **👀 Gemini Vision Model**: Extracts text-based coding problems from images.
- **🔒 E2B Sandbox Execution**: Securely runs Python code, handles errors, and formats results.
- **📜 Dynamic Programming Assistance**: Solves problems like **Knapsack**, **Sorting**, and **Graphs** with efficiency.
- **📌 Clean & Structured Code**: Includes type hints, documentation, and edge-case handling.

---

## 📂 Project Structure

📦 O3-Mini-Coding-Agent ┣ 📜 app.py # Streamlit-based chatbot interface ┣ 📜 requirements.txt # List of dependencies ┣ 📜 README.md # Project documentation ┗ 📂 assets/ # Image assets for documentation
---

## 🔧 Installation

1️⃣ Clone the repository:
```bash
git clone https://github.com/yourusername/O3-Mini-Coding-Agent.git
cd O3-Mini-Coding-Agent
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the chatbot:

bash
Copy
Edit
streamlit run app.py

📌 Usage
Enter API Keys:
OpenAI API Key (for GPT-4 Turbo)
Gemini API Key (for vision-based problem extraction)
E2B API Key (for secure code execution)
Provide Input:
Upload an image containing a coding problem or enter a text-based problem.
Get Optimized Code:
The AI will generate an optimized Python solution with explanations.
Execute Code in Sandbox:
Securely runs code, handles errors, and formats outputs.


📡 Model Architecture
Text-based Code Generation: Uses GPT-4 Turbo to generate optimal Python solutions.
Image-based Extraction: Gemini processes images, extracts coding problems, and converts them into structured prompts.
Secure Execution: Runs code in an isolated E2B sandbox environment, preventing unwanted side effects.

🔥 Example Run
python
Copy
Edit
def knapsack(values, weights, capacity):
    """
    Solve the 0/1 Knapsack problem using dynamic programming.
    """
    n = len(values)
    dp = [0] * (capacity + 1)

    for i in range(n):
        for w in range(capacity, weights[i] - 1, -1):
            dp[w] = max(dp[w], dp[w - weights[i]] + values[i])

    return dp[capacity]

# Example usage:
values = [60, 100, 120]
weights = [10, 20, 30]
capacity = 50
print(knapsack(values, weights, capacity))  # Output: 220
📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Feel free to fork this repo, submit PRs, or raise issues for feature requests! 🚀

🌟 Star this repository if you find it useful! ⭐
markdown
Copy
Edit

This format ensures **GitHub compatibility**, **easy readability**, and a **well-structured** documentation experience. 🚀 Let me know if you need any modifications!
