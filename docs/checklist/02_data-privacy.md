# 🔐 Data & Privacy Checklist (LLM Projects)

This guide helps your team think through key **data and privacy questions** when starting an AI project using a **Large Language Model (LLM)**.

It applies to both:
- Closed models (e.g. OpenAI, Anthropic, Cohere)
- Open-weight models (e.g. LLaMA, Mistral, Falcon, MPT)

---

## 🧾 1. Understand What Data Will Be Used

- [ ] What **input data** will the model receive? (e.g. customer messages, internal documents)
- [ ] Does it include **personal, confidential, or regulated information**?
- [ ] Are we enriching prompts with **real user data** or company-specific insights?

> For basic definitions of personal data, refer to [ICO UK’s quick guide](https://ico.org.uk/for-organisations/guide-to-data-protection/introduction-to-data-protection/).

---

## 🌐 2. Know Where Data Is Going

- [ ] Are we using a **hosted API** (e.g. OpenAI, Claude, Bard)?
  - If yes, where is the data sent? Is it stored? Can we opt out of training?
  - [OpenAI data usage policy](https://openai.com/enterprise-privacy)
- [ ] If self-hosting an open-weight model:
  - Who controls access to the model server?
  - Is input/output logging turned on?

> Some APIs **log requests** by default unless you’re on a paid/private tier.

---

## 📦 3. Check Consent and Permissions

- [ ] Do we have user/customer consent to use their data this way?
- [ ] Are employees aware their input may be used to train or tune a model?
- [ ] If training or fine-tuning, are the datasets **ethically sourced**?

---

## ⚖️ 4. Assess Legal and Ethical Boundaries

- [ ] Are we complying with relevant data laws (e.g. GDPR, PDPA, CCPA)?
- [ ] Have we discussed ethical implications for:
  - Employee monitoring?
  - Surveillance or profiling?
  - Generating synthetic personal information?

> ⚖️ You don’t need to be a lawyer to raise the right questions early.  
> See [MIT Responsible AI Toolkit](https://mitsloan.mit.edu/ideas-made-to-matter/responsible-ai-toolkit) for team-friendly templates.

---

## 🧪 5. Perform a Minimal Data Impact Review

Use this simple framing to reflect:

| Question | Example |
|---------|---------|
| What’s the minimum data needed for the task? | "Can we anonymize names?" |
| Where could data leaks occur? | "Prompt injection reveals private info" |
| Who gets access to the logs? | "Model outputs may be cached by engineers" |

---

## ✅ Next Step: [Accountability & Roles Checklist →](./03_accountability-roles.md)
