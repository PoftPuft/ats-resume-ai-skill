# 🛡️ Security Policy

The security and privacy of users of this Skill are absolute priorities. Since this project is not executable software but rather a prompt engineering (System Prompt) for LLMs, the security scope focuses primarily on personal data protection and mitigation of unwanted AI behaviors.

## 📌 Security Scope

We consider the following as valid security incidents for reporting in this repository:

- **Unintentional Data Leakage:** The prompt induces or forces the user to provide sensitive data (SSN, ID, exact address) that should not be requested.
- **Output Failures (Prompt Injection):** The prompt can be easily subverted to generate malicious, offensive, or off-scope content outside professional recruitment.
- **Privacy Violations:** The AI behavior violates the guidelines stipulated in the `LEGAL_NOTICE_LGPD.md` file.

_Note: We are not responsible for how third-party companies (OpenAI, Google, Anthropic) process or store data entered in their respective chats._

## 🚨 How to Report a Vulnerability or Privacy Issue

If you find an issue that falls within the scope above, **DO NOT open a public Issue** immediately, as this may expose the flaw before we can mitigate it in the main instruction.

1. Send an email directly to the project maintainer or use direct messages via [GitHub](https://github.com/PoftPuft).
2. Include in the report:
   - Which LLM you were using (Gemini, ChatGPT, Claude, etc.).
   - The exact behavior the AI exhibited.
   - The prompt snippet you believe is causing the failure (if known).
3. We will attempt to respond and apply corrections to the `SKILL.md` file as quickly as possible, usually within 48 hours.

## ✅ Supported Versions

Only the latest version present in the `main` branch of the `SKILL.md` file receives support and security updates.

---

_Policy integrated into the **ats-resume-optimizer** skill._
_Originally developed by [PoftPuft](https://github.com/PoftPuft) under CC BY-NC-SA 4.0 license._