# 🔍 ALU Regex Data Extraction - {YourUsername}

## 📘 Project Overview

Welcome to the **Regex Onboarding Hackathon**! This project demonstrates the power of Regular Expressions in extracting structured data from unstructured string inputs — a common task in full-stack web development. The assignment simulates a real-world scenario in which a web application aggregates text-based data from across the internet and extracts meaningful information using regex patterns.

This repository contains solutions for extracting the following data types using Regular Expressions (at least 4 implemented):

- ✅ Email Addresses
- ✅ URLs
- ✅ Phone Numbers
- ✅ Credit Card Numbers
- ✅ Time Formats (12-hour and 24-hour)
- ✅ HTML Tags
- ✅ Hashtags
- ✅ Currency Amounts

> _Language Used:_ **Python** / **JavaScript**  
> _Author:_ **MUHIRWA Nathan**  
> _GitHub Repo:_ `(https://github.com/muhirwanathan/alu_regex-data-extraction-muhirwanathan/)`

---

## 📂 Repository Structure

```bash
alu_regex-data-extraction-{YourUsername}/
│
├── README.md                 # Project documentation
├── regex_extraction.py       # (or regex_extraction.js)
├── sample_inputs.txt         # Sample raw text with test cases
├── output_results.txt        # Extracted results after running the script
└── test_cases/               # Unit test scripts (if applicable)
````

---

## 🚀 How to Run the Project

### ✅ Python

1. Clone the repository:

   ```bash
   git clone https://github.com/{YourUsername}/alu_regex-data-extraction-{YourUsername}.git
   cd alu_regex-data-extraction-{YourUsername}
   ```

2. Run the script:

   ```bash
   python3 regex_extraction.py
   ```

### ✅ JavaScript (Node.js)

1. Clone the repository and navigate into it:

   ```bash
   git clone https://github.com/{YourUsername}/alu_regex-data-extraction-{YourUsername}.git
   cd alu_regex-data-extraction-{YourUsername}
   ```

2. Run the script:

   ```bash
   node regex_extraction.js
   ```

---

## ✅ Implemented Patterns

Here are the regex patterns implemented in the project:

| Data Type         | Regex Overview                                                 |
| ----------------- | -------------------------------------------------------------- |
| **Emails**        | Matches standard email formats                                 |
| **URLs**          | Detects `http`, `https`, and subdomains                        |
| **Phone Numbers** | Supports `(123) 456-7890`, `123-456-7890`, `123.456.7890`      |
| **Credit Cards**  | Matches `1234-5678-9012-3456`, with or without spaces          |
| **Times**         | Handles both 24-hour (`14:30`) and 12-hour (`2:30 PM`) formats |
| **HTML Tags**     | Matches tags like `<p>`, `<div class="x">`, `<img src="...">`  |
| **Hashtags**      | Identifies strings like `#example` and `#ThisIsAHashtag`       |
| **Currency**      | Extracts values like `$19.99` and `$1,234.56`                  |

---

## 🔬 Sample Output

Example output from `output_results.txt`:

```
Emails Found:
- user@example.com
- firstname.lastname@company.co.uk

URLs Found:
- https://subdomain.example.org/page

Phone Numbers Found:
- (123) 456-7890
- 123.456.7890

...
```

---

## 🧪 Edge Case Handling

All regex expressions are tested against:

* Missing domain suffixes in emails
* URLs with or without trailing slashes
* Incomplete credit card formats
* Unclosed HTML tags
* Hashtags with special characters

---

## ✅ Project Requirements Checklist

* [x] Minimum 4 regex types implemented
* [x] GitHub repo with ALU email
* [x] Clean code structure and meaningful commits
* [x] Edge case handling
* [x] Testable output included

