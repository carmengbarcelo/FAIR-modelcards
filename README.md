# FAIR Model Cards

This repository accompanies the paper:

**FAIR Model Cards: Transparent and Machine-Readable AI Documentation**

It contains the corpus of original Model Cards collected from Hugging Face and the corresponding FAIR-aligned, machine-readable metadata extracted from them.

---

## Repository Contents

The repository includes two compressed archives:

- **inputs.zip**  
  Original Model Cards as published on Hugging Face, organized by model author/user.

- **outputs.zip**  
  JSON files containing FAIR-compliant metadata extracted from the original Model Cards.

---

## Description

- The model cards in `inputs.zip` reflect real-world documentation practices and are written in natural language (Markdown).
- The metadata in `outputs.zip` follows the structured schema proposed in the paper.
- Each JSON file is generated exclusively from the corresponding model card, without using external knowledge.
- Missing or ambiguous information is explicitly marked as `"Not provided"`.
