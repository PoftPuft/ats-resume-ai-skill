# 🚀 ATS & AI Resume Optimizer Skill

A universal prompt skill (system instruction) designed to transform LLMs (Gemini, ChatGPT, Claude) into recruitment specialists. The main focus is creating from scratch, rewriting, and optimizing resumes to bypass **Applicant Tracking Systems (ATS)** filters and AI screening algorithms.

## 🎯 Why Use This Skill?

Modern companies use screening software that reads resumes looking for keywords, linear structures, and specific patterns. A visually beautiful but poorly structured resume in text is often discarded before reaching a human. This skill ensures your resume "speaks the language" of recruitment robots and generates a ready-to-submit file.

## 🛠️ How to Use

1. Copy the content of the [`SKILL.md`](SKILL.md) file.
2. Paste it into your preferred AI's configuration section:
   - **Gemini:** Create a new "Skill" (feature replacing the old "Gems").
   - **ChatGPT:** Paste into the "Custom Instructions" section or create a custom GPT.
   - **Claude:** Use the "Projects" functionality to add the system prompt.
3. Start the conversation. You have two options:
   - **Option A (Update):** Send your current resume as an attachment (PDF or text) and ask the AI to optimize it. The AI will always ask for the target role before starting.
   - **Option B (Create from Scratch):** Just say "I want to create my resume." The skill will activate **Questionnaire Mode**, asking targeted questions about your career to build the document.

## ✨ Key Features

- **LinkedIn Market Analysis:** If the AI has web access, it searches for real jobs on LinkedIn with the title you want and extracts the hottest keywords from the market right now.
- **Memory Integration:** Pulls tool history and work area saved in the AI profile.
- **Minimalist ATS Design (Single Page):** Focuses on a black-and-white, structured layout without graphical elements, saving AI **tokens** and ensuring both human recruiters and bots read what matters.
- **Export to `.docx`:** The AI is instructed to generate a Word file ready for download, facilitating future edits and ensuring the best compatibility with ATS readers.

## 🗂️ Repository Structure

- [`SKILL.md`](SKILL.md): The source code of the main prompt (System Prompt) to be injected into the AI.
- [`README.md`](README.md): Main documentation and project showcase.
- [`SECURITY.md`](SECURITY.md): Security policy, privacy, and prompt vulnerability mitigation.
- [`LICENSE`](LICENSE): Creative Commons License (CC BY-NC-SA 4.0).
- [`docs/BEST_PRACTICES_ATS.md`](docs/BEST_PRACTICES_ATS.md): Technical documentation on ATS parsers and applied rules.
- [`docs/LEGAL_NOTICE_LGPD.md`](docs/LEGAL_NOTICE_LGPD.md): Terms of use, privacy, and sensitive data protection (LGPD/GDPR).

### 🌐 Multilingual Versions

- **Portuguese:** [`README.pt.md`](README.pt.md) | [`SKILL.pt.md`](SKILL.pt.md) | [`SECURITY.pt.md`](SECURITY.pt.md) | [`docs/BOAS_PRATICAS_ATS.md`](docs/BOAS_PRATICAS_ATS.md) | [`docs/AVISO_LEGAL_LGPD.md`](docs/AVISO_LEGAL_LGPD.md)
- **Spanish:** [`README.es.md`](README.es.md) | [`SKILL.es.md`](SKILL.es.md) | [`SECURITY.es.md`](SECURITY.es.md) | [`docs/BUENAS_PRACTICAS_ATS.md`](docs/BUENAS_PRACTICAS_ATS.md) | [`docs/AVISO_LEGAL_GDPR.md`](docs/AVISO_LEGAL_GDPR.md)

## 👨‍💻 Authorship and Credits

This project was conceived, developed, and is maintained by **[PoftPuft](https://github.com/PoftPuft)**.
If this skill optimized your resume and helped you land an interview, connect with me on GitHub and share your success!

## ⚖️ License and Contributions

Feel free to open _issues_ or submit _pull requests_ with suggestions. This project is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**, protecting the original author's usage rights and prohibiting monetization or commercial use by third parties.