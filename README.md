# Awesome-LLM-Supply-Chain-Security

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Page Views Count](https://badges.toozhao.com/badges/01JC7TB564H01HKPZZQXDVRNBG/blue.svg)](.)
![Stars](https://img.shields.io/github/stars/ShenaoW/awesome-llm-supply-chain-security?style=flat&logo=github)


A curated list of awesome resources about LLM supply chain security (including papers, security reports and CVEs)

Contributions are always welcome. Please follow the [Contribution Guidelines](https://github.com/ShenaoW/awesome-llm-supply-chain-security#Contribution).

## Table of Contents

- [Awesome LLM Supply Chain Security](#awesome-llm-supply-chain-security-)
  - [Papers](#papers)
    - [Technical Paper](#technical-paper)
    - [Survey](#survey)
  - [Talks](#talks)
  - [Security Reports](#security-reports)
  - [CVEs](#cves)

## Papers

### Technical Paper
- **[ICSE'25]** Prompt-to-SQL Injections in LLM-Integrated Web Applications: Risks and Defenses [[Paper]](https://syssec.dpss.inesc-id.pt/papers/pedro_icse25.pdf)


- **[S&P'25]** My Model is Malware to You: Transforming AI Models into Malware by Abusing TensorFlow APIs [[Repo]](https://github.com/ZJU-SEC/TensorAbuse)

- **[ASE'24]** Models Are Codes: Towards Measuring Malicious Code Poisoning Attacks on Pre-trained Model Hubs [[Paper]](https://arxiv.org/pdf/2409.09368)

- **[CCS'24]** Demystifying RCE Vulnerabilities in LLM-Integrated Apps [[Paper]](https://arxiv.org/pdf/2309.02926) [[Repo]](https://github.com/LLMSmith/LLMSmith)

- **[arXiv]** We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs [[Paper]](https://arxiv.org/pdf/2406.10279)

- **[SCORED'22]** An Empirical Study of Artifacts and Security Practices in the Pre-trained Model Supply Chain [[Paper]](https://wenxin-jiang.github.io/files/publications/JiangSynovicSethiIndarapuHyattSchorlemmerThiruvathukalDavis-PTMSupplyChain-SCORED22.pdf) [[Repo]](https://github.com/PurdueDualityLab/SCORED22-PTMSupplyChain)

- **[arXiv]** Naming Practices of Pre-Trained Models in Hugging Face [[Paper]](https://arxiv.org/pdf/2310.01642) 

- **[arXiv]** Towards Semantic Versioning of Open Pre-trained Language Model Releases on Hugging Face [[Paper]](https://arxiv.org/pdf/2409.10472)

- **[arXiv]** A New Era in LLM Security: Exploring Security Concerns in Real-World LLM-based Systems [[Paper]](https://arxiv.org/pdf/2402.18649)

### Survey

- **[arXiv]** Large Language Model Supply Chain: A Research Agenda [[Paper]](https://arxiv.org/pdf/2404.12736)

- **[arXiv]** Lifting the Veil on the Large Language Model Supply Chain: Composition, Risks, and Mitigations [[Paper]](https://arxiv.org/pdf/2410.21218)

- **[arXiv]** Large Language Model Supply Chain: Open  Problems From the Security Perspective [[Paper]](https://arxiv.org/pdf/2411.01604)

## Talks

- **[BlackhatUSA'24]** Practical LLM Security: Takeaways From a Year in the Trenches [[Link]](https://www.blackhat.com/us-24/briefings/schedule/#practical-llm-security-takeaways-from-a-year-in-the-trenches-39468) [[Slides]](https://i.blackhat.com/BH-US-24/Presentations/US24-Harang-Practical-LLM-Security-Takeaways-From-Wednesday.pdf?_gl=1*7acwri*_gcl_au*MjEyNjc0MzYwNC4xNzMxMTM3MDA2*_ga*MTM5MTcwNjc4OS4xNzMxMTM3MDA2*_ga_K4JK67TFYV*MTczMTEzNzAwNi4xLjAuMTczMTEzNzAwNi4wLjAuMA..&_ga=2.180973351.1863731842.1731137007-1391706789.1731137006)

- **[BlackhatUSA'24]** Isolation or Hallucination? Hacking AI Infrastructure Providers for Fun and Weights [[Link]](https://www.blackhat.com/us-24/briefings/schedule/#isolation-or-hallucination-hacking-ai-infrastructure-providers-for-fun-and-weights-40569)

- **[BlackhatUSA'24]** From MLOps to MLOops - Exposing the Attack Surface of Machine Learning Platforms [[Link]](https://www.blackhat.com/us-24/briefings/schedule/#from-mlops-to-mloops---exposing-the-attack-surface-of-machine-learning-platforms-39309) [[Slides]](https://i.blackhat.com/BH-US-24/Presentations/US24-Menashe-From-MLOps-To-MLOops.pdf?_gl=1*1vixzrp*_gcl_au*MjEyNjc0MzYwNC4xNzMxMTM3MDA2*_ga*MTM5MTcwNjc4OS4xNzMxMTM3MDA2*_ga_K4JK67TFYV*MTczMTEzNzAwNi4xLjEuMTczMTEzNzI1MS4wLjAuMA..&_ga=2.140149939.1863731842.1731137007-1391706789.1731137006)

- **[BlackhatASIA'24]** LLM4Shell: Discovering and Exploiting RCE Vulnerabilities in Real-World LLM-Integrated Frameworks and Apps [[Link]](https://www.blackhat.com/asia-24/briefings/schedule/index.html#llmshell-discovering-and-exploiting-rce-vulnerabilities-in-real-world-llm-integrated-frameworks-and-apps-37215) [[Slides]](https://i.blackhat.com/Asia-24/Presentations/bh-asia-2024-llm4shell.pdf?_gl=1*lfjimg*_gcl_au*MjEyNjc0MzYwNC4xNzMxMTM3MDA2*_ga*MTM5MTcwNjc4OS4xNzMxMTM3MDA2*_ga_K4JK67TFYV*MTczMTEzNzAwNi4xLjEuMTczMTEzNzg4OS4wLjAuMA..&_ga=2.89155611.1863731842.1731137007-1391706789.1731137006)

- **[BlackhatASIA'24]** Confused Learning: Supply Chain Attacks through Machine Learning Models [[Link]](https://www.blackhat.com/asia-24/briefings/schedule/index.html#confused-learning-supply-chain-attacks-through-machine-learning-models-37794) [[Slides]](https://i.blackhat.com/Asia-24/Presentations/Asia-24-Wood-Confused-Learning.pdf?_gl=1*xwt703*_gcl_au*MjEyNjc0MzYwNC4xNzMxMTM3MDA2*_ga*MTM5MTcwNjc4OS4xNzMxMTM3MDA2*_ga_K4JK67TFYV*MTczMTEzNzAwNi4xLjEuMTczMTEzODExMy4wLjAuMA..&_ga=2.160178365.1863731842.1731137007-1391706789.1731137006)

- **[BlackhatASIA'24]** How to Make Hugging Face to Hug Worms: Discovering and Exploiting Unsafe Pickle.loads over Pre-Trained Large Model Hubs [[Link]](https://www.blackhat.com/asia-24/briefings/schedule/index.html#how-to-make-hugging-face-to-hug-worms-discovering-and-exploiting-unsafe-pickleloads-over-pre-trained-large-model-hubs-36261) [[Slides]](https://i.blackhat.com/Asia-24/Presentations/Asia-24-Zhou-HowtoMakeHuggingFace.pdf?_gl=1*ymvfd9*_gcl_au*MjEyNjc0MzYwNC4xNzMxMTM3MDA2*_ga*MTM5MTcwNjc4OS4xNzMxMTM3MDA2*_ga_K4JK67TFYV*MTczMTEzNzAwNi4xLjEuMTczMTEzODIzNi4wLjAuMA..&_ga=2.51586089.1863731842.1731137007-1391706789.1731137006)

- **[AIVillage@Defcon'31]** Assessing the Vulnerabilities of the Open-Source Artificial Intelligence (AI) Landscape: A Large-Scale Analysis of the Hugging Face Platform [[Slides]](https://aivillage.org/assets/AIVDC31/DSAIL%20DEFCON%20AI%20Village.pdf)

- **[AIVillage@Defcon'31]** You Sound Confused, Anyways - Thanks for The Jewels [[Slides]](https://aivillage.org/assets/AIVDC31/AIVDC31.pdf)

## Security Reports

- Machine Learning Bug Bonanza – Exploiting ML Services [[Link](https://jfrog.com/blog/machine-learning-bug-bonanza-exploiting-ml-services/)]

- Machine Learning Bug Bonanza – Exploiting ML Clients and “Safe” Model Formats [[Link](https://jfrog.com/blog/machine-learning-bug-bonanza-exploiting-ml-clients-and-safe-models/)]

- Offensive ML Playbook [[Link]](https://wiki.offsecml.com/Welcome+to+the+Offensive+ML+Playbook)

- OWASP Top 10 for LLMs [[Link]](https://owasp.org/www-project-top-10-for-large-language-model-applications/assets/PDF/OWASP-Top-10-for-LLMs-2023-v1_1.pdf)

- Wiz Research finds architecture risks that may compromise AI-as-a-Service providers and consequently risk customer data; works with Hugging Face on mitigations [[Link]](https://www.wiz.io/blog/wiz-and-hugging-face-address-risks-to-ai-infrastructure)

- The risk in malicious AI models: Wiz Research discovers critical vulnerability in AI-as-a-Service provider, Replicate [[Link]](https://www.wiz.io/blog/wiz-research-discovers-critical-vulnerability-in-replicate)

- Data Scientists Targeted by Malicious Hugging Face ML Models with Silent Backdoor [[Link]](https://jfrog.com/blog/data-scientists-targeted-by-malicious-hugging-face-ml-models-with-silent-backdoor/)

- From MLOps to MLOops: Exposing the Attack Surface of Machine Learning Platforms [[Link]](https://jfrog.com/blog/from-mlops-to-mloops-exposing-the-attack-surface-of-machine-learning-platforms/)

- Legit Discovers "AI Jacking" Vulnerability in Popular Hugging Face AI Platform [[Link]](https://www.legitsecurity.com/blog/tens-of-thousands-of-developers-were-potentially-impacted-by-the-hugging-face-aijacking-attack)

- Diving Deeper into AI Package Hallucinations [[Link]](https://www.lasso.security/blog/ai-package-hallucinations)

- +1500 HuggingFace API Tokens were exposed, leaving millions of Meta-Llama, Bloom, and Pythia users vulnerable [[Link]](https://www.lasso.security/blog/1500-huggingface-api-tokens-were-exposed-leaving-millions-of-meta-llama-bloom-and-pythia-users-for-supply-chain-attacks)

- More Models, More ProbLLMs [[Link]](https://www.oligo.security/blog/more-models-more-probllms)

- Shelltorch Explained: Multiple Vulnerabilities in Pytorch Model Server [[Link]](https://www.oligo.security/blog/shelltorch-explained-multiple-vulnerabilities-in-pytorch-model-server)

- Anatomy of an LLM RCE [[Link]](https://www.cyberark.com/resources/threat-research-blog/anatomy-of-an-llm-rce)

- 老树开新花：大模型时代的代码执行沙箱 [[Link]](https://mp.weixin.qq.com/s/X54d0foyBS56lGFUPyOvTw)

- 警惕Hugging Face开源组件风险被利用于大模型供应链攻击 [[Link]](https://security.tencent.com/index.php/blog/msg/209)

## CVEs

- **[CVE-2024-34359]** Supply-Chain Attacks in LLMs: From GGUF model format metadata RCE, to State-of-The-Art NLP Project RCEs [[Link]](https://0reg.dev/blog/from-gguf-model-format-metadata-rce-to-state-of-the-art-nlp-project-rces)

- **[CVE-2024-3660]** Keras 2 Lambda Layers Allow Arbitrary Code Injection in TensorFlow Models [[Link]](https://kb.cert.org/vuls/id/253266)

- **[CVE-2023-48022]** The story of ShadowRay [[Link]](https://www.vicarius.io/vsociety/posts/the-story-of-shadowray-cve-2023-48022)

- **[CVE-2023-49785]** Hacking AI Chatbots for fun and learning - Analyzing an unauthenticated SSRF and reflected XSS in ChatGPT-Next-Web (CVE-2023-49785) [[Link]](https://www.vicarius.io/vsociety/posts/hacking-ai-chatbots-for-fun-and-learning-analyzing-an-unauthenticated-ssrf-and-reflected-xss-in-chatgpt-next-web-cve-2023-49785)
to be continued...

## Contribution

Any contribution to make this list more comprehensive (adding papers, talks, reports, and CVEs etc.) is always welcome. Please feel free to open an issue or a PR.