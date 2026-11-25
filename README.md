# Zhonghui Xie · 谢中辉

**AI R&D Engineer · Self-Evolving Agents · AI Evaluation**

I build and study AI agents that improve through execution feedback. My work focuses on agent engineering, experience memory, and evaluation, with clinical coding as a demanding application.

I currently work in the Academic Department at Hangzhou Trizen Medical Technology. Previously, I developed EDA automation tools at Anlogic. I hold a master's degree in Computer Technology from Jiangsu University.

[Website](https://heloanc.github.io) · [CV](https://heloanc.github.io/cv.html) · [Email](mailto:1076694262@qq.com)

## Selected research

### RSI-ICD — self-evolving agents for clinical coding

A Teacher–Executor–Verifier framework that jointly revises executable code and role prompts while keeping model weights fixed. Paired execution feedback updates both the agent and its revision experience; independent validation selects the final version.

- **Quality:** +6.53 / +9.90 percentage points in mean diagnosis/procedure micro-F1 on MIMIC-IV ICD-9 / ICD-10, compared with the initial agent across all 200 test cases per system, including execution failures.
- **Efficiency:** 55.2% / 48.1% fewer execution tokens on common-success cases, excluding optimization cost.
- **Manuscript:** first author; submitted to *Computer Methods and Programs in Biomedicine*.

[Project overview and results](https://heloanc.github.io/rsi-icd.html)

The implementation repository is currently private. Please contact me to discuss the method or request shareable materials.

## Other work

- **Experience memory:** applicability conditions, three-valued evidence, and feedback-driven adaptation.
- **Agent evaluation:** node-level scoring, execution-trace diagnosis, LLM judges, and regression evaluation.
- **Engineering:** Python, retrieval-augmented generation, model deployment, and EDA automation tools.

---

我关注自进化智能体、经验记忆与自动评测，致力于将研究方法落实为可运行、可验证的 AI 系统。

[中文主页](https://heloanc.github.io/?lang=zh) · [研究与项目](https://heloanc.github.io/rsi-icd.html)
