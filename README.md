# 🤖 AI Assistant with GPT-4o

Build a custom AI assistant that can read and explain academic papers — specifically focusing on Artificial General Intelligence (AGI) — using OpenAI's Assistant API.

---

## 🚀 Getting Started

### ✅ Prerequisites

Before you begin:

- Make sure you have an **OpenAI developer account**.
- Your account must have **active credit**.
- Define an environment variable named `OPENAI_API_KEY` with your API key.

If you're unsure how to set up your API key, check out the companion notebook: `openai-setup.ipynb`.

---

## 📘 Project Overview

In this notebook, you will:

1. Upload academic papers in PDF format (e.g., from arXiv).
2. Use the OpenAI API to:
   - Upload files
   - Create a vector store
   - Configure a custom assistant ("Aggie")
3. Send messages and receive smart, contextual replies.
4. Learn how to write effective prompts (even using ChatGPT to write them!).

---

## 📂 Files

- `AI_Assistant.ipynb` – Main notebook with all the logic.
- `openai-setup.ipynb` – Helps configure and test your OpenAI key.
- `images/` – Folder for any visuals (optional).
- `README.md` – You’re reading it!

---

## 💡 Pro Tip

> Yes, you can use ChatGPT to help write prompts for assistants. One of the prompts in this notebook was created using ChatGPT itself with only minor edits!

---

## ⚠️ Billing Warning

> 🧠 Vector databases on OpenAI are **billed daily**. They auto-delete after 7 days of inactivity, but it’s a good idea to manually delete them when you’re done testing.