<h1 align="center">Awesome Agent Security Research</h1>

<p align="center">A curated, daily-updated list of research papers on the security of AI agents.</p>

<p align="center">
<img src="https://img.shields.io/badge/papers-55-2da44e" alt="papers">
<img src="https://img.shields.io/badge/peer--reviewed-32-d1242f" alt="peer-reviewed">
<img src="https://img.shields.io/badge/benchmarks-5-8250df" alt="benchmarks">
<img src="https://img.shields.io/badge/years-2024--2027-0969da" alt="years">
</p>

## How to read

Every entry starts with a badge that shows **where and when** the paper appeared, followed by the title (linked to the paper) and the authors. Within each topic, papers are grouped by year, newest first.

| Badge | Meaning |
|---|---|
| ![S&P 2026](https://img.shields.io/badge/S%26P-2026-d1242f) | Security venues: S&P, USENIX Security, CCS, NDSS |
| ![ICSE 2026](https://img.shields.io/badge/ICSE-2026-0969da) | Software engineering venues: ICSE, FSE, ASE, ISSTA, TOSEM |
| ![ICLR Workshop 2026](https://img.shields.io/badge/ICLR%20Workshop-2026-8250df) | Other venues |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) | Preprints |

`Analysis` after the authors links to our write-up of the paper (in Chinese).

## Contents

| Topic | Papers | Scope |
|---|---|---|
| [Benchmarks](#benchmarks) | 5 | Benchmarks and datasets for evaluating agent security. |
| [Agent Skills and Plugin Ecosystems](#agent-skills-and-plugin-ecosystems) | 11 | Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege. |
| [MCP and Tool Chains](#mcp-and-tool-chains) | 8 | Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies. |
| [Agent Applications and Frameworks](#agent-applications-and-frameworks) | 6 | Vulnerabilities in agent applications, agent frameworks, and multi-agent systems. |
| [Prompt Injection, Guardrails, and Permissions](#prompt-injection-guardrails-and-permissions) | 11 | Prompt injection attacks and defenses, runtime guardrails, isolation architectures, and permission models. |
| [Agents on the Web and Privacy](#agents-on-the-web-and-privacy) | 7 | Web and mobile agents, detecting and deterring agents, content manipulation, and privacy leakage. |
| [Surveys and SoKs](#surveys-and-soks) | 7 | Surveys, systematizations, and literature reviews of agent security. |

## Benchmarks

> Benchmarks and datasets for evaluating agent security.

### 2026

- ![CCS 2026](https://img.shields.io/badge/CCS-2026-d1242f) **[PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents](https://arxiv.org/abs/2609.13873)**<br><sub>Qihang Cen, Tianshuo Cong, Da Song, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-primobibench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **SkillVetBench: [Benchmarking Security Risk Detection and Verification in Open Agentic Skill Ecosystems](https://arxiv.org/abs/2606.00925)**<br><sub>Ismail Hossain, Sai Puppala, Zhuoran Lu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillvetbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[HarmfulSkillBench: How Do Harmful Skills Weaponize Your Agents?](https://arxiv.org/abs/2604.15415)**<br><sub>Yukun Jiang, Yage Zhang, Michael Backes, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-harmfulskillbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[MalSkillBench: A Runtime-Verified Benchmark of Malicious Agent Skills](https://arxiv.org/abs/2606.07131)**<br><sub>Wenbo Guo, Wei Zeng, Chengwei Liu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskillbench/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[SkillSafetyBench: Evaluating Agent Safety under Skill-Facing Attack Surfaces](https://arxiv.org/abs/2605.12015)**<br><sub>Chang Jin, An Wang, Zeming Wei, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillsafetybench/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agent Skills and Plugin Ecosystems

> Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege.

### 2026

- ![ASE 2026](https://img.shields.io/badge/ASE-2026-0969da) **[How Your Credentials Are Leaked by LLM Agent Skills: An Empirical Study](https://arxiv.org/abs/2604.03070)**<br><sub>Zhihao Chen, Ying Zhang, Yi Liu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skill-credential-leak/article.md)</sub>
- ![CCS 2026](https://img.shields.io/badge/CCS-2026-d1242f) **[SkillScope: Toward Fine-Grained Least-Privilege Enforcement for Agent Skills](https://arxiv.org/abs/2605.05868)**<br><sub>Jiangrong Wu, Yuhong Nan, Yixi Lin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-skillscope/article.md)</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **["Do Not Mention This to the User": Detecting and Understanding Malicious Agent Skills in the Wild](https://arxiv.org/abs/2602.06547)**<br><sub>Yi Liu, Zhihao Chen, Yanjun Zhang, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malicious-skills-wild/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **["Elementary, My Dear Watson." Detecting Malicious Skills via Neuro-Symbolic Reasoning across Heterogeneous Artifacts](https://arxiv.org/abs/2603.27204)**<br><sub>Shenao Wang, Junjie He, Yanjie Zhao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskills-neurosymbolic/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[A Comprehensive Survey on Agent Skills: Taxonomy, Techniques, and Applications](https://arxiv.org/abs/2605.07358)**<br><sub>Yingli Zhou, Wang Shu, Yaodong Su, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skills-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale](https://arxiv.org/abs/2601.10338)**<br><sub>Yi Liu, Weizhe Wang, Ruitao Feng, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skills-wild-vulns/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[ColluSkill: Adversarial Cross-Skill Composition for Evading Agent Skill Scanners](https://arxiv.org/abs/2608.09732)**<br><sub>Puyu Zeng, Simeng Qin, Jingzhi Li, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-colluskill/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[JailbreakSkill: Scaling Automated Red-Teaming with Reusable and Ever-Evolving Skills](https://arxiv.org/abs/2608.16465)**<br><sub>Xiaoyu Wen, Jiajia Li, Zhida He, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-jailbreakskill/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Skills That Don't Exist: A Large-Scale Study of Hallucinated Skill Recommendation in LLM Agents](https://arxiv.org/abs/2607.12340)**<br><sub>Weifeng Yuan, Wenbo Guo, Feng Dong, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-hallucinated-skills/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Towards Secure Agent Skills: Architecture, Threat Taxonomy, and Security Analysis](https://arxiv.org/abs/2604.02837)**<br><sub>Zhiyuan Li, Jingzheng Wu, Xiang Ling, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-secure-agent-skills-sok/article.md)</sub>

### 2025

- ![CAMLIS 2025](https://img.shields.io/badge/CAMLIS-2025-8250df) **[Agent Skill Security: Threat Models, Attacks, Defenses, and Evaluation](https://arxiv.org/abs/2607.13987)**<br><sub>Sanket Badhe, Priyanka Tiwari &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skill-security-tmade/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## MCP and Tool Chains

> Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies.

### 2026

- ![FSE 2026](https://img.shields.io/badge/FSE-2026-0969da) **[AgentBound: Securing Execution Boundaries of AI Agents](https://doi.org/10.1145/3808103)**<br><sub>Christoph Bühler, Matteo Biagiola, Luca Di Grazia, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://arxiv.org/abs/2504.03111)**<br><sub>Zichuan Li, Jian Cui, Xiaojing Liao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-les-dissonances/article.md)</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[Prompt Injection Attack to Tool Selection in LLM Agents](https://doi.org/10.14722/ndss.2026.230675)**<br><sub>Jiawen Shi, Zenghui Yuan, Guiyao Tie, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-d1242f) **[Parasites in the Toolchain: A Large-Scale Analysis of Attacks on the MCP Ecosystem](https://arxiv.org/abs/2509.06572)**<br><sub>Shuli Zhao, Qinsheng Hou, Zihan Zhan, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-mcp-parasites/article.md)</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-d1242f) **[When AI Meets the Web: Prompt Injection Risks in Third-Party AI Chatbot Plugins](https://arxiv.org/abs/2511.05797)**<br><sub>Yigitcan Kaya, Anton Landerer, Stijn Pletinckx, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-chatbot-plugins/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[AGENTFLOW: Building Agent Dependency Graphs for Static Analysis of Agent Programs](https://arxiv.org/abs/2607.01640)**<br><sub>Shenao Wang, Xinyi Hou, Yanjie Zhao, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentflow-adg/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Characterizing LLM Agent Behaviors in Module Shadowing Environments](https://arxiv.org/abs/2610.40716)**<br><sub>Shuai Yang, Enmeng Lu, Jinyu Fan, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-module-shadowing/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Characterizing Security Effects of OSS Vulnerabilities in Agent Systems](https://arxiv.org/abs/2610.05036)**<br><sub>Yu Ji, Yang Wei, Yutao Hu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-oss-vuln-agent/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agent Applications and Frameworks

> Vulnerabilities in agent applications, agent frameworks, and multi-agent systems.

### 2026

- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **[Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity26/presentation/luo)**<br><sub>Jiaqi Luo, Jiarun Dai, Fengyu Liu, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **[MASLeak: Investigating and Exposing Intellectual Property Leakage Vulnerabilities in Multi-Agent Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/wang-liwen)**<br><sub>Liwen Wang, Wenxuan Wang, Shuai Wang, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **[When AIOps Become "AI Oops": Subverting LLM-driven IT Operations via Telemetry Manipulation](https://www.usenix.org/conference/usenixsecurity26/presentation/pasquini)**<br><sub>Dario Pasquini, Evgenios M. Kornaropoulos, Giuseppe Ateniese, et al.</sub>

### 2025

- ![ASE 2025](https://img.shields.io/badge/ASE-2025-0969da) **[Security Debt in LLM Agent Applications: A Measurement Study of Vulnerabilities and Mitigation Trade-offs](https://doi.org/10.1109/ase63991.2025.00053)**<br><sub>Zhuoxiang Shen, Jiarun Dai, Yuan Zhang, et al.</sub>
- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-d1242f) **[Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/liu-fengyu)**<br><sub>Fengyu Liu, Yuan Zhang, Jiaqi Luo, et al.</sub>

### 2024

- ![CCS 2024](https://img.shields.io/badge/CCS-2024-d1242f) **[Demystifying RCE Vulnerabilities in LLM-Integrated Apps](https://doi.org/10.1145/3658644.3690338)**<br><sub>Tong Liu, Zizhuang Deng, Guozhu Meng, et al.</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Prompt Injection, Guardrails, and Permissions

> Prompt injection attacks and defenses, runtime guardrails, isolation architectures, and permission models.

### 2026

- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[ACE: A Security Architecture for LLM-Integrated App Systems](https://doi.org/10.14722/ndss.2026.230352)**<br><sub>Enlai Li, Tushin Mallick, Evan Rose, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[Attention is All You Need to Defend Against Indirect Prompt Injection Attacks in LLMs](https://doi.org/10.14722/ndss.2026.240394)**<br><sub>Yinan Zhong, Qianhao Miao, Yanjiao Chen, et al.</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data](https://doi.org/10.14722/ndss.2026.240702)**<br><sub>Reachal Wang, Yuqi Jia, Neil Zhenqiang Gong</sub>
- ![NDSS 2026](https://img.shields.io/badge/NDSS-2026-d1242f) **[SAGA: A Security Architecture for Governing AI Agentic Systems](https://doi.org/10.14722/ndss.2026.230869)**<br><sub>Georgios Syros, Anshuman Suri, Jacob Ginesin, et al.</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **[The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections](https://arxiv.org/abs/2510.09023)**<br><sub>Milad Nasr, Nicholas Carlini, Chawin Sitawarin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-attacker-moves-second/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695)**<br><sub>Wenhao Lin, Chenyu Yu, Xingwei Lin, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-dreamguard/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[How Agents Ask for Permission: User Permissions for AI Agents, from Interfaces to Enforcement](https://arxiv.org/abs/2607.13718)**<br><sub>Alexandra E. Michael, Franziska Roesner &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-permissions/article.md)</sub>

### 2025

- ![CCS 2025](https://img.shields.io/badge/CCS-2025-d1242f) **[AgentSentinel: An End-to-End and Real-Time Security Defense Framework for Computer-Use Agents](https://doi.org/10.1145/3719027.3765064)**<br><sub>Hu Haitao, Peng Chen, Yanpeng Zhao, et al.</sub>
- ![NDSS 2025](https://img.shields.io/badge/NDSS-2025-d1242f) **[IsolateGPT: An Execution Isolation Architecture for LLM-Based Systems](https://doi.org/10.14722/ndss.2025.241131)**<br><sub>Yuhao Wu, Franziska Roesner, Tadayoshi Kohno, et al.</sub>
- ![S&P 2025](https://img.shields.io/badge/S%26P-2025-d1242f) **[DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks](https://doi.org/10.1109/sp61157.2025.00250)**<br><sub>Yupei Liu, Yuqi Jia, Jinyuan Jia, et al.</sub>

### 2024

- ![CCS 2024](https://img.shields.io/badge/CCS-2024-d1242f) **[AirGapAgent: Protecting Privacy-Conscious Conversational Agents](https://doi.org/10.1145/3658644.3690350)**<br><sub>Eugene Bagdasarian, Ren Yi, Sahra Ghalebikesabi, et al.</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Agents on the Web and Privacy

> Web and mobile agents, detecting and deterring agents, content manipulation, and privacy leakage.

### 2027

- ![S&P 2027](https://img.shields.io/badge/S%26P-2027-d1242f) **[AgentShield: Fortifying Web Applications Against AI Agents and Agentic Browsers](https://arxiv.org/abs/2610.41181)**<br><sub>Moiz Ali, Nafis Karim, Rownak Islam, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-agentshield/article.md)</sub>

### 2026

- ![ICLR Workshop 2026](https://img.shields.io/badge/ICLR%20Workshop-2026-8250df) **[Large-scale online deanonymization with LLMs](https://arxiv.org/abs/2602.16800)**<br><sub>Simon Lermen, Daniel Paleka, Joshua Swanson, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-llm-deanon/article.md)</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-d1242f) **[Investigating the Impact of Dark Patterns on LLM-Based Web Agents](https://doi.org/10.1109/sp63933.2026.00042)**<br><sub>Devin Ersoy, Brandon Lee, Ananth Shreekumar, et al.</sub>
- ![S&P 2026](https://img.shields.io/badge/S%26P-2026-d1242f) **[WebCloak: Characterizing and Mitigating Threats From LLM-Driven Web Agents as Intelligent Scrapers](https://doi.org/10.1109/sp63933.2026.00025)**<br><sub>Xinfeng Li, Tianze Qiu, Yingbin Jin, et al.</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[GEOHunter: Mapping a Generative Engine Optimization Network in the Wild](https://arxiv.org/abs/2611.26564)**<br><sub>Sean Tang, Peiran Wang, Ying Li, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-geohunter/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[Say Shibboleth: Fingerprinting the LLMs and Harnesses Behind Agentic Attacks](https://arxiv.org/abs/2611.12386)**<br><sub>Dario Pasquini, Reworr, Giuseppe Ateniese, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-shibboleth/article.md)</sub>

### 2025

- ![USENIX Security 2025](https://img.shields.io/badge/USENIX%20Security-2025-d1242f) **[Cloak, Honey, Trap: Proactive Defenses Against LLM Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn)**<br><sub>Daniel Ayzenshteyn, Roy Weiss, Yisroel Mirsky</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Surveys and SoKs

> Surveys, systematizations, and literature reviews of agent security.

### 2026

- ![TOSEM 2026](https://img.shields.io/badge/TOSEM-2026-0969da) **[Navigating the Risks: A Survey of Security and Privacy Threats in LLM-Based Agents](https://doi.org/10.1145/3807666)**<br><sub>Yuyou Gan, Yong Yang, Zhe Ma, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-05-llm-agent-threat-survey/article.md)</sub>
- ![USENIX Security 2026](https://img.shields.io/badge/USENIX%20Security-2026-d1242f) **[The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey](https://arxiv.org/abs/2603.11088)**<br><sub>Juhee Kim, Xiaoyuan Liu, Zhun Wang, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-ai-survey/article.md)</sub>
- ![Preprint 2026](https://img.shields.io/badge/Preprint-2026-8b949e) **[Behavior Safety of Autonomous Interactive Agents: Risks, Attacks, Defenses and Evaluation](https://github.com/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents)**<br><sub>Xinjie Lai, Weihao Zuo, Zheng Wu, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-behavior-safety-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[A Survey of LLM-Driven Penetration Testing: Taxonomy, Co-Evolution, and Open Challenges](https://arxiv.org/abs/2607.02605)**<br><sub>Zheyuan He, Jiaxun Dong, Zihao Li, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-llm-pentest-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445)**<br><sub>Asif Shahriar, Md Nafiu Rahman, Sadif Ahmed, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-security-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338)**<br><sub>Kexin Chu &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-lasm-survey/article.md)</sub>
- ![arXiv 2026](https://img.shields.io/badge/arXiv-2026-8b949e) **[LLM-Based Agents for Software and Systems Security: Approaches, Applications, and Assessment](https://arxiv.org/abs/2608.28490)**<br><sub>Jingjing Nie, Jiawei Guo, Krishna Meda, et al. &nbsp;·&nbsp; [Analysis](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-security-agents-slr/article.md)</sub>

<p align="right"><a href="#contents">back to top</a></p>

## Contributing

Missing a paper? Open an issue or a pull request with the title, authors, venue, and link.
