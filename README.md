````markdown
# 🛒 Smart Online Product Search & Summarization

This project uses **LLMs**, **Semantic Kernel**, and **SerpAPI** to search for products (e.g., on Amazon), filter relevant results, and generate short, human-readable summaries using natural language. It’s designed to be a starting point for AI-powered shopping assistants.

---

## 🚀 Features

- 🔍 **Live Product Search** using [SerpAPI](https://serpapi.com/)
- 🧠 **Summarization** with HuggingFace Transformers (`distilbart-cnn-12-6`)
- 🧰 Semantic Kernel integration for future agent-based automation
- ✅ Clean code with fallback handling and simple summarization logic
- 📦 Modular functions for easy re-use in your own apps

---

## 🧠 Tech Stack

| Tool | Purpose |
|------|---------|
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Planning and future agent integration |
| [Transformers](https://huggingface.co/transformers) | Summarization (DistilBART) |
| [SerpAPI](https://serpapi.com/) | Amazon product search |
| Python | Core scripting |

---

## 📂 File Structure

```bash
.
├── M_OnlineSmartSearch_Final.ipynb  # Jupyter Notebook with full implementation
└── README.md                        # Project documentation
````

---

## 📦 Setup Instructions

1. **Clone the Repository**

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**
   Open the Jupyter notebook:

   ```bash
   jupyter notebook M_OnlineSmartSearch_Final.ipynb
   ```

4. **Enter Your SerpAPI Key**
   When prompted in the notebook, paste your [SerpAPI](https://serpapi.com/) key:

---

## 🧪 Example Usage

Search for **"Best noise cancelling headphones under $300"**, and the script will:

* Pull top 8 Online listings
* Extract names, prices, and ratings

---

## ⚠️ Limitations

* **Semantic Kernel usage is minimal**: Only imported; not actively used in this version
* **API limitations**: Ensure your SerpAPI quota allows Amazon searches
* **Summarization length**: Handles only moderately long texts (between 50–150 words)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
