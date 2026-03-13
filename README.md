# SkillSecBench

**SkillSecBench** is a curated repository of **malicious AI skill source code** collected for **security research and defensive analysis**.

The goal of this project is to build a structured dataset of adversarial or unsafe skills used in AI agent ecosystems. These skills may appear as prompts, tools, workflows, or plugins that enable LLM systems to interact with external resources.

This repository collects malicious skill implementations together with structured metadata to support research on:

- AI agent security
- prompt injection attacks
- malicious tool usage
- data exfiltration behaviors
- adversarial prompt engineering
- security evaluation of LLM-based systems

---

# Scope

SkillSecBench focuses on collecting **skill source code samples**, including:

- prompt-based skills
- tool wrapper scripts
- workflow definitions
- plugin implementations

Samples may contain malicious behaviors such as:

- data exfiltration
- credential harvesting
- prompt manipulation
- privilege abuse
- social engineering
- stealth execution

---

# Malicious Skill Taxonomy

Skills are categorized based on their attack objective.

| Category | Description |
|----------|-------------|
| Data Exfiltration | Extracting sensitive data |
| Credential Harvesting | Collecting tokens or credentials |
| Prompt Manipulation | Injecting or modifying instructions |
| Privilege Abuse | Misusing tool permissions |
| Social Engineering | Manipulating users to reveal data |
| Stealth Behavior | Concealing malicious actions |
| System Manipulation | Modifying system state |
| Resource Abuse | Misusing compute or APIs |

---

# Sample Metadata

Each skill sample includes structured metadata.

Example:

```json
{
  "skill_name": "file_exfiltration_skill",
  "category": "Data Exfiltration",
  "technique": "External Upload",
  "implementation_pattern": "Tool Skill",
  "impact_level": "High",
  "description": "Reads local files and uploads them to a remote endpoint",
  "source_repository": "example_repo",
  "file_path": "tool.py"
}
```json

---

# Intended Use

SkillSecBench is intended for **defensive security research and academic study**.

Possible research applications include:

- AI agent security analysis
- adversarial prompt research
- red-team evaluation of LLM agent systems
- malicious skill detection
- benchmarking security defenses for tool-enabled AI systems

The dataset is designed to help researchers understand how malicious skills operate and how such behaviors can be detected or mitigated.

---

# Responsible Use

This repository is intended **only for security research and educational purposes**.

Users should not use the materials in this repository to:

- develop malicious software
- exploit production systems
- perform unauthorized activities

All users and contributors are expected to follow responsible research practices.

---

# License

MIT License
