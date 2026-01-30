# My PhD in Depth
---

<p align="justify">
AI is increasingly deployed in high-stakes domains, yet it continues to raise significant <strong>ethical and societal concerns</strong>. While many organizations have defined ethical principles to ensure the <strong>trustworthiness</strong> of AI systems, these principles often remain difficult to operationalize and may even conflict when assessed independently. In parallel, regulatory frameworks such as the <strong>GDPR highlight the right to explanation</strong> as central to building trust in AI, emphasizing the importance of transparency in decision-making. Building on this insight, my PhD investigates <strong>transparency not merely as a means to explain individual AI decisions, but as a principled tool for auditing AI systems as a whole</strong>. In particular, my research addresses the following questions.
</p>

---

### _What type of transparency enables meaningful auditing of AI systems?_

Transparency in AI typically refers to the <strong>explanations used to account for model outputs</strong>, which can be characterized by their scope (local vs. global) and their level of rigor (non-formal vs. formal). In this work, we focus on <strong>formal explanations</strong>, instantiated through <strong>abductive and contrastive reasoning</strong>. In particular, <strong>formal abductive explanations</strong>, which answer <em>why a decision was made</em> by identifying its justifying conditions, are well suited for <strong>diagnostic analysis</strong> and therefore form the core explanatory mechanism of our auditing frameworks. This choice is inspired by influential works in explainable AI and reasoning
[[Ref1](https://link.springer.com/chapter/10.1007/978-3-030-77091-4_21), [Ref2](https://cacm.acm.org/research/explainability-is-not-a-game/)].

---

### _How can this transparency assess proxy discrimination and unfairness?_
When discussing <strong>unfairness</strong> and <strong>proxy discrimination</strong>, the focus is on how certain <strong>protected features</strong> influence a model’s decisions. Using <strong>abductive explanations</strong>, we define <strong>proxy discrimination</strong> as the model’s ability to provide explanations that apply only to individuals within the same subgroup, that is, individuals sharing the same value of a protected attribute. For <strong>unfairness</strong>, we introduce the concept of <strong>aptitude</strong>, derived from abductive explanations, which is a property <strong>independent of subgroup membership</strong>. Fairness is ensured when all individuals satisfying the same aptitude receive the same model outcome
[[Article](https://link.springer.com/chapter/10.1007/978-981-95-4969-6_20#Bib1)].

---

### _How can this transparency assess privacy leakage?_

Privacy leakage concerns the <strong>existence of individuals whose sensitive information should not be revealed</strong> by an AI model. Individuals can be divided into those with sensitive information (sensitive individuals) and those without. Using <strong>abductive explanations</strong>, we define <strong>privacy preservation for a sensitive individual</strong> as the AI model’s ability to provide an explanation that also applies to at least one non-sensitive individual. When such an explanation exists, the model is said to <strong>guarantee a shielder</strong> for that sensitive individual. Assessing privacy leakage therefore amounts to checking whether every sensitive individual admits a shielder, ensuring that sensitive information is not inadvertently exposed
[[Workshop Paper](https://arxiv.org/abs/2511.10284v1)]. Furthermore, we propose a <strong>repair methodology</strong> that enforces this property, guaranteeing that every sensitive individual admits a shielder <em>[submitted under review]</em>

---

### _How can this transparency improve healthcare decision-making and clinician–AI alignment?_

<p align="justify">
Although AI has demonstrated strong potential in <strong>healthcare decision-making</strong>, sometimes surpassing clinicians in diagnosis, its integration into clinical practice remains limited. A key challenge is the <strong>lack of trust in AI reasoning</strong>, as clinicians are often uncertain whether model decisions rely on <strong>clinically meaningful facts</strong>. While clinicians typically base diagnoses on specific clinical evidence, AI systems may justify the same diagnosis using alternative patterns learned from data. Since <strong>abductive explanations reveal model reasoning by identifying all formal hypotheses supporting a decision</strong>, we investigate how they can be used to <strong>bridge clinical reasoning and AI reasoning</strong>. We show that an AI model’s diagnosis is <strong>aligned with clinical reasoning</strong> if it provides at least one explanation that includes a clinically relevant fact <em>[submitted under review]</em>.
</p>
---
## Navigation
- [Home](../index.md)
- [Publications](pages/Publications.md)
- [News](pages/News.md)
- [CV & Contact](pages/Contact.md)
