# AI Acceptable Use Policy (AUP) and Governance Framework for US Enterprises

**Version 1.1 – Agent and Automation Guidance (September 2026)**
**License**: MIT (Open Source – see LICENSE file for details)
**Purpose**: This document provides customizable guidance for US businesses to establish responsible AI policies, protecting intellectual property (IP), confidential/privileged information, financial governance, and IT infrastructure while enabling innovation with generative AI, agentic AI, agent development, and workflow/process automation — including uses beyond chat interfaces.

**AI Contributors**: Grok 4, Claude Sonnet, GPT-5, Google NotebookLM (research synthesis)

**Disclaimer**: This is general guidance, not legal advice. Consult qualified legal counsel, HR, and infosec professionals to adapt for your organization. Laws evolve rapidly (e.g., 2025–2026 federal executive orders promote minimal-burden national AI policy and challenge inconsistent state laws).

---

## Summary

This framework guides responsible adoption of generative and agentic AI (commercial enterprise subscriptions and open-source/on-premises models) while prioritizing protection of confidential information, IP, privileged data, and infrastructure. It covers chat and non-chat uses alike: developing and operating AI agents, and automating workflows or processes, are recognized productive practices that need proportionate guidance — not a separate forbidden category. It draws from NIST AI RMF (updated 2025 threat taxonomy), ISO/IEC 42001:2022, and US laws (e.g., Defend Trade Secrets Act, CCPA, emerging federal policy post-2025 EOs).

Key emphases:
- Privacy tiers for tools (enterprise vs. public).
- HR obligations for human and digital (agentic) employees.
- Infosec controls (audit logs, behavioral guardrails, model unlearning).
- Contractual safeguards (no-training clauses, IP ownership).
- Agentic risks from 2025–2026 frontier models (autonomous orchestration, MCP/A2A protocols).
- High-level starting guidance for agent development, agent use, and workflow/process automation; organizations adapt reasonable local definitions and controls.

Review annually or upon major changes (e.g., new federal/state rules, incidents).

---

## 1. Introduction and Purpose

- **Overview**: Guidelines for ethical, secure, compliant use of generative/agentic AI — including agent development, agent use, and workflow/process automation — to boost productivity while mitigating risks to company assets.
- **Purpose**: Prevent unauthorized disclosure; ensure compliance with US laws (copyright, trade secrets); promote responsible adoption of productive AI practices (chat and beyond); avoid financial liabilities from breaches/IP infringement.
- **Key Principles**: Transparency, accountability, data minimization, human oversight, bounded autonomy for agents. The same principles apply beyond chat interfaces. All users (human/digital) prioritize confidentiality over convenience. Organizations define reasonable local bounds rather than copying a single control model.

---

## 2. Scope

Applies to all employees, contractors, vendors, and digital agents using, developing, or operating AI for company tasks. Covers conversational tools, AI agents, workflow/process automation, commercial tools (with privacy features), and open-source models (on-premises/secure APIs). Chat is one interface among others; development and automation are in scope. Effective upon approval; mandatory for US operations and affiliates (adapt for cross-border via Appendix A).

---

## 3. Definitions

- **Generative AI**: Models creating content (text, code, images) from prompts (e.g., ChatGPT, Claude). Not limited to a chat window; includes embedded and API-driven generation.
- **Agentic AI**: Systems that act to complete work beyond a single prompt-response, including tool use, multi-step tasks, and orchestration (vendor-provided or internally developed; 2025–2026 frontier examples include MCP/A2A protocols). Organizations should refine this definition to match their tools and risk profile.
- **AI Agent**: An AI system that can take actions or complete work with limited autonomy — with or without a chat interface. This framework uses the term loosely; adopting organizations should set a reasonable local definition.
- **Workflow / Process Automation**: Use of AI to execute, assist, or orchestrate business processes outside a conversational interface (for example, routing work, updating systems, or running unattended pipelines). May or may not use an agent. Organizations define what is in scope.
- **Confidential Information**: Non-public data including trade secrets, customer data, financials, IP, privileged communications (attorney-client).
- **Approved Tools**: Vetted platforms (e.g., Enterprise Tier: no-training guarantees).
- **Shadow AI**: Unauthorized use of non-approved tools.
- **Digital Agent**: AI system treated as "digital employee" with policy-embedded obligations.

---

## 4. Permitted Uses

