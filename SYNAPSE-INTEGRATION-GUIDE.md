# SYNAPSE Universal B2B Sales Intelligence Engine — Integration Guide

This guide explains how to use the **single combined `SKILL.md` file** with ChatGPT, Google Gemini, and Claude. The file already contains the SYNAPSE operating instructions and sales knowledge base; a separate `REFERENCE.md` is not required for this single-file distribution.

**Repository:** [SYNAPSE Universal B2B Sales Intelligence Engine](https://github.com/ysiswoadiguna-source/SYNAPSE-Universal-B2B-Sales-Intelligence-Engine)  
**Core file:** [`SKILL.md`](SKILL.md)

## 1. ChatGPT Projects

1. Open [ChatGPT](https://chatgpt.com/).
2. Create a Project named `SYNAPSE Sales Intelligence`.
3. Upload the repository's `SKILL.md` file to the Project.
4. In Project settings, add this instruction:

   ```text
   Use the uploaded SYNAPSE SKILL.md as the primary operating framework. Follow its evidence-classification rules, opportunity qualification method, probability and confidence guidance, communication standards, and Next Best Action logic. Never invent missing customer, product, price, timing, or competitor information.
   ```

5. Start a chat inside the Project and paste a customer conversation, CRM entry, or email for analysis.

Official guide: [Projects in ChatGPT](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)

## 2. Google Gemini Skills

1. Open [Google Gemini](https://gemini.google.com/).
2. Open **Customize → Skills** and choose **Create/Upload** (labels may vary by interface).
3. Select the single `SKILL.md` file from this repository.
4. Review the detected Skill name and instructions, then choose **Create**.
5. Enable or select the Skill when needed, then test it with a customer conversation.

Official guide: [Create and manage skills for Gemini Apps](https://support.google.com/gemini/answer/17094296?hl=en)

Gemini requires Skill metadata and instructions to be in `SKILL.md` at the top level. This distribution is designed for that single-file workflow.

## 3. Claude Skills

Use the upload flow available in your Claude account:

1. Open [Claude](https://claude.ai/).
2. Ensure **Code execution and file creation** (or **Create and edit files**) is enabled if your account requires it for Skills.
3. Open **Customize → Skills** and choose **Create skill / Upload a skill**.
4. If the interface accepts a Markdown file directly, upload `SKILL.md`.
5. If the interface requires a ZIP, create a folder named `synapse-sales-intelligence`, place only `SKILL.md` inside it, and ZIP that folder:

   ```text
   synapse-sales-intelligence.zip
   └── synapse-sales-intelligence/
       └── SKILL.md
   ```

6. Finish the upload/import, enable the Skill, and test it with a customer conversation.

Official guides: [Use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude) · [How to create custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)

## 4. Test the Integration

After setup, use this prompt to test the integration:

```text
Analyze the following customer conversation using the SYNAPSE Universal B2B Sales Intelligence Engine.

1. Determine the current opportunity position and buying stage.
2. Identify buying signals, objections, risks, and key unknowns.
3. Estimate opportunity probability (0–99%) and state confidence separately.
4. Recommend one primary Next Best Action and explain why.
5. Draft a natural customer-facing reply appropriate to the relationship and sales stage.

Separate facts from claims and inferences. Do not invent missing information.

[Paste customer conversation here]
```

## 5. Usage Notes

- Use the combined `SKILL.md` as the single source for the SYNAPSE framework.
- Distinguish verified facts, customer claims, inferences, hypotheses, and unknowns.
- Do not invent pricing, stock, specifications, competitor details, dates, or commitments.
- Review AI-generated analysis before using it in a live customer interaction.
- Avoid uploading confidential customer data unless you are authorized and have checked the platform's data settings.

---

**Less guessing. Smarter selling. Better decisions.**
