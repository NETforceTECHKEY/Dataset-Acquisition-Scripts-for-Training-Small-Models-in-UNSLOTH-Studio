# Dataset-Acquisition-Scripts-for-Training-Small-Models-in-UNSLOTH-Studio
Scripts for collecting and preparing datasets for small model training
SCRIPTS FOR CREATING CODING MODELS
The generator produces **two types of JSONL files**:

- **Valid files** – already correct and ready to use.
- **Invalid files** – intentionally saved with broken JSON / code errors at the beginning of the file.

All **invalid files must be passed through the Reviewer script**, which reads the corrupted output, fixes all errors, and returns a fully valid, cleaned JSONL sample.
