<h1 align="center">Awesome Agent Security Research</h1>

<p align="center">A curated, daily-updated list of research papers on the security of AI agents.</p>

<p align="center">
<img src="https://img.shields.io/badge/papers-86-2da44e" alt="papers">
<img src="https://img.shields.io/badge/peer--reviewed-64-d1242f" alt="peer-reviewed">
<img src="https://img.shields.io/badge/benchmarks-6-8250df" alt="benchmarks">
<img src="https://img.shields.io/badge/years-2024--2027-0969da" alt="years">
</p>

## How to read

Every entry starts with a badge that shows **where and when** the paper appeared, followed by the title (linked to the paper) and the authors. Within each topic, papers are grouped by year, newest first.

| Badge | Meaning |
|---|---|
| ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) | Security venues: S&P, USENIX Security, CCS, NDSS |
| ![ICSE 2026](https://img.shields.io/badge/ICSE-2026-24292f?labelColor=0969da&style=flat-square) | Software engineering venues: ICSE, FSE, ASE, ISSTA, TOSEM |
| ![ICLR Workshop 2026](https://img.shields.io/badge/ICLR%20Workshop-2026-24292f?labelColor=8250df&style=flat-square) | Other venues |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) | Preprints |

`Analysis` after the authors links to our write-up of the paper (in Chinese).

## Contents

| Topic | Papers | Scope |
|---|---|---|
| [Benchmarks](#benchmarks) | 6 | Benchmarks and datasets for evaluating agent security. |
| [Agent Skills and Plugin Ecosystems](#agent-skills-and-plugin-ecosystems) | 11 | Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege. |
| [MCP and Tool Chains](#mcp-and-tool-chains) | 10 | Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies. |
| [Agent Applications and Frameworks](#agent-applications-and-frameworks) | 19 | Vulnerabilities in agent and LLM-integrated applications, agent frameworks, LLM app stores, and multi-agent systems. |
| [Prompt Injection, Guardrails, and Permissions](#prompt-injection-guardrails-and-permissions) | 24 | Prompt injection attacks and defenses, runtime guardrails, isolation architectures, and permission models. |
| [Agents on the Web and Privacy](#agents-on-the-web-and-privacy) | 11 | Web and mobile agents, agents misused as attackers, detecting and deterring agents, content manipulation, and privacy leakage. |
| [Surveys and SoKs](#surveys-and-soks) | 5 | Surveys, systematizations, and literature reviews of agent security. |

## Benchmarks

> Benchmarks and datasets for evaluating agent security.

### 2026

- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents](https://arxiv.org/abs/2609.13873)**<br><sub>Qihang Cen, Tianshuo Cong, Da Song, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-primobibench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **SkillVetBench: [Benchmarking Security Risk Detection and Verification in Open Agentic Skill Ecosystems](https://arxiv.org/abs/2606.00925)**<br><sub>Ismail Hossain, Sai Puppala, Zhuoran Lu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillvetbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **DTap-Bench: [DecodingTrust-Agent Platform (DTap): A Controllable and Interactive Red-Teaming Platform for AI Agents](https://arxiv.org/abs/2605.04808)**<br><sub>Zhaorun Chen, Xun Liu, Haibo Tong, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-dtap/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[HarmfulSkillBench: How Do Harmful Skills Weaponize Your Agents?](https://arxiv.org/abs/2604.15415)**<br><sub>Yukun Jiang, Yage Zhang, Michael Backes, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-harmfulskillbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[MalSkillBench: A Runtime-Verified Benchmark of Malicious Agent Skills](https://arxiv.org/abs/2606.07131)**<br><sub>Wenbo Guo, Wei Zeng, Chengwei Liu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskillbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[SkillSafetyBench: Evaluating Agent Safety under Skill-Facing Attack Surfaces](https://arxiv.org/abs/2605.12015)**<br><sub>Chang Jin, An Wang, Zeming Wei, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillsafetybench/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agent Skills and Plugin Ecosystems

> Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege.

### 2026

- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **["Elementary, My Dear Watson." Detecting Malicious Skills via Neuro-Symbolic Reasoning across Heterogeneous Artifacts](https://arxiv.org/abs/2603.27204)**<br><sub>Shenao Wang, Junjie He, Yanjie Zhao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskills-neurosymbolic/article.md)</sub>
- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **[How Your Credentials Are Leaked by LLM Agent Skills: An Empirical Study](https://arxiv.org/abs/2604.03070)**<br><sub>Zhihao Chen, Ying Zhang, Yi Liu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skill-credential-leak/article.md)</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[SkillScope: Toward Fine-Grained Least-Privilege Enforcement for Agent Skills](https://arxiv.org/abs/2605.05868)**<br><sub>Jiangrong Wu, Yuhong Nan, Yixi Lin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-skillscope/article.md)</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **["Do Not Mention This to the User": Detecting and Understanding Malicious Agent Skills in the Wild](https://arxiv.org/abs/2602.06547)**<br><sub>Yi Liu, Zhihao Chen, Yanjun Zhang, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malicious-skills-wild/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[A Comprehensive Survey on Agent Skills: Taxonomy, Techniques, and Applications](https://arxiv.org/abs/2605.07358)**<br><sub>Yingli Zhou, Wang Shu, Yaodong Su, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skills-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale](https://arxiv.org/abs/2601.10338)**<br><sub>Yi Liu, Weizhe Wang, Ruitao Feng, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skills-wild-vulns/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[ColluSkill: Adversarial Cross-Skill Composition for Evading Agent Skill Scanners](https://arxiv.org/abs/2608.09732)**<br><sub>Puyu Zeng, Simeng Qin, Jingzhi Li, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-colluskill/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[JailbreakSkill: Scaling Automated Red-Teaming with Reusable and Ever-Evolving Skills](https://arxiv.org/abs/2608.16465)**<br><sub>Xiaoyu Wen, Jiajia Li, Zhida He, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-jailbreakskill/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Skills That Don't Exist: A Large-Scale Study of Hallucinated Skill Recommendation in LLM Agents](https://arxiv.org/abs/2607.12340)**<br><sub>Weifeng Yuan, Wenbo Guo, Feng Dong, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-hallucinated-skills/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Towards Secure Agent Skills: Architecture, Threat Taxonomy, and Security Analysis](https://arxiv.org/abs/2604.02837)**<br><sub>Zhiyuan Li, Jingzheng Wu, Xiang Ling, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-secure-agent-skills-sok/article.md)</sub>

### 2025

- ![CAMLIS 2025](https://img.shields.io/badge/CAMLIS-2025-24292f?labelColor=8250df&style=flat-square) **[Agent Skill Security: Threat Models, Attacks, Defenses, and Evaluation](https://arxiv.org/abs/2607.13987)**<br><sub>Sanket Badhe, Priyanka Tiwari &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skill-security-tmade/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## MCP and Tool Chains

> Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies.

### 2026

- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[ContractGuard: Auditing Semantic Contracts of MCP Tools for Security Violations](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)**<br><sub>Hengkai Ye, Zhechang Zhang, Ruibo Lu, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[MetaMancer: Practical Tool Selection Attacks against LLM Agents](https://doi.org/10.1145/3830454.3846793)**<br><sub>Wenbin Zhai, Yihao Liu, Dong Wang, et al.</sub>
- ![FSE 2026](https://img.shields.io/badge/FSE-2026-24292f?labelColor=0969da&style=flat-square) **[AgentBound: Securing Execution Boundaries of AI Agents](https://doi.org/10.1145/3808103)**<br><sub>Christoph Bühler, Matteo Biagiola, Luca Di Grazia, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://arxiv.org/abs/2504.03111)**<br><sub>Zichuan Li, Jian Cui, Xiaojing Liao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-les-dissonances/article.md)</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[Prompt Injection Attack to Tool Selection in LLM Agents](https://doi.org/10.14722/ndss.2026.230675)**<br><sub>Jiawen Shi, Zenghui Yuan, Guiyao Tie, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[Parasites in the Toolchain: A Large-Scale Analysis of Attacks on the MCP Ecosystem](https://arxiv.org/abs/2509.06572)**<br><sub>Shuli Zhao, Qinsheng Hou, Zihan Zhan, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-mcp-parasites/article.md)</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[When AI Meets the Web: Prompt Injection Risks in Third-Party AI Chatbot Plugins](https://arxiv.org/abs/2511.05797)**<br><sub>Yigitcan Kaya, Anton Landerer, Stijn Pletinckx, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-chatbot-plugins/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[AGENTFLOW: Building Agent Dependency Graphs for Static Analysis of Agent Programs](https://arxiv.org/abs/2607.01640)**<br><sub>Shenao Wang, Xinyi Hou, Yanjie Zhao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentflow-adg/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Characterizing LLM Agent Behaviors in Module Shadowing Environments](https://arxiv.org/abs/2610.40716)**<br><sub>Shuai Yang, Enmeng Lu, Jinyu Fan, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-module-shadowing/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Characterizing Security Effects of OSS Vulnerabilities in Agent Systems](https://arxiv.org/abs/2610.05036)**<br><sub>Yu Ji, Yang Wei, Yutao Hu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-oss-vuln-agent/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agent Applications and Frameworks

> Vulnerabilities in agent and LLM-integrated applications, agent frameworks, LLM app stores, and multi-agent systems.

### 2027

- ![ICSE 2027](https://img.shields.io/badge/ICSE-2027-24292f?labelColor=0969da&style=flat-square) **[Automated Safety Analysis for Agentic Workflows](https://arxiv.org/abs/2611.28469)**<br><sub>Yanju Chen, Ying Li, Bosi Zhang, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-apsis/article.md)</sub>

### 2026

- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **[What Breaks When LLMs Code? Characterizing Operational Safety Failures of Agentic Code Assistants](https://arxiv.org/abs/2605.30777)**<br><sub>Alif Al Hasan, Sumon Biswas</sub>
- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **[When Compression Becomes an Attack Surface: Black-Box Attacks on Prompt-Compressed LLM Agents](https://arxiv.org/abs/2510.22963)**<br><sub>Zesen Liu, Zhixiang Zhang, Yuchong Xie, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[Comment and Control: Hijacking Agentic Workflows via Context-Grounded Evolution](https://arxiv.org/abs/2605.11229)**<br><sub>Neil Fendley, Zhengyu Liu, Aonan Guan, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[Janus: Characterizing Bidirectional Privacy and Security Risks in LLM-Integrated Android Apps](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)**<br><sub>Jiawei Guo, Zongze Li, Haipeng Cai</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[MemPoison: Bypassing Selective Memory Mechanisms to Plant Backdoors in LLM Agents](https://arxiv.org/abs/2605.29960)**<br><sub>Hongtao Wang, Se Yang, Yu Chen, et al.</sub>
- ![ICSE 2026](https://img.shields.io/badge/ICSE-2026-24292f?labelColor=0969da&style=flat-square) **[TaintP2X: Detecting Taint-Style Prompt-to-Anything Injection Vulnerabilities in LLM-Integrated Applications](https://conf.researchr.org/track/icse-2026/icse-2026-research-track#event-overview)**<br><sub>Junjie He, Shenao Wang, Yanjie Zhao, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[Beyond Jailbreak: Unveiling Risks in LLM Applications Arising from Blurred Capability Boundaries](https://doi.org/10.14722/ndss.2026.242941)**<br><sub>Yunyi Zhang, Shibo Cui, Baojun Liu, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[LLMThief: Evaluating Configuration Leaking Risks in Commercial LLM App Stores](https://doi.org/10.1109/sp63933.2026.00195)**<br><sub>Pinji Chen, Jinlong Jiang, Jianjun Chen, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity26/presentation/luo)**<br><sub>Jiaqi Luo, Jiarun Dai, Fengyu Liu, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[MASLeak: Investigating and Exposing Intellectual Property Leakage Vulnerabilities in Multi-Agent Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/wang-liwen)**<br><sub>Liwen Wang, Wenxuan Wang, Shuai Wang, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[When AIOps Become "AI Oops": Subverting LLM-driven IT Operations via Telemetry Manipulation](https://www.usenix.org/conference/usenixsecurity26/presentation/pasquini)**<br><sub>Dario Pasquini, Evgenios M. Kornaropoulos, Giuseppe Ateniese, et al.</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Coding Agents Propagate Vulnerabilities in Code Bases](https://arxiv.org/abs/2611.11455)**<br><sub>Chenhao Sun, Niels Mündler-Sasahara, Mark Vero, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-agents-propagate-vulns/article.md)</sub>

### 2025

- ![ASE 2025](https://img.shields.io/badge/ASE-2025-24292f?labelColor=0969da&style=flat-square) **[Security Debt in LLM Agent Applications: A Measurement Study of Vulnerabilities and Mitigation Trade-offs](https://doi.org/10.1109/ase63991.2025.00053)**<br><sub>Zhuoxiang Shen, Jiarun Dai, Yuan Zhang, et al.</sub>
- ![ICSE 2025](https://img.shields.io/badge/ICSE-2025-24292f?labelColor=0969da&style=flat-square) **[Prompt-to-SQL Injections in LLM-Integrated Web Applications: Risks and Defenses](https://doi.org/10.1109/icse55347.2025.00007)**<br><sub>Rodrigo Pedro, Miguel E. Coimbra, Daniel Castro, et al.</sub>
- ![S&P 2025](https://img.shields.io/badge/S%26P-2025-24292f?labelColor=d1242f&style=flat-square) **[GPTracker: A Large-Scale Measurement of Misused GPTs](https://doi.org/10.1109/sp61157.2025.00118)**<br><sub>Xinyue Shen, Shen Yun, Michael Backes, et al.</sub>
- ![S&P 2025](https://img.shields.io/badge/S%26P-2025-24292f?labelColor=d1242f&style=flat-square) **[On the (In)Security of LLM App Stores](https://doi.org/10.1109/sp61157.2025.00117)**<br><sub>Xinyi Hou, Yanjie Zhao, Haoyu Wang &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2025-08-llm-app-store-insecurity/article.md)</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/liu-fengyu)**<br><sub>Fengyu Liu, Yuan Zhang, Jiaqi Luo, et al.</sub>

### 2024

- ![CCS 2024](https://img.shields.io/badge/CCS-2024-24292f?labelColor=d1242f&style=flat-square) **[Demystifying RCE Vulnerabilities in LLM-Integrated Apps](https://doi.org/10.1145/3658644.3690338)**<br><sub>Tong Liu, Zizhuang Deng, Guozhu Meng, et al.</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Prompt Injection, Guardrails, and Permissions

> Prompt injection attacks and defenses, runtime guardrails, isolation architectures, and permission models.

### 2026

- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **[ProbGuard: Proactive Runtime Monitoring for LLM Agent Safety via Probabilistic Prediction](https://arxiv.org/abs/2508.00500)**<br><sub>Haoyu Wang, Chris Poskitt, Jiali Wei, et al.</sub>
- ![ASE 2026](https://img.shields.io/badge/ASE-2026-24292f?labelColor=0969da&style=flat-square) **[Safeguarding LLM Agents from Misalignment through Provenance Analysis](https://arxiv.org/abs/2607.01236)**<br><sub>Yining She, Yiliang Liang, Eunsuk Kang</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[DRIP: Defending Prompt Injection via Token-wise Representation Editing and Residual Fusion](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)**<br><sub>Ruofan Liu, Yun Lin, Zhiyong Huang, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[Governing AI Agent with Capability and Delegation Chain](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)**<br><sub>Jiaqin Yan, Guoxing Chen, Yan Meng, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[LocalAlign: Enabling Generalizable Prompt Injection Defense via Generation of Near-Target Adversarial Examples for Alignment Training](https://arxiv.org/abs/2605.01462)**<br><sub>Yuyang Gong, Zihao Wang, Jiawei Liu, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[MirrorGuard: Toward Secure Computer-Use Agents via Simulation-to-Real Reasoning Correction](https://arxiv.org/abs/2601.12822)**<br><sub>Wenqi Zhang, Yulin Shen, Changyue Jiang, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[Safeguarding LLM Agents against Long-Horizon Threats via Shadow Memory](https://arxiv.org/abs/2605.03228)**<br><sub>Yuhui Wang, Tanqiu Jiang, Jiacheng Liang, et al.</sub>
- ![ICSE 2026](https://img.shields.io/badge/ICSE-2026-24292f?labelColor=0969da&style=flat-square) **[AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents](https://arxiv.org/abs/2503.18666)**<br><sub>Haoyu Wang, Chris Poskitt, Jun Sun</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[ACE: A Security Architecture for LLM-Integrated App Systems](https://doi.org/10.14722/ndss.2026.230352)**<br><sub>Enlai Li, Tushin Mallick, Evan Rose, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[Attention is All You Need to Defend Against Indirect Prompt Injection Attacks in LLMs](https://doi.org/10.14722/ndss.2026.240394)**<br><sub>Yinan Zhong, Qianhao Miao, Yanjiao Chen, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data](https://doi.org/10.14722/ndss.2026.240702)**<br><sub>Reachal Wang, Yuqi Jia, Neil Zhenqiang Gong</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-24292f?labelColor=d1242f&style=flat-square) **[SAGA: A Security Architecture for Governing AI Agentic Systems](https://doi.org/10.14722/ndss.2026.230869)**<br><sub>Georgios Syros, Anshuman Suri, Jacob Ginesin, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[PromptLocate: Localizing Prompt Injection Attacks](https://doi.org/10.1109/sp63933.2026.00105)**<br><sub>Yuqi Jia, Yupei Liu, Zhujun Shao, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[Overcoming the Retrieval Barrier: Indirect Prompt Injection in the Wild for LLM Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/chang-hongyan)**<br><sub>Hongyan Chang, Ergute Bao, Xinjian Luo, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections](https://arxiv.org/abs/2510.09023)**<br><sub>Milad Nasr, Nicholas Carlini, Chawin Sitawarin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-attacker-moves-second/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695)**<br><sub>Wenhao Lin, Chenyu Yu, Xingwei Lin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-dreamguard/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[How Agents Ask for Permission: User Permissions for AI Agents, from Interfaces to Enforcement](https://arxiv.org/abs/2607.13718)**<br><sub>Alexandra E. Michael, Franziska Roesner &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-permissions/article.md)</sub>

### 2025

- ![CCS 2025](https://img.shields.io/badge/CCS-2025-24292f?labelColor=d1242f&style=flat-square) **[AgentSentinel: An End-to-End and Real-Time Security Defense Framework for Computer-Use Agents](https://doi.org/10.1145/3719027.3765064)**<br><sub>Hu Haitao, Peng Chen, Yanpeng Zhao, et al.</sub>
- ![NDSS 2025](https://img.shields.io/badge/NDSS-2025-24292f?labelColor=d1242f&style=flat-square) **[IsolateGPT: An Execution Isolation Architecture for LLM-Based Systems](https://doi.org/10.14722/ndss.2025.241131)**<br><sub>Yuhao Wu, Franziska Roesner, Tadayoshi Kohno, et al.</sub>
- ![S&P 2025](https://img.shields.io/badge/S%26P-2025-24292f?labelColor=d1242f&style=flat-square) **[DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks](https://doi.org/10.1109/sp61157.2025.00250)**<br><sub>Yupei Liu, Yuqi Jia, Jinyuan Jia, et al.</sub>
- ![S&P 2025](https://img.shields.io/badge/S%26P-2025-24292f?labelColor=d1242f&style=flat-square) **[Fun-tuning: Characterizing the Vulnerability of Proprietary LLMs to Optimization-Based Prompt Injection Attacks via the Fine-Tuning Interface](https://doi.org/10.1109/sp61157.2025.00121)**<br><sub>Andrey Labunets, Nishit V. Pandya, Ashish Hooda, et al.</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[StruQ: Defending Against Prompt Injection with Structured Queries](https://www.usenix.org/conference/usenixsecurity25/presentation/chen-sizhe)**<br><sub>Sizhe Chen, Julien Piet, Chawin Sitawarin, et al.</sub>

### 2024

- ![CCS 2024](https://img.shields.io/badge/CCS-2024-24292f?labelColor=d1242f&style=flat-square) **[AirGapAgent: Protecting Privacy-Conscious Conversational Agents](https://doi.org/10.1145/3658644.3690350)**<br><sub>Eugene Bagdasarian, Ren Yi, Sahra Ghalebikesabi, et al.</sub>
- ![USENIX Security 2024](https://img.shields.io/badge/USENIX%20Security-2024-24292f?labelColor=d1242f&style=flat-square) **[Formalizing and Benchmarking Prompt Injection Attacks and Defenses](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-yupei)**<br><sub>Yupei Liu, Yuqi Jia, Runpeng Geng, et al.</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agents on the Web and Privacy

> Web and mobile agents, agents misused as attackers, detecting and deterring agents, content manipulation, and privacy leakage.

### 2027

- ![S&P 2027](https://img.shields.io/badge/S%26P-2027-24292f?labelColor=d1242f&style=flat-square) **[AgentShield: Fortifying Web Applications Against AI Agents and Agentic Browsers](https://arxiv.org/abs/2610.41181)**<br><sub>Moiz Ali, Nafis Karim, Rownak Islam, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-agentshield/article.md)</sub>

### 2026

- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[A Large-scale Measurement of In-Page Prompt Injections Against LLM Web Agents](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)**<br><sub>Soheil Khodayari, Xuenan Zhang, Bhupendra Acharya, et al.</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-24292f?labelColor=d1242f&style=flat-square) **[Mind the Gap: Action Rebinding Attacks against Android GUI Agents](https://arxiv.org/abs/2601.12349)**<br><sub>Yi Qian, Kunwei Qian, Xingbang He, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[Investigating the Impact of Dark Patterns on LLM-Based Web Agents](https://doi.org/10.1109/sp63933.2026.00042)**<br><sub>Devin Ersoy, Brandon Lee, Ananth Shreekumar, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-24292f?labelColor=d1242f&style=flat-square) **[WebCloak: Characterizing and Mitigating Threats From LLM-Driven Web Agents as Intelligent Scrapers](https://doi.org/10.1109/sp63933.2026.00025)**<br><sub>Xinfeng Li, Tianze Qiu, Yingbin Jin, et al.</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[GEOHunter: Mapping a Generative Engine Optimization Network in the Wild](https://arxiv.org/abs/2611.26564)**<br><sub>Sean Tang, Peiran Wang, Ying Li, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-geohunter/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[Say Shibboleth: Fingerprinting the LLMs and Harnesses Behind Agentic Attacks](https://arxiv.org/abs/2611.12386)**<br><sub>Dario Pasquini, Reworr, Giuseppe Ateniese, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-shibboleth/article.md)</sub>

### 2025

- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[Are CAPTCHAs Still Bot-hard? Generalized Visual CAPTCHA Solving with Agentic Vision Language Model](https://www.usenix.org/conference/usenixsecurity25/presentation/teoh)**<br><sub>Xiwen Teoh, Yun Lin, Siqi Li, et al.</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[Big Help or Big Brother? Auditing Tracking, Profiling, and Personalization in Generative AI Assistants](https://www.usenix.org/conference/usenixsecurity25/presentation/vekaria)**<br><sub>Yash Vekaria, Aurelio Loris Canino, Jonathan Levitsky, et al.</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[Cloak, Honey, Trap: Proactive Defenses Against LLM Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn)**<br><sub>Daniel Ayzenshteyn, Roy Weiss, Yisroel Mirsky</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-24292f?labelColor=d1242f&style=flat-square) **[When LLMs Go Online: The Emerging Threat of Web-Enabled LLMs](https://www.usenix.org/conference/usenixsecurity25/presentation/kim-hanna)**<br><sub>Hanna Kim, Minkyoo Song, Seung Ho Na, et al.</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Surveys and SoKs

> Surveys, systematizations, and literature reviews of agent security.

### 2026

- ![TOSEM 2026](https://img.shields.io/badge/TOSEM-2026-24292f?labelColor=0969da&style=flat-square) **[Navigating the Risks: A Survey of Security and Privacy Threats in LLM-Based Agents](https://doi.org/10.1145/3807666)**<br><sub>Yuyou Gan, Yong Yang, Zhe Ma, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-05-llm-agent-threat-survey/article.md)</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-24292f?labelColor=d1242f&style=flat-square) **[The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey](https://arxiv.org/abs/2603.11088)**<br><sub>Juhee Kim, Xiaoyuan Liu, Zhun Wang, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-ai-survey/article.md)</sub>
- ![Preprint 2026](https://img.shields.io/badge/Preprint-2026-24292f?labelColor=8b949e&style=flat-square) **[Behavior Safety of Autonomous Interactive Agents: Risks, Attacks, Defenses and Evaluation](https://github.com/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents)**<br><sub>Xinjie Lai, Weihao Zuo, Zheng Wu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-behavior-safety-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445)**<br><sub>Asif Shahriar, Md Nafiu Rahman, Sadif Ahmed, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-security-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-24292f?labelColor=8b949e&style=flat-square) **[A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338)**<br><sub>Kexin Chu &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-lasm-survey/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Contributing

Missing a paper? Open an issue or a pull request with the title, authors, venue, and link.
