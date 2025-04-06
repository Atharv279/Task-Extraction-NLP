Task Extraction & Categorization using NLP

📌 Project Overview

This project implements an NLP-based pipeline to extract and categorize tasks from unstructured text. The system identifies action items, extracts key details (who needs to perform the task, what action needs to be done, and the deadline), and categorizes the task using custom heuristics and a Word2Vec-based custom model.

🛠 Features

✅ Task Identification – Extracts actionable tasks from unstructured text.
✅ Entity Extraction – Identifies Person, Action, and Deadline.

✅ Task Categorization – Uses custom Word2Vec model to assign categories.

✅ Preprocessing Pipeline – Tokenization, POS tagging, and text cleaning.

✅ Modular Design – Functions are structured for reusability and clarity.



⚙️ How It Works

1️⃣ Preprocessing

Cleans text (removes stopwords, punctuation, etc.).
Tokenizes sentences & words.

2️⃣ Task Identification

Uses POS tagging to detect action-oriented sentences.
Checks for imperative verbs & task-related keywords.

3️⃣ Entity Extraction

Identifies Person, Action, Deadline using heuristics.

4️⃣ Task Categorization



📌 Challenges & Insights

🔹 Challenges Faced

Handling false positives – Some general statements (e.g., "I need to sleep early") were misclassified as tasks.

Person extraction accuracy – Named Entity Recognition (NER) was not allowed, so heuristic-based name extraction was used instead.

Deadline detection – Some phrases like "end of the week" were difficult to standardize.

🔹 Insights & Improvements

Fine-tuning heuristics improved task identification accuracy.
Custom Word2Vec model enabled better task categorization based on action words.

Expanding the dataset with more training examples could further enhance performance.

📽️ Code Walkthrough Video

Watch the video walkthrough of this project:  
[📹 Click Here to Watch] (https://drive.google.com/file/d/1LT_Ej2eizjz3rLMlTYFJp5aPAXMnFU5T/view?usp=sharing)

📜 License

This project is for educational purposes and part of an AI internship assignment.

📬 Contact
For any questions or improvements, feel free to connect on GitHub or LinkedIn: www.linkedin.com/in/atharv-patil-bab53a284.