- Use approved AI for research, drafting, code suggestions (with review), routine automation, agent development/configuration, and workflow/process automation.
- Prefer enterprise subscriptions with contractual assurances.
- Input only anonymized/public data unless authorized.
- **Agents, development, and workflow automation** (beyond chat):
  - Developing, configuring, testing, and operating AI agents — and automating workflows or processes with AI — are recognized productive uses. They sit inside this policy, not outside it.
  - Chat is one interface. The same principles (confidentiality, accountability, proportionate human oversight) apply when AI acts, orchestrates, or runs with limited or no conversation.
  - Organizations should adopt their own reasonable definitions of "agent" and "automation," and proportionate expectations for ownership, review, and logging. This framework does not prescribe a single control set.
  - Identify a human (or accountable role) for outcomes. Apply extra human review when actions are high-stakes, irreversible, or externally facing, as the organization reasonably defines those terms.
- **Attribution / metadata** for AI-generated outputs (reports, code, analyses):
  - For conversational or document-style use: source references; model/version (e.g., Grok 4, Claude Sonnet); date/time; user/agent ID; prompt summary (redacted if needed).
  - For agents and automations: attribution should be reasonably reconstructable (what system acted, on whose authority) in a form the organization defines — a chat-style citation block is not required on every automated action.

---

## 5. Prohibited Uses

- Input confidential/privileged/sensitive data into non-enterprise tools.
- AI for bias-risk decisions (e.g., HR) without documented human review/bias mitigation (EEOC alignment).
- Generating infringing content or deepfakes/misinformation.
- Bypassing policy via shadow AI or personal accounts.
- For open-source/agentic: Training on company data without legal review; unlicensed use risking IP contamination.
- Agentic / automation: Unbounded autonomy in critical systems (e.g., financial databases) without testing/guardrails; deploying agents or automations that take external or irreversible actions with no identified human owner.

---

## 6. Data Handling and Confidentiality Protections

- **Privacy Tiers**: Free/public prohibit sensitive inputs; enterprise require vendor contracts (no-training, isolation).
- **Contractual Safeguards**: NDAs/data processing agreements; IP ownership clauses (outputs = company property). See Appendix B samples.
- **Security Measures**: On-premises/private instances for high-risk; encryption, access controls, SIEM integration.
- **Agentic Considerations**: Embed confidentiality in code (data minimization, escalation paths); bounded autonomy; model unlearning for inadvertent exposure. Apply in proportion to how the agent or automation acts — not only to chat prompts.
- **Audit Trails**: Log Who/What/When/Where/How/Why; tamper-proof storage; retain 7 years; integrate with SIEM for anomalies.
- **Incident Response**: Immediate reporting; align with breach notification policies.

---

## 7. Approval and Oversight

- Pre-approval from IT/security/legal for new tools/uses.
- Establish AI Governance Committee (legal, HR, IT, ethics reps) for risk evaluation, vendor diligence.
- Conduct impact assessments (NIST-aligned) for agentic/high-risk deployments.
- Agent development and workflow automation are not automatically "high-risk." Apply existing approval paths in proportion to impact; the organization decides which uses need extra review.

---

## 8. Training and Awareness

- Mandatory annual training (risks, anonymization, agentic guardrails); integrate into HR handbook.
- Tailor by role; certify managers of agents.
- Cover agent development and process automation — not only chat prompting — at a level the organization defines.
- For digital agents: "Onboarding" via code-embedded rules; "reviews" via audits.

---

## 9. Monitoring, Enforcement, and Consequences

- Monitor via logs/audits (privacy-compliant); violations → disciplinary action (up to termination/deactivation).
- Report liabilities (e.g., board/SEC if material).
- Whistleblower protections.

---

## 10. Policy Review and Updates

- Annual review + triggers (regulatory changes, incidents, frontier advances, material growth in agent or automation use).
- Incorporate feedback/emerging threats (e.g., MCP exposures, agentic breaches).

---

## Appendix A: Customization Questionnaire

This appendix serves as a comprehensive, self-guided tool for organizations to customize the **AI Acceptable Use Policy (AUP)** and **Governance Framework** in the main document. It draws from best practices in NIST AI RMF (including Playbook suggestions for Govern/Map/Measure/Manage functions), ISO/IEC 42001 implementation guidance (e.g., context assessment, stakeholder expectations), emerging 2026 agentic AI governance trends (e.g., autonomy boundaries, decision authority, escalation triggers), and practical enterprise checklists (e.g., risk tiering, vendor diligence, HR integration). Use it to turn the high-level agent, development, and automation starting points in the main document into local definitions and proportionate controls — without copying a single rigid model.

