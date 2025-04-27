# ✅ Getting Started: AI Project Kickoff Checklist

This checklist is designed for teams about to begin an AI project using **Large Language Models (LLMs)**—whether you're calling an API (like OpenAI or Claude) or hosting your own open-weight model (like LLaMA or Mistral).

Use this before you start building. It helps you clarify your intent, spot potential risks early, and bring the right people into the conversation.

---

## 🧭 1. Clarify the Use Case

- [ ] Have we clearly defined the goal of using AI?
  - e.g. "Auto-generate product descriptions for our e-commerce site"
- [ ] Is an LLM the right type of model for this task?
  - [Intro to LLMs → OpenAI](https://openai.com/research), [Anthropic](https://www.anthropic.com/), [Stanford HAI](https://hai.stanford.edu/)

---

## 🔍 2. Understand Your LLM Options

- [ ] Will we use a **closed API** (like GPT-4, Claude) or **open-weight model** (like LLaMA 3)?
- [ ] Do we understand the **trade-offs** between API and self-hosted models?
  - APIs are easy to start with, but raise dependency and privacy concerns
  - Open-weight models offer flexibility, but require hosting and governance
  - [Compare LLM options → Hugging Face Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)

---

## 🧠 3. Define Roles and Responsibilities

- [ ] Who is the **Project Owner**?
- [ ] Who will handle **data sourcing** and **model configuration**?
- [ ] Who ensures the project is **aligned with company values and risks**?

💡 Use the [Role Mapping Template](../templates/role-mapping-template.md) to assign responsibilities.

---

## 🔐 4. Plan for Data Use and Privacy

- [ ] What **data will we input** into the model (e.g. prompts, documents)?
- [ ] Could that data contain sensitive or personal information?
- [ ] Are we sharing this data with a third-party LLM provider?

> Note: Some LLMs may **store inputs for training or logging**.  
> Always check provider terms. See [AWS on Data Privacy](https://aws.amazon.com/blogs/security/data-privacy-in-generative-ai/).

---

## ⚠️ 5. Identify Early Risks and Friction Points

- [ ] Could the model generate inappropriate, biased, or false outputs?
- [ ] Have we defined what "harm" might look like for this use case?
- [ ] Do we have a rollback plan if it goes wrong?

Use the [Risk Evaluation Checklist](./04_risk-evaluation.md) to go deeper.

---

## 👥 6. Involve the Right Stakeholders Early

- [ ] Who in our company needs to know before we launch this?
  - Legal? IT? Data? Marketing?
- [ ] Have we booked time for a **project kickoff review**?
- [ ] Are we aligned on how "success" will be measured?

💡 Use the [Stakeholder Prompt Guide](../templates/stakeholder-prompt-guide.md) to prep talking points.

---

## 🧾 7. Document Your Starting Point

- [ ] Create a shared document or repo to track:
  - Use case description
  - Risks discussed
  - Chosen model + rationale
  - Project roles and checkpoints

> This will help you **iterate responsibly** and refer back as your project evolves.

---

## ✅ Next Step: [Data & Privacy Checklist →](./02_data-privacy.md)
