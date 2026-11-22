# Awesome Agent Security Research

A curated, daily-updated list of research papers on AI agent security, grouped by topic. Each entry links to the paper, and `[Analysis]` links to our write-up of it (in Chinese).

35 papers so far.

## Contents

- [Benchmarks](#benchmarks) (4)
- [Agent Skills and Plugin Ecosystems](#agent-skills-and-plugin-ecosystems) (11)
- [MCP and Tool Chains](#mcp-and-tool-chains) (6)
- [Prompt Injection, Guardrails, and Permissions](#prompt-injection-guardrails-and-permissions) (3)
- [Agents on the Web and Privacy](#agents-on-the-web-and-privacy) (4)
- [Surveys and SoKs](#surveys-and-soks) (7)

## Benchmarks

Benchmarks and datasets for evaluating agent security.

- **PriMobiBench**: [PriMobiBench: Characterizing Visual Privacy Leakage in VLM-Driven Mobile GUI Agents](https://arxiv.org/abs/2609.13873). Qihang Cen, Tianshuo Cong, Da Song, et al. *ACM CCS 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-primobibench/article.md)
- **SkillVetBench**: [Benchmarking Security Risk Detection and Verification in Open Agentic Skill Ecosystems](https://arxiv.org/abs/2606.00925). Ismail Hossain, Sai Puppala, Zhuoran Lu, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillvetbench/article.md)
- **SkillSafetyBench**: [SkillSafetyBench: Evaluating Agent Safety under Skill-Facing Attack Surfaces](https://arxiv.org/abs/2605.12015). Chang Jin, An Wang, Zeming Wei, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skillsafetybench/article.md)
- **HarmfulSkillBench**: [HarmfulSkillBench: How Do Harmful Skills Weaponize Your Agents?](https://arxiv.org/abs/2604.15415). Yukun Jiang, Yage Zhang, Michael Backes, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-harmfulskillbench/article.md)

## Agent Skills and Plugin Ecosystems

Malicious, vulnerable, and harmful agent skills; skill marketplaces; skill vetting and least privilege.

- [SkillScope: Toward Fine-Grained Least-Privilege Enforcement for Agent Skills](https://arxiv.org/abs/2605.05868). Jiangrong Wu, Yuhong Nan, Yixi Lin, et al. *ACM CCS 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-skillscope/article.md)
- [Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale](https://arxiv.org/abs/2601.10338). Yi Liu, Weizhe Wang, Ruitao Feng, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skills-wild-vulns/article.md)
- [How Your Credentials Are Leaked by LLM Agent Skills: An Empirical Study](https://arxiv.org/abs/2604.03070). Zhihao Chen, Ying Zhang, Yi Liu, et al. *ASE 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-skill-credential-leak/article.md)
- [Towards Secure Agent Skills: Architecture, Threat Taxonomy, and Security Analysis](https://arxiv.org/abs/2604.02837). Zhiyuan Li, Jingzheng Wu, Xiang Ling, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-secure-agent-skills-sok/article.md)
- ["Elementary, My Dear Watson." Detecting Malicious Skills via Neuro-Symbolic Reasoning across Heterogeneous Artifacts](https://arxiv.org/abs/2603.27204). Shenao Wang, Junjie He, Yanjie Zhao, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malskills-neurosymbolic/article.md)
- ["Do Not Mention This to the User": Detecting and Understanding Malicious Agent Skills in the Wild](https://arxiv.org/abs/2602.06547). Yi Liu, Zhihao Chen, Yanjun Zhang, et al. *USENIX Security 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-malicious-skills-wild/article.md)
- [JailbreakSkill: Scaling Automated Red-Teaming with Reusable and Ever-Evolving Skills](https://arxiv.org/abs/2608.16465). Xiaoyu Wen, Jiajia Li, Zhida He, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-jailbreakskill/article.md)
- [Skills That Don't Exist: A Large-Scale Study of Hallucinated Skill Recommendation in LLM Agents](https://arxiv.org/abs/2607.12340). Weifeng Yuan, Wenbo Guo, Feng Dong, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-hallucinated-skills/article.md)
- [ColluSkill: Adversarial Cross-Skill Composition for Evading Agent Skill Scanners](https://arxiv.org/abs/2608.09732). Puyu Zeng, Simeng Qin, Jingzhi Li, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-colluskill/article.md)
- [A Comprehensive Survey on Agent Skills: Taxonomy, Techniques, and Applications](https://arxiv.org/abs/2605.07358). Yingli Zhou, Wang Shu, Yaodong Su, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skills-survey/article.md)
- [Agent Skill Security: Threat Models, Attacks, Defenses, and Evaluation](https://arxiv.org/abs/2607.13987). Sanket Badhe, Priyanka Tiwari. *CAMLIS 2025*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-skill-security-tmade/article.md)

## MCP and Tool Chains

Attacks and analyses on MCP servers, tool pools, third-party plugins, and agent dependencies.

- [Characterizing LLM Agent Behaviors in Module Shadowing Environments](https://arxiv.org/abs/2610.40716). Shuai Yang, Enmeng Lu, Jinyu Fan, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-module-shadowing/article.md)
- [Characterizing Security Effects of OSS Vulnerabilities in Agent Systems](https://arxiv.org/abs/2610.05036). Yu Ji, Yang Wei, Yutao Hu, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-oss-vuln-agent/article.md)
- [Parasites in the Toolchain: A Large-Scale Analysis of Attacks on the MCP Ecosystem](https://arxiv.org/abs/2509.06572). Shuli Zhao, Qinsheng Hou, Zihan Zhan, et al. *IEEE S&P 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-mcp-parasites/article.md)
- [When AI Meets the Web: Prompt Injection Risks in Third-Party AI Chatbot Plugins](https://arxiv.org/abs/2511.05797). Yigitcan Kaya, Anton Landerer, Stijn Pletinckx, et al. *IEEE S&P 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-chatbot-plugins/article.md)
- [Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://arxiv.org/abs/2504.03111). Zichuan Li, Jian Cui, Xiaojing Liao, et al. *NDSS 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-les-dissonances/article.md)
- [AGENTFLOW: Building Agent Dependency Graphs for Static Analysis of Agent Programs](https://arxiv.org/abs/2607.01640). Shenao Wang, Xinyi Hou, Yanjie Zhao, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentflow-adg/article.md)

## Prompt Injection, Guardrails, and Permissions

Prompt injection and jailbreak defenses, runtime guardrails, and permission models.

- [The Attacker Moves Second: Stronger Adaptive Attacks Bypass Defenses Against LLM Jailbreaks and Prompt Injections](https://arxiv.org/abs/2510.09023). Milad Nasr, Nicholas Carlini, Chawin Sitawarin, et al. *USENIX Security 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-attacker-moves-second/article.md)
- [DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695). Wenhao Lin, Chenyu Yu, Xingwei Lin, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-dreamguard/article.md)
- [How Agents Ask for Permission: User Permissions for AI Agents, from Interfaces to Enforcement](https://arxiv.org/abs/2607.13718). Alexandra E. Michael, Franziska Roesner. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-permissions/article.md)

## Agents on the Web and Privacy

Web and mobile agents, agent detection and fingerprinting, content manipulation, and privacy leakage.

- [Say Shibboleth: Fingerprinting the LLMs and Harnesses Behind Agentic Attacks](https://arxiv.org/abs/2611.12386). Dario Pasquini, Reworr, Giuseppe Ateniese, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-shibboleth/article.md)
- [GEOHunter: Mapping a Generative Engine Optimization Network in the Wild](https://arxiv.org/abs/2611.26564). Sean Tang, Peiran Wang, Ying Li, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-geohunter/article.md)
- [AgentShield: Fortifying Web Applications Against AI Agents and Agentic Browsers](https://arxiv.org/abs/2610.41181). Moiz Ali, Nafis Karim, Rownak Islam, et al. *IEEE S&P 2027*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-11-agentshield/article.md)
- [Large-scale online deanonymization with LLMs](https://arxiv.org/abs/2602.16800). Simon Lermen, Daniel Paleka, Joshua Swanson, et al. *ICLR 2026 Workshop*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-10-llm-deanon/article.md)

## Surveys and SoKs

Surveys, systematizations, and literature reviews of agent security.

- [LLM-Based Agents for Software and Systems Security: Approaches, Applications, and Assessment](https://arxiv.org/abs/2608.28490). Jingjing Nie, Jiawei Guo, Krishna Meda, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-09-security-agents-slr/article.md)
- [A Survey of LLM-Driven Penetration Testing: Taxonomy, Co-Evolution, and Open Challenges](https://arxiv.org/abs/2607.02605). Zheyuan He, Jiaxun Dong, Zihao Li, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-llm-pentest-survey/article.md)
- [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents: A Layered Attack Surface Framework](https://arxiv.org/abs/2604.23338). Kexin Chu. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-lasm-survey/article.md)
- [A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445). Asif Shahriar, Md Nafiu Rahman, Sadif Ahmed, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-security-survey/article.md)
- [The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey](https://arxiv.org/abs/2603.11088). Juhee Kim, Xiaoyuan Liu, Zhun Wang, et al. *arXiv 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agentic-ai-survey/article.md)
- [Behavior Safety of Autonomous Interactive Agents: Risks, Attacks, Defenses and Evaluation](https://github.com/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents). Xinjie Lai, Weihao Zuo, Zheng Wu, et al. *Preprint 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-08-agent-behavior-safety-survey/article.md)
- [Navigating the Risks: A Survey of Security and Privacy Threats in LLM-Based Agents](https://doi.org/10.1145/3807666). Yuyou Gan, Yong Yang, Zhe Ma, et al. *ACM TOSEM 2026*. [[Analysis]](https://github.com/lxyeternal/paper-to-wechat/blob/main/papers/2026-05-llm-agent-threat-survey/article.md)

## Contributing

Missing a paper? Open an issue or a pull request with the title, authors, venue, and link.
