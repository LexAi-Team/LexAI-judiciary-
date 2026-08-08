Here’s your **final clean `README.md`** for the **project dataset folder** — ready to paste directly 👇

---

```md
# 📊 LexAI Project Dataset

This folder contains the **final processed legal dataset** used in the LexAI project.

The data is clean, structured, and ready to be used directly for:
- Search systems
- Backend APIs
- AI-based retrieval

---

## 📁 Folder Structure

```

dataset/
│
├── documents.json   ⭐ Main dataset
├── sections.json
├── acts.json
├── relationships.json
├── references.json
└── definitions.json (optional)

````

---

## 🧠 Core File

### `documents.json`

This is the **primary dataset** used in the project.

Each entry represents a complete legal section with all relevant content merged.

```json
{
  "id": "DOC000001",
  "section_id": "SEC000001",
  "act_id": "ACT000001",
  "title": "Short title and extent",
  "section": "Section 1",
  "content": "Full legal text...",
  "keywords": ["act", "law"],
  "references": []
}
````

---

## 📄 Other Files

### `sections.json`

Contains structured section-level data and hierarchy.

### `acts.json`

List of all Acts included in the dataset.

### `relationships.json`

Defines hierarchy:

```
Act → Part → Chapter → Section
```

### `references.json`

Cross-references between legal sections.

### `definitions.json` *(optional)*

Legal terms and definitions extracted from Acts.

---

## 🎯 Purpose

This dataset is used to:

* Retrieve relevant legal sections
* Support legal search and query matching
* Power backend services
* Serve as input for AI systems

---

## ⚙️ Usage

Example:

```python
import json

with open("dataset/documents.json", encoding="utf-8") as f:
    documents = json.load(f)

print(documents[0])
```

---

## ⚠️ Notes

* Only final processed data is included
* Raw datasets and scripts are excluded
* Data is cleaned and normalized for direct use

---

## 🚀 Status

```
✔ Ready for use
✔ Cleaned
✔ Structured
✔ AI-ready
```

```

---

If you want next:

👉 I can create **full project README (UI + API + dataset + demo)**  
👉 Or help you make your repo look 🔥 for judges

Just say 👍
```
