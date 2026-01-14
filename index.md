<!-- ## Belona Sonna-->
  
## About Me
  
I am a PhD student in the [Humanizing Machine Intelligence](https://hmi.anu.edu.au/) group at the **Australian National University**, where my research focuses on the **formal verification of AI ethics principles in AI decision processes**. I am honoured to be supervised by [Dr. Alban Grastien](https://comp.anu.edu.au/people/alban-grastien/), [Prof. Lexing Xie](https://users.cecs.anu.edu.au/~xlx/index.html), and [Dr. Michael Norrish](https://researchportalplus.anu.edu.au/en/persons/michael-norrish).

My current work aims to design **assessment frameworks based on formal abductive explanations** to audit **proxy discrimination**, **unfairness**, and **privacy leakage** in AI decisions. I am particularly interested in applying these methods to **healthcare systems**, where ensuring trustworthy AI is critical for real-world impact.

Beyond research, I actively advocate for **expanding access to AI and STEM education** among underrepresented communities, especially in Africa. I am the **Founder and Co-lead of [Bel’s AI Initiative](https://www.linkedin.com/company/bel-s-ai-initiative/)**, which conducts bilingual (English and French) AI outreach in Central Africa with a focus on rural areas. I am also a member of [AfroLeadership](https://afroleadership.org/), the [WIMLDS Yaoundé](http://wimlds.org/about-the-yaounde-team-2/) chapter, and a co-organizer of [KMERAI](https://sites.google.com/view/kmerai-2021/home?authuser=0) events.

I have been recognized among the [Top 40 under 40 African AI Achievers](https://www.linkedin.com/posts/society-for-ai_ai40under40-africanaisummit-activity-7395416482526142464-zOql?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAB2_j58BZ0lhOJB8dtUXWivqrgWvl2Vcdqo), the  [100 Brilliant Women in AI Ethics™ – 2022](https://womeninaiethics.org/the-list/of-2022/) and the [80 African women advancing Artificial Intelligence in Africa and around the world](https://africanshapers.com/en/80-african-women-advancing-artificial-intelligence-in-africa-and-the-world/).



---

## Navigation

- [PhD Research](pages/phd.md)
- [Publications](pages/publications.md)
- [CV](pages/CV.md)
- [Contact](pages/contact.md)

  
---


## My PhD Research in Depth

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
## Selected Publications
- **Belona Sonna**, Alban Grastien, Claire Benn. _Beyond Verification: Abductive Explanations for Post-AI Assessment of Privacy Leakage_.  In Proceedings of The Workshop on Post-AI Formal Methods @ AAAI-26.[[Link](https://arxiv.org/abs/2511.10284v1)]
- **Belona Sonna**, Alban Grastien. _On Explaining Proxy Discrimination and Unfairness in Individual Decisions Made by AI Systems_. In Proceedings of Australasian Joint Conference in Artificial Intelligence 2025 (AJCAI 2025). [[Link](https://link.springer.com/chapter/10.1007/978-981-95-4969-6_20), [Slides](https://drive.google.com/file/d/1Ndl_tXJSpZhdnuz-j0kh7wDBzlcnwsd-/view?usp=drive_link), [Poster](https://drive.google.com/file/d/1jAZRdhunYmtNy9JjWEoOcE4gTTReetKt/view?usp=drive_link)]
- **Belona Sonna**, Alain Momo and Alban Grastien. _Formal Abductive Explanations for Navigating Mental Health Help-Seeking and
Diversity in Tech Workplaces_. In Proceedings of Empowering Women of Colour in AI-Driven Mental Health Research @ IJCAI-25. [[Slides](https://drive.google.com/file/d/1qLwUIqr4cifvUvdG1ne9z6N4bqzHwKWJ/view?usp=drive_link), [Award](https://drive.google.com/drive/folders/1ZNoberoMxLUOOs0PVtnwTQxtq4DQHJcH)]
- **Belona Sonna** and Alban Grastien. 2024. _Can Unfairness in ML Decision-Making Processes be Assessed  Through the Lens of Formal Explanations?_. In Proceedings of XAI 2024 workshop @ IJCAI. [[Link](https://drive.google.com/file/d/1S4JfA3NtBtLXx9HOAtQQk0C8ECS-W7Lk/view?pli=1)]
- Gadosey Pius Kwao, Deborah Dormah Kanubala, and **Belona Sonna**. 2023. AI Ethics Education for Future African Leaders. In book: AI Ethics in Higher Education: Insights from Africa and Beyond (pp.87-101). [[Link](https://link.springer.com/content/pdf/10.1007/978-3-031-23035-6_7.pdf)]
- Ezinne Nwankwo and **Belona Sonna**. 2019. Africa’s social contract with AI. XRDS 26, 2 (Winter 2019), 44–48. [[Link](https://dl.acm.org/doi/10.1145/3368073)].
- Full list available through my [Google Scholar Profile](https://scholar.google.com/citations?hl=en&user=oqqzmloAAAAJ)

---
## News
- **August 2025**: I was thrilled to deliver a lightning talk at the Empowering Women of Colour in AI-Driven Mental Health Research @ IJCAI-25
- **July 2025**: I have served as reviewer for the Trustworthy AI workshop @ Deep Learning Indaba 2025
- **June 2025**: I have served as reviewer for the AIES 2025 Conference
- **August 2024**: Presenting at the XAI 2024 workshop @ IJCAI
- **September 2023**: I was priviledged to participate virtually to the CCAIM AI and Machine Learning Summer School
- **February 2023**: I was featured in the podcast The [Fault in our Algorithms](https://podcasts.apple.com/be/podcast/episode-7-belona-sonna-phd-candidate-at-humanizing/id1614227469?i=1000575262447)
- **July 2022**: I have attended the [inSTEM](https://archive.fleet.org.au/blog/events/instem-conference-2022/) conference in Brisbane
- **March 2022**: I am thrilled to serve as a panelist in the responsible AI project with [MIT Sloan Management Review](https://sloanreview.mit.edu/). My views are listed [here](https://sloanreview.mit.edu/panelist/belona-sonna/)
- **February 2022**: Excited to share my interview about my experience with [wordsthatcount](https://wordsthatcount.org/my-journey-into-artificial-intelligence-ai-belona-sonna/)
- **February 2022**: Excited to start tutoring the statistical Machine Learning course.
- **January 2022**:  Excited to begin my PhD with Dr Alban Grastien in the Humanizing Machine Intelligence at the Australian National University.
- **October 2021**: I was thrilled to be granted my student visa to Australia. I couldn’t wait to travel to Canberra to start my PhD journey once the borders reopened after the COVID lockdowns.
- **September 2021**: I am excited to receive a signed copy of the book [*THE AI THOUGHT BOOK: Inspirational Thoughts & Quotes on Artificial Intelligence*](https://www.amazon.com.au/dp/B08Z4BWN1X?ref_=mr_referred_us_au_au) from the author [Murat Durmus](https://www.linkedin.com/in/ceosaisoma/).
- **June 2020**: I was privileged to attend virtually the [MLSS 2020](http://mlss.tuebingen.mpg.de/2020/index.html)
- **December 2029**: I have attended the [NeurIPS 2019](https://neurips.cc/Conferences/2019) and presented a poster at the [WiML workshop 2019](https://www.wiml.org/wiml-workshop-2019)
- **September 2019**: I have served as reviewer for the WiML Workshop NeuriPS 2019
- **August 2019**: I have attended my first international conference in Artificial Intelligence , The [Deep Learning Indaba 2019](https://deeplearningindaba.com/2019/) in Nairobi.

---
## Social Media
- **LinkedIn:** [Belona Sonna](https://www.linkedin.com/in/belona-sonna/)
- **X:** [Belona Sonna](https://x.com/BelonaSonna)
- **Facebook:** [Belona Sonna](https://www.facebook.com/DameIAEthics/)
- **GitHub:** [Belona Sonna](https://github.com/belsonna/)

---