**How to Use This Questionnaire**:

- Answer each question as a team (legal, HR, IT/security, business leads, and AI governance committee if established).
- Document responses in a shared artifact (e.g., spreadsheet or internal wiki).
- Use answers to modify specific sections of the main policy (cross-references provided).
- Reassess annually or after major changes (e.g., new frontier model adoption, regulatory shifts like federal AI policy updates).
- **Always consult legal counsel** for final adaptations — especially for regulated industries (finance, healthcare) or multinationals.

### Section 1: Organizational Context and Scope

1. **What is your primary industry/sector** (e.g., technology/SaaS, finance/BFSI, healthcare, manufacturing, public sector, retail)?
   *Rationale*: Determines applicable regulations (e.g., HIPAA for healthcare, GLBA/SEC for finance, CCPA for California-based ops) and risk priorities.
   *Customization Impact*: Add industry-specific prohibitions (Section 5) or data handling rules (Section 6).

2. **What is your organization size and structure** (e.g., startup <50 employees, mid-market 50–500, enterprise >500; single-location vs. multinational; public vs. private)?
   *Rationale*: Larger enterprises need formal committees and board oversight; smaller ones may use simplified approval processes. Public companies face SEC disclosure obligations for material AI risks.
   *Customization Impact*: Expand Section 7 (Governance Committee composition) or simplify for smaller orgs.

3. **Do you have operations or data subjects in jurisdictions beyond the US** (e.g., EU/UK, Canada, APAC)? If yes, list key regions.
   *Rationale*: Triggers compliance with EU AI Act (high-risk classifications), GDPR, or other extraterritorial laws.
   *Customization Impact*: Add a "Cross-Border Compliance" subsection to Scope (Section 2).

### Section 2: Current and Planned AI Usage

4. **What categories of AI tools/models are currently in use or planned** (e.g., generative chat, image/video gen, code assistants, internally developed or configured agents, agentic/autonomous workflows, process automation beyond chat, multi-agent orchestration, custom fine-tuned models, open-source)?
   *Rationale*: Chat is only one interface. Agent development and workflow/process automation are productive, expected uses with different operational patterns than prompt-and-response.
   *Customization Impact*: Update Approved Tools list (Section 3); add locally defined agent/automation guidance (Section 4) rather than a one-size control set.

5. **For agents and automations: What level of autonomy is deployed or planned** (e.g., assisted suggestions only; bounded/single-step autonomy; multi-step goal-oriented execution; fully independent multi-agent fleets; integration with enterprise systems like ERP/CRM/databases)? Who is the human owner of outcomes?
   *Rationale*: Higher autonomy requires clearer ownership and review — defined by the organization, not a universal template.
   *Customization Impact*: Strengthen bounded autonomy rules and escalation triggers (Sections 4–5) only where local risk warrants it; expand audit trails (Section 6) in proportion.

6. **Which business functions or workflows involve AI** (e.g., customer support, software dev, HR/recruitment, financial analysis, legal review, marketing content, internal research)? Which of those are being automated as processes rather than used only through chat?
   *Rationale*: High-stakes areas (HR decisions, financial reporting) demand stricter human oversight and bias mitigation. Process automation can change who acts, not only who drafts.
   *Customization Impact*: Add role-specific prohibitions or review requirements (Section 5); tailor training (Section 8).

7. **Are staff developing, composing, or configuring AI agents (including internal prototypes) rather than only consuming vendor chat tools?** How will you locally define "agent" and "automation," and what is out of scope (e.g., simple macros vs. systems that take external actions)?
   *Rationale*: This framework stays high-level on purpose. Reasonable definitions and ownership belong to the organization so the AUP does not overtighten.
   *Customization Impact*: Refine Definitions (Section 3) and Permitted Uses (Section 4); set proportionate approval (Section 7) so development is not treated as high-risk by default.

### Section 3: Risk Profile and Governance Maturity

8. **What is your current risk tolerance for AI** (e.g., conservative/minimal autonomy in production; moderate/experiment in non-critical areas; aggressive/scale agentic workflows rapidly)?
   *Rationale*: Aligns policy enforcement with business strategy.
   *Customization Impact*: Adjust approval thresholds (Section 7) and monitoring intensity (Section 9).

