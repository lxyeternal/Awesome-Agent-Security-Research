# Awesome Agent Security Research

A curated, daily-updated list of research papers on AI agent security, grouped by topic. Each entry gives the venue and year, the title (linked to the paper), and the authors. `[Analysis]` links to our write-up of the paper (in Chinese), where we have one.

55 papers so far.

## Contents

- [Benchmarks](#benchmarks) (5)
- [Agent Skills and Plugin Ecosystems](#agent-skills-and-plugin-ecosystems) (11)
- [MCP and Tool Chains](#mcp-and-tool-chains) (8)
- [Agent Applications and Frameworks](#agent-applications-and-frameworks) (6)
- [Prompt Injection, Guardrails, and Permissions](#prompt-injection-guardrails-and-permissions) (11)
- [Agents on the Web and Privacy](#agents-on-the-web-and-privacy) (7)
- [Surveys and SoKs](#surveys-and-soks) (7)

## Benchmarks

Benchmarks and datasets for evaluating agent security.

- [CCS] [2026] **PriMobiBench**: [PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents](https://arxiv.org/abs/2609.13873). Qihang Cen, Tianshuo Cong, Da Song, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-primobibench/article.md)
- [arXiv] [2026] **SkillVetBench**: [Benchmarking Security Risk Detection and Verification in Open Agentic Skill Ecosystems](https://arxiv.org/abs/2606.00925). Ismail Hossain, Sai Puppala, Zhuoran Lu, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillvetbench/article.md)
- [arXiv] [2026] **HarmfulSkillBench**: [HarmfulSkillBench: How Do Harmful Skills Weaponize Your Agents?](https://arxiv.org/abs/2604.15415). Yukun Jiang, Yage Zhang, Michael Backes, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-harmfulskillbench/article.md)
- [arXiv] [2026] **MalSkillBench**: [MalSkillBench: A Runtime-Verified Benchmark of Malicious Agent Skills](https://arxiv.org/abs/2606.07131). Wenbo Guo, Wei Zeng, Chengwei Liu, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskillbench/article.md)
- [arXiv] [2026] **SkillSafetyBench**: [SkillSafetyBench: Evaluating Agent Safety under Skill-Facing Attack Surfaces](https://arxiv.org/abs/2605.12015). Chang Jin, An Wang, Zeming Wei, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillsafetybench/article.md)

## Agent Skills and Plugin Ecosystems

Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege.

- [ASE] [2026] [How Your Credentials Are Leaked by LLM Agent Skills: An Empirical Study](https://arxiv.org/abs/2604.03070). Zhihao Chen, Ying Zhang, Yi Liu, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skill-credential-leak/article.md)
- [CCS] [2026] [SkillScope: Toward Fine-Grained Least-Privilege Enforcement for Agent Skills](https://arxiv.org/abs/2605.05868). Jiangrong Wu, Yuhong Nan, Yixi Lin, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-skillscope/article.md)
- [USENIX Security] [2026] ["Do Not Mention This to the User": Detecting and Understanding Malicious Agent Skills in the Wild](https://arxiv.org/abs/2602.06547). Yi Liu, Zhihao Chen, Yanjun Zhang, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malicious-skills-wild/article.md)
- [arXiv] [2026] ["Elementary, My Dear Watson." Detecting Malicious Skills via Neuro-Symbolic Reasoning across Heterogeneous Artifacts](https://arxiv.org/abs/2603.27204). Shenao Wang, Junjie He, Yanjie Zhao, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskills-neurosymbolic/article.md)
- [arXiv] [2026] [A Comprehensive Survey on Agent Skills: Taxonomy, Techniques, and Applications](https://arxiv.org/abs/2605.07358). Yingli Zhou, Wang Shu, Yaodong Su, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skills-survey/article.md)
- [arXiv] [2026] [Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale](https://arxiv.org/abs/2601.10338). Yi Liu, Weizhe Wang, Ruitao Feng, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skills-wild-vulns/article.md)
- [arXiv] [2026] [ColluSkill: Adversarial Cross-Skill Composition for Evading Agent Skill Scanners](https://arxiv.org/abs/2608.09732). Puyu Zeng, Simeng Qin, Jingzhi Li, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-colluskill/article.md)
- [arXiv] [2026] [JailbreakSkill: Scaling Automated Red-Teaming with Reusable and Ever-Evolving Skills](https://arxiv.org/abs/2608.16465). Xiaoyu Wen, Jiajia Li, Zhida He, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-jailbreakskill/article.md)
- [arXiv] [2026] [Skills That Don't Exist: A Large-Scale Study of Hallucinated Skill Recommendation in LLM Agents](https://arxiv.org/abs/2607.12340). Weifeng Yuan, Wenbo Guo, Feng Dong, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-hallucinated-skills/article.md)
- [arXiv] [2026] [Towards Secure Agent Skills: Architecture, Threat Taxonomy, and Security Analysis](https://arxiv.org/abs/2604.02837). Zhiyuan Li, Jingzheng Wu, Xiang Ling, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-secure-agent-skills-sok/article.md)
- [CAMLIS] [2025] [Agent Skill Security: Threat Models, Attacks, Defenses, and Evaluation](https://arxiv.org/abs/2607.13987). Sanket Badhe, Priyanka Tiwari. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skill-security-tmade/article.md)

## MCP and Tool Chains

Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies.

- [FSE] [2026] [AgentBound: Securing Execution Boundaries of AI Agents](https://doi.org/10.1145/3808103). Christoph Bühler, Matteo Biagiola, Luca Di Grazia, et al.
- [NDSS] [2026] [Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://arxiv.org/abs/2504.03111). Zichuan Li, Jian Cui, Xiaojing Liao, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-les-dissonances/article.md)
- [NDSS] [2026] [Prompt Injection Attack to Tool Selection in LLM Agents](https://doi.org/10.14722/ndss.2026.230675). Jiawen Shi, Zenghui Yuan, Guiyao Tie, et al.
- [S&P] [2026] [Parasites in the Toolchain: A Large-Scale Analysis of Attacks on the MCP Ecosystem](https://arxiv.org/abs/2509.06572). Shuli Zhao, Qinsheng Hou, Zihan Zhan, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-mcp-parasites/article.md)
- [S&P] [2026] [When AI Meets the Web: Prompt Injection Risks in Third-Party AI Chatbot Plugins](https://arxiv.org/abs/2511.05797). Yigitcan Kaya, Anton Landerer, Stijn Pletinckx, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-chatbot-plugins/article.md)
- [arXiv] [2026] [AGENTFLOW: Building Agent Dependency Graphs for Static Analysis of Agent Programs](https://arxiv.org/abs/2607.01640). Shenao Wang, Xinyi Hou, Yanjie Zhao, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentflow-adg/article.md)
- [arXiv] [2026] [Characterizing LLM Agent Behaviors in Module Shadowing Environments](https://arxiv.org/abs/2610.40716). Shuai Yang, Enmeng Lu, Jinyu Fan, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-module-shadowing/article.md)
- [arXiv] [2026] [Characterizing Security Effects of OSS Vulnerabilities in Agent Systems](https://arxiv.org/abs/2610.05036). Yu Ji, Yang Wei, Yutao Hu, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-oss-vuln-agent/article.md)

## Agent Applications and Frameworks

Vulnerabilities in agent applications, agent frameworks, and multi-agent systems.

- [USENIX Security] [2026] [Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity26/presentation/luo). Jiaqi Luo, Jiarun Dai, Fengyu Liu, et al.
- [USENIX Security] [2026] [MASLeak: Investigating and Exposing Intellectual Property Leakage Vulnerabilities in Multi-Agent Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/wang-liwen). Liwen Wang, Wenxuan Wang, Shuai Wang, et al.
- [USENIX Security] [2026] [When AIOps Become "AI Oops": Subverting LLM-driven IT Operations via Telemetry Manipulation](https://www.usenix.org/conference/usenixsecurity26/presentation/pasquini). Dario Pasquini, Evgenios M. Kornaropoulos, Giuseppe Ateniese, et al.
- [ASE] [2025] [Security Debt in LLM Agent Applications: A Measurement Study of Vulnerabilities and Mitigation Trade-offs](https://doi.org/10.1109/ase63991.2025.00053). Zhuoxiang Shen, Jiarun Dai, Yuan Zhang, et al.
- [USENIX Security] [2025] [Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/liu-fengyu). Fengyu Liu, Yuan Zhang, Jiaqi Luo, et al.
- [CCS] [2024] [Demystifying RCE Vulnerabilities in LLM-Integrated Apps](https://doi.org/10.1145/3658644.3690338). Tong Liu, Zizhuang Deng, Guozhu Meng, et al.

## Prompt Injection, Guardrails, and Permissions

Prompt injection attacks and defenses, runtime guardrails, isolation architectures, and permission models.

- [NDSS] [2026] [ACE: A Security Architecture for LLM-Integrated App Systems](https://doi.org/10.14722/ndss.2026.230352). Enlai Li, Tushin Mallick, Evan Rose, et al.
- [NDSS] [2026] [Attention is All You Need to Defend Against Indirect Prompt Injection Attacks in LLMs](https://doi.org/10.14722/ndss.2026.240394). Yinan Zhong, Qianhao Miao, Yanjiao Chen, et al.
- [NDSS] [2026] [ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data](https://doi.org/10.14722/ndss.2026.240702). Reachal Wang, Yuqi Jia, Neil Zhenqiang Gong.
- [NDSS] [2026] [SAGA: A Security Architecture for Governing AI Agentic Systems](https://doi.org/10.14722/ndss.2026.230869). Georgios Syros, Anshuman Suri, Jacob Ginesin, et al.
- [USENIX Security] [2026] [The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections](https://arxiv.org/abs/2510.09023). Milad Nasr, Nicholas Carlini, Chawin Sitawarin, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-attacker-moves-second/article.md)
- [arXiv] [2026] [DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695). Wenhao Lin, Chenyu Yu, Xingwei Lin, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-dreamguard/article.md)
- [arXiv] [2026] [How Agents Ask for Permission: User Permissions for AI Agents, from Interfaces to Enforcement](https://arxiv.org/abs/2607.13718). Alexandra E. Michael, Franziska Roesner. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-permissions/article.md)
- [CCS] [2025] [AgentSentinel: An End-to-End and Real-Time Security Defense Framework for Computer-Use Agents](https://doi.org/10.1145/3719027.3765064). Hu Haitao, Peng Chen, Yanpeng Zhao, et al.
- [NDSS] [2025] [IsolateGPT: An Execution Isolation Architecture for LLM-Based Systems](https://doi.org/10.14722/ndss.2025.241131). Yuhao Wu, Franziska Roesner, Tadayoshi Kohno, et al.
- [S&P] [2025] [DataSentinel: A Game-Theoretic Detection of Prompt Injection Attacks](https://doi.org/10.1109/sp61157.2025.00250). Yupei Liu, Yuqi Jia, Jinyuan Jia, et al.
- [CCS] [2024] [AirGapAgent: Protecting Privacy-Conscious Conversational Agents](https://doi.org/10.1145/3658644.3690350). Eugene Bagdasarian, Ren Yi, Sahra Ghalebikesabi, et al.

## Agents on the Web and Privacy

Web and mobile agents, detecting and deterring agents, content manipulation, and privacy leakage.

- [S&P] [2027] [AgentShield: Fortifying Web Applications Against AI Agents and Agentic Browsers](https://arxiv.org/abs/2610.41181). Moiz Ali, Nafis Karim, Rownak Islam, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-agentshield/article.md)
- [ICLR Workshop] [2026] [Large-scale online deanonymization with LLMs](https://arxiv.org/abs/2602.16800). Simon Lermen, Daniel Paleka, Joshua Swanson, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-llm-deanon/article.md)
- [S&P] [2026] [Investigating the Impact of Dark Patterns on LLM-Based Web Agents](https://doi.org/10.1109/sp63933.2026.00042). Devin Ersoy, Brandon Lee, Ananth Shreekumar, et al.
- [S&P] [2026] [WebCloak: Characterizing and Mitigating Threats From LLM-Driven Web Agents as Intelligent Scrapers](https://doi.org/10.1109/sp63933.2026.00025). Xinfeng Li, Tianze Qiu, Yingbin Jin, et al.
- [arXiv] [2026] [GEOHunter: Mapping a Generative Engine Optimization Network in the Wild](https://arxiv.org/abs/2611.26564). Sean Tang, Peiran Wang, Ying Li, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-geohunter/article.md)
- [arXiv] [2026] [Say Shibboleth: Fingerprinting the LLMs and Harnesses Behind Agentic Attacks](https://arxiv.org/abs/2611.12386). Dario Pasquini, Reworr, Giuseppe Ateniese, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-shibboleth/article.md)
- [USENIX Security] [2025] [Cloak, Honey, Trap: Proactive Defenses Against LLM Agents](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn). Daniel Ayzenshteyn, Roy Weiss, Yisroel Mirsky.

## Surveys and SoKs

Surveys, systematizations, and literature reviews of agent security.

- [TOSEM] [2026] [Navigating the Risks: A Survey of Security and Privacy Threats in LLM-Based Agents](https://doi.org/10.1145/3807666). Yuyou Gan, Yong Yang, Zhe Ma, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-05-llm-agent-threat-survey/article.md)
- [USENIX Security] [2026] [The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey](https://arxiv.org/abs/2603.11088). Juhee Kim, Xiaoyuan Liu, Zhun Wang, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-ai-survey/article.md)
- [Preprint] [2026] [Behavior Safety of Autonomous Interactive Agents: Risks, Attacks, Defenses and Evaluation](https://github.com/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents). Xinjie Lai, Weihao Zuo, Zheng Wu, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-behavior-safety-survey/article.md)
- [arXiv] [2026] [A Survey of LLM-Driven Penetration Testing: Taxonomy, Co-Evolution, and Open Challenges](https://arxiv.org/abs/2607.02605). Zheyuan He, Jiaxun Dong, Zihao Li, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-llm-pentest-survey/article.md)
- [arXiv] [2026] [A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445). Asif Shahriar, Md Nafiu Rahman, Sadif Ahmed, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-security-survey/article.md)
- [arXiv] [2026] [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338). Kexin Chu. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-lasm-survey/article.md)
- [arXiv] [2026] [LLM-Based Agents for Software and Systems Security: Approaches, Applications, and Assessment](https://arxiv.org/abs/2608.28490). Jingjing Nie, Jiawei Guo, Krishna Meda, et al. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-security-agents-slr/article.md)

## Contributing

Missing a paper? Open an issue or a pull request with the title, authors, venue, and link.
