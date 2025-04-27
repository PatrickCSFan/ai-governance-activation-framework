# ⚠️ Risk Evaluation Checklist (LLM Projects)

Every AI project carries risk—not just technical, but reputational, ethical, and operational. For teams using **Large Language Models (LLMs)**, some risks may not be obvious at first.

This checklist helps you **spot early-stage risks** so they can be tracked, discussed, or designed around—not ignored.

---

## 🔄 1. Start With the “What If” Test

- [ ] What’s the **worst-case scenario** if this LLM output is wrong or misleading?
- [ ] Could it create **legal, brand, or customer trust issues**?
- [ ] Who would be **impacted or harmed**, and how?

💡 Think about both *false positives* and *false negatives*.

---

## 📊 2. Identify LLM-Specific Risk Factors

- [ ] Could the model generate **biased or offensive content**?
- [ ] Can the outputs be **easily manipulated** (e.g. prompt injection)?
- [ ] Are **hallucinations** (confident but false answers) a risk?
- [ ] Are we relying on LLM outputs **without human review**?

> [Anthropic: Red Teaming LLMs](https://www.anthropic.com/index/2023/10/04/red-teaming-language-models) is a good resource for exploring failure modes.

---

## 🔐 3. Consider Data & Privacy Risks

- [ ] Could the model **reproduce sensitive data**?
- [ ] Are we accidentally sharing confidential input with a third-party API?
- [ ] Have we defined **data retention and logging policies**?

> Go back to the [Data & Privacy Checklist](./02_data-privacy.md) if needed.

---

## 📉 4. Reputational or Misuse Risk

- [ ] Could this system be **misused or misinterpreted**?
- [ ] Are we clearly communicating what the model can and cannot do?
- [ ] Is it being deployed in a **public or user-facing setting**?

> ⚠️ Even internal pilots can leak externally—always assume visibility.

---

## 🧰 5. Align on Risk Handling Approach

- [ ] Are we **tracking these risks** in a shared place (e.g. Notion, Jira, repo)?
- [ ] Have we discussed **when to escalate** concerns?
- [ ] Have we defined **fallbacks, guards, or human review checkpoints**?

---

## 🌐 6. Want to Go Deeper?

Once your team is ready to formalize, consider these resources:

- [Stanford CRFM: AI Risk Framework](https://crfm.stanford.edu/)
- [OECD: AI Risk Classification](https://oecd.ai/en/classification)
- [MIT Sloan: Risk Identification Toolkit](https://mitsloan.mit.edu/ideas-made-to-matter/responsible-ai-toolkit)

---

## ✅ Next Step: [Iteration & Scaling Checklist →](./05_next-steps.md)