9. **Do you already have an AI Governance Committee, AI ethics board, or designated AI risk owner?** If yes, describe composition and authority. If no, who will lead governance?
   *Rationale*: NIST/ISO require clear leadership and accountability.
   *Customization Impact*: Flesh out Section 7; include sample charter in Appendix B if needed.

10. **Have you conducted any AI risk/impact assessments** (e.g., NIST AI RMF Map/Measure steps, bias audits, data exposure reviews)? If yes, summarize key findings. Distinguish high-impact agent/automation uses from routine development so assessments stay proportionate.
    *Rationale*: Baseline maturity informs gaps. Not every agent or automation is high-risk by default.
    *Customization Impact*: Mandate pre-deployment assessments for high-risk uses (Section 7); avoid treating all agent development as high-risk.

### Section 4: Data, IP, and Confidentiality Protections

11. **How is company data classified** (e.g., public, internal, confidential, highly sensitive/privileged)? Do you have a formal Data Classification Policy?
    *Rationale*: Drives input prohibitions and anonymization rules.
    *Customization Impact*: Reference or embed classification in Definitions (Section 3) and Data Handling (Section 6).

12. **What types of confidential/privileged/IP-sensitive information are most at risk** (e.g., source code/IP, customer PII, financial models, attorney-client comms, trade secrets)?
    *Rationale*: Prioritizes safeguards under Defend Trade Secrets Act and contractual obligations.
    *Customization Impact*: Strengthen prohibitions (Section 5) and agentic embedding rules (Section 6).

13. **Do you use or plan to use third-party AI vendors?** What due diligence is performed (e.g., vendor questionnaires on training use, data isolation, IP clauses)?
    *Rationale*: Organizations remain liable for vendor practices.
    *Customization Impact*: Expand vendor review in Section 7; add sample questions/clauses in Appendix B.

### Section 5: Human Resources and Digital Employees

14. **How do you classify digital/agentic AI in HR terms** (e.g., pure tools; "digital employees" with obligations; hybrid)?
    *Rationale*: Impacts onboarding, logging, deactivation, and liability.
    *Customization Impact*: Customize HR provisions (Section 8) and sample clauses in Appendix B.

15. **What training/awareness mechanisms exist for employees managing AI/agents** (e.g., annual certs, role-based modules on guardrails/unlearning)? Does training cover developing and operating agents and automations, not only chat use?
    *Rationale*: HR handbooks require mandatory protective steps. Guidance beyond chat is part of ordinary productive use.
    *Customization Impact*: Enhance Section 8 with agent- and automation-specific content at a level the organization defines.

### Section 6: Technical and Operational Controls

16. **What infosec/infrastructure protections are in place for AI** (e.g., SIEM monitoring, encryption, DLP for prompts, tamper-proof logs, model unlearning capability)?
    *Rationale*: Protects IT footprint from agentic actions/behaviors.
    *Customization Impact*: Detail in Section 6; add log format examples in Appendix B.

17. **Do you need additional templates/tools** (e.g., AI impact assessment form, committee charter, vendor diligence questionnaire, incident reporting template)?
    *Rationale*: Makes the framework immediately actionable.
    *Customization Impact*: Expand Appendix B or create new appendices.

---

## Appendix B: Sample Contractual Language and Audit Log Format

**Sample Vendor Clause (No-Training/IP)**:
> "Vendor shall not use, retain, or disclose Company Data for model training, fine-tuning, or improvement without express written consent. All outputs generated using Company Data remain Company's exclusive property. Vendor provides audit logs upon request (retained 7 years)."

**Sample HR Provision for Digital Agents**:
> "Digital agents are provisioned as 'employees' with code-embedded obligations: log interactions involving confidential information; minimize data use; escalate high-risk actions to human overseers; enable model unlearning for breaches. Violations trigger deactivation and incident review."

**Sample Audit Log Format** (illustrative; organizations should adapt fields for agents and automations that do not use a chat prompt):
```json
{
  "timestamp": "2026-03-09T20:36:00Z",
  "user_agent_id": "emp123 / agent-fin-review-01",
  "model_version": "Grok-4",
  "prompt_summary": "Redacted financial analysis",
  "output_hash": "SHA256...",
  "action": "autonomous report generation",
  "compliance_check": "Approved / Escalated"
}
```

---

*Version 1.1 — September 2026*
*License: MIT — see LICENSE file*
*Published by fxops.ai*
