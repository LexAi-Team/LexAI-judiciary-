# 📚 LexAI Judiciary Dataset (Processed)

## 🚀 Overview

This repository contains the **processed legal dataset** used in the LexAI Judiciary project.  
The data has been structured, cleaned, and converted into a format suitable for **AI-based legal search and retrieval systems**.

---

## 🧠 What Has Been Done

### ✅ Data Processing
- Parsed raw legal data into structured JSON format
- Extracted:
  - Acts
  - Sections
  - Definitions
  - Relationships
  - References

### ✅ Document Generation
- Converted legal sections into **AI-ready documents**
- Each document contains:
  - `id`
  - `content`
  - `keywords`
  - `section`
  - `act_id`

### ✅ Embedding Generation
- Generated semantic embeddings using:
  - **Model:** `bhavyagiri/InLegal-Sbert`
- Output:
  - `embeddings.npy` → vector representations
  - `id_map.json` → index-to-document mapping

---

## 📁 Dataset Structure

```text
Dataset/
├── documents.json        # Final AI-ready documents
├── sections.json         # Section-level data
├── acts.json             # Act-level data
├── definitions.json      # Legal definitions
├── relationships.json    # Graph relationships
├── references.json       # Cross references
├── embeddings.npy        # Vector embeddings (generated)
├── id_map.json           # Index mapping for retrieval
└── README.md