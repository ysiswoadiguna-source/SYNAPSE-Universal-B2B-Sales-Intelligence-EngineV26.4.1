# SYNAPSE Universal B2B Sales Intelligence Engine — Integration Guide

This guide explains how to use SYNAPSE with ChatGPT, Google Gemini, and Claude. It uses the existing files in this repository; the sales knowledge does not need to be rewritten.

**Repository:** [SYNAPSE Universal B2B Sales Intelligence Engine](https://github.com/ysiswoadiguna-source/SYNAPSE-Universal-B2B-Sales-Intelligence-Engine)

## Repository Files

- \`SKILL.md\` — instructions that describe how the AI should apply SYNAPSE.
- \`REFERENCE.md\` — the main SYNAPSE sales knowledge base and operating rules.

Keep these files together when packaging SYNAPSE as a Skill. For ChatGPT Projects, upload both files as project sources.

---

## 1. ChatGPT Projects

ChatGPT Projects let you keep related conversations, reference files, and project instructions together.

1. Open [ChatGPT](https://chatgpt.com/).
2. Create a new Project and name it \`SYNAPSE Sales Intelligence\`.
3. Download \`SKILL.md\` and \`REFERENCE.md\` from this repository and upload both files to the Project.
4. Open the Project settings and add the following project instructions:

   \`\`\`text
   Use SKILL.md as the operating instructions and REFERENCE.md as the primary SYNAPSE knowledge base. Follow the evidence-classification rules, opportunity qualification framework, probability and confidence guidance, communication standards, and Next Best Action logic. Do not invent missing customer, product, price, timing, or competitor information.
   \`\`\`

5. Start a Project chat and paste the customer conversation, CRM record, or email you want to analyze.

**Official guide:** [Projects in ChatGPT](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)

---

## 2. Google Gemini Skills

Gemini can create a Skill from a \`SKILL.md\` file, a folder, or a ZIP containing the Skill file.

1. Download \`SKILL.md\` and \`REFERENCE.md\` from this repository.
2. Create a folder named \`synapse-sales-intelligence\` and place both files inside it:

   \`\`\`text
   synapse-sales-intelligence/
   ├── SKILL.md
   └── REFERENCE.md
   \`\`\`

3. Compress the \`synapse-sales-intelligence\` folder into a ZIP file. Make sure \`SKILL.md\` is inside the folder at the top level.
4. Open [Google Gemini](https://gemini.google.com/) and go to the Skills page.
5. Choose **Upload**, select the ZIP file, review the Skill, and select **Create**.
6. Test the Skill with a customer conversation and verify that it uses the SYNAPSE framework.

**Official guide:** [Create and manage skills for Gemini Apps](https://support.google.com/gemini/answer/17094296?hl=en)

> Menu labels and feature availability may vary by account, region, or interface updates. Follow the instructions shown in your Gemini account.

---

## 3. Claude Skills

Claude supports custom Skills uploaded as ZIP files containing a Skill folder.

1. Download \`SKILL.md\` and \`REFERENCE.md\` from this repository.
2. Put both files inside a folder named \`synapse-sales-intelligence\`:

   \`\`\`text
   synapse-sales-intelligence/
   ├── SKILL.md
   └── REFERENCE.md
   \`\`\`

3. Compress the folder itself into a ZIP. The ZIP should contain \`synapse-sales-intelligence/\` as its top-level folder, not just loose files at the ZIP root.
4. Open [Claude](https://claude.ai/).
5. Go to **Customize → Skills → + Create skill → Upload a skill**.
6. Upload the ZIP, finish the import, and enable the Skill.
7. Test it with several customer conversations to confirm that the Skill is applied as expected.

**Official guides:**
- [Use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- [How to create custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)

> Follow any additional requirements displayed in your Claude account. Feature availability may depend on your plan or workspace settings.

---

## 4. Test SYNAPSE

After setup, use this prompt to test the integration:

\`\`\`text
Analyze the following customer conversation using the SYNAPSE Universal B2B Sales Intelligence Engine.

1. Determine the current opportunity position and buying stage.
2. Identify buying signals, objections, risks, and key unknowns.
3. Estimate opportunity probability (0–99%) and state confidence separately.
4. Recommend one primary Next Best Action and explain why.
5. Draft a natural customer-facing reply appropriate to the relationship and sales stage.

Separate facts from claims and inferences. Do not invent missing information.

[Paste customer conversation here]
\`\`\`

## 5. Usage Principles

- Treat \`REFERENCE.md\` as the primary source for SYNAPSE's sales analysis framework.
- Distinguish facts, customer claims, inferences, hypotheses, and unknowns.
- Never invent prices, product specifications, commitments, deadlines, or competitor details.
- Compare outputs from each platform. Different AI platforms may interpret or express the same framework differently.
- Avoid uploading confidential customer or company information unless you are authorized to do so and the platform's data settings are appropriate.

---

**SYNAPSE Universal B2B Sales Intelligence Engine**  
*Less guessing. Smarter selling. Better decisions.*
