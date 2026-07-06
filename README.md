# Britley Hoff — Speaking

Speaker sheet, talk material, and speaking-engagement notes for Britley Hoff.

**Live site:** https://wren-creator.github.io/speaking/

## About

Britley Hoff is a systems programmer turned Sovereign AI Architect with 20+ years hardening and running Linux, z/Linux, and IBM mainframe infrastructure. She currently serves as Technology Owner for zLinux on IBM Mainframes at BlueCross BlueShield of South Carolina, where she owns end-to-end security and modernization strategy for 1,000+ RHEL/SUSE servers on IBM S/390X mainframes. She holds an active DoD C4 security clearance along with GPEN, GCFA, and Red Hat RHCSA/RHCT credentials.

At the 2026 Red Hat Conference in Atlanta, her talk on the Rosetta Stone legacy-modernization pipeline — built on top of work first shown at Red Hat Summit — turned hallway conversations about COBOL and enterprise PowerShell into one of the event's talked-about sessions. She is the author of eight books on private, auditable AI infrastructure and builds open-source tools, from a browser-based TN3270 mainframe client to Ollama-powered legacy-code converters, that hand enterprises back control of their own systems and their own data.

## Featured talks

**The Terminal Time Forgot** — *Mainframe Security*
A hands-on look at Web3270, an open-source, browser-based TN3270 client, and the decades-old attack surface it exposes: RACF credential probing, protocol fuzzing, and live man-in-the-middle field injection on systems that still run the world's core financial infrastructure.

**Silicon Sovereignty: Reclaiming AI from the Cloud** — *AI Infrastructure*
Why "private AI" usually still means someone else's cloud, and what it actually takes, hardware, local inference, retrieval, agent protocols, to run a fully sovereign AI stack you own end to end, from a laptop to an enterprise mainframe.

**The Rosetta Stone: Modernizing Legacy Code Without Losing Trust** — *Legacy Modernization*
Inside the AI + Ansible pipeline born at Red Hat Summit and reforged at the 2026 Red Hat Conference: how to document, test, and convert decades-old shell scripts and PowerShell into modern automation, with proof, not promises, that the new code does what the old one did.

## Publications

- *Silicon Sovereignty: Orchestrating Private AI at the Edge*
- *The Big Red Book of AI on IBM Mainframe*
- *Ironclad Intelligence: The Manual for Sovereign AI on IBM Mainframes*
- *The Algorithmic Audit: Compliance in a Probabilistic World*
- *Unbound Intelligence*
- *LLMOps Infrastructure for the Generative Era*
- *A Beginner's Introduction to Terraform*
- *The Prompt Playbook*

## Open source

Selected projects underpinning the talks above (18 public repos at [github.com/wren-creator](https://github.com/wren-creator)):

- **[Web3270](https://github.com/wren-creator/web3270)** — browser-based TN3270(E) mainframe terminal client with a built-in security-testing toolkit (RACF probing, protocol fuzzing, MITM traffic modification)
- **[Rosetta Stone](https://github.com/wren-creator/red-hat-conference)** — AI + Ansible legacy code modernization pipeline; documents, tests, and converts legacy scripts before touching them
- **[ModelForge](https://github.com/wren-creator/ModelForge)** — LLM observability and hardware-recommendation platform for local/private model deployment
- **[LLM Validator](https://github.com/wren-creator/llm-validator)** — model-fingerprinting CLI that detects silent provider-side model changes via deterministic prompts and response hashing
- **[AI Compliance Standards](https://github.com/wren-creator/AI-compliance-standards)** — open, living workspace for AI governance and AI-BOM standards

## Repo contents

- `index.html` — the public speaker sheet, served via GitHub Pages
- `assets/` — headshot and conference photo used on the sheet
- `speaker-sheet-private.html` — a local-only copy with direct phone contact, used for printed/emailed PDFs; excluded from this repo via `.gitignore`

## Contact

- Email: britleyhoff@gmail.com
- GitHub: [github.com/wren-creator](https://github.com/wren-creator)
- LinkedIn: [linkedin.com/in/britley-h-2a429811](https://linkedin.com/in/britley-h-2a429811)

Available for keynotes, conference talks, and workshops on sovereign AI infrastructure and legacy modernization.
