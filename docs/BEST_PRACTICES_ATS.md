# ⚙️ ATS Best Practices: Behind the Scenes of the Skill

The `SKILL.md` in this repository was built based on strict Applicant Tracking System parsing (syntactic analysis) rules, while also focusing on LLM token efficiency. Here we detail the reasoning behind each instruction contained in the skill.

### 1. Integrated Web Research (LinkedIn)

The technology and business job market changes rapidly. The skill instructs the AI to scan recently posted jobs on LinkedIn using the position the user wants. This ensures the resume doesn't use generic keywords, but rather the exact terms recruiters are configuring in their ATS filters at that very moment.

### 2. Minimalist Design and Token Economy

The instruction requires creating a single-page, black-and-white document without excessive formatting (like colored tables or skill progress bars). There are two reasons for this:

- **Parseability (ATS):** Bots don't read design. Graphic elements, floating text boxes, or progress bars often corrupt data extraction.
- **LLM Efficiency:** AIs consume _tokens_ to generate responses. Forcing the AI to attempt drawing a visually complex resume using code wastes the processing limit and increases the chance of hallucinations. The clean layout keeps the AI focused on content quality.

### 3. File Format: Why We Require `.docx`?

Although PDF is great for maintaining visual formatting, it can be the worst enemy of older ATS systems (which often read the page as an image). The `.docx` format (Microsoft Word) is natively structured as plain text under the hood (XML), guaranteeing a very high success rate in bot reading.

### 4. Objective Title

AI algorithms cross-reference the job requisition (Job Description) with the top of your resume. The skill requires the exact name of the desired position (without trying to "guess" what the user wants) right at the beginning to ensure the initial indexing "match".

### 5. Action Verbs and Results

AIs are trained to identify the impact you caused, not just your duties. The skill rewrites experiences by inserting proactive action verbs ("Developed", "Optimized") geared toward results.

---

_Documentation integrated into the **ats-resume-optimizer** skill._
_Originally developed by [PoftPuft](https://github.com/PoftPuft) under CC BY-NC-SA 4.0 license._