##### **GRC 102: Week 1 Lab-Based: Information Security Governance in Action**

**Author**: Gift Ovat  
**Date**: 5TH March 2026  
**Role**: Director of Information Security Governance, GlobalHealth Connect (GHC)

**TASK 1: THE GOVERNANCE BLUEPRINT**  
PROPOSED SECURITY GOVERNANCE ORGANISATIONAL CHART

RACI MATRIX 

| Activity | CEO  | CFO  | CTO  | Board Member  | IT Manager  | Compliance Officer | HR Manager  | Director of InfoSec Governance |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- | :---- | ----- |
| **Policy Approval** | A | C | C | I | C | C | I | R |
| **Risk Assessment Review** | A | C | C | I | C | C | I | R |
| **Security Incident Response Planning** | I | I | C | I | R | C | C | A |

**TASK 2: THE SECURITY CHARTER**  
2.1 GlobalHealth Connect Information Security Charter  
**Effective Date:** March 15, 2026  
**Approved By:** Sarah Chen, CEO  
**1\. Purpose**  
GlobalHealth Connect (GHC) provides cloud-based patient management systems that handle sensitive Protected Health Information (PHI). The purpose of this Charter is to establish a formal Information Security Program that protects the confidentiality, integrity, and availability of all information assets. This program supports GHC’s strategic goals of market growth, operational efficiency, customer trust, innovation, and regulatory excellence by embedding security into business processes.  
**2\. Scope**  
This Charter applies to:

* All information systems, networks, and devices owned or leased by GHC.  
* All employees, contractors, and third parties who access, process, or store GHC data.  
* All data, including PHI, financial records, intellectual property, and business-sensitive information, regardless of format or location (on-premises, cloud, or mobile).

**3\. Authority**  
The authority for the Information Security Program is derived from the CEO and the Board of Directors. The Director of Information Security Governance is empowered to:

* Develop, implement, and enforce information security policies and standards.  
* Conduct security assessments, audits, and investigations.  
* Require compliance from all departments and personnel.  
* Allocate resources necessary to maintain an effective security posture, subject to budget approval.

**4\. Roles and Responsibilities**

* **Board of Directors**: Provides oversight, reviews security posture, and approves major investments.  
* **CEO**: Has ultimate accountability for the security program and ensures alignment with business objectives.  
* **Director of Information Security Governance**: Owns the program, chairs the Security Steering Committee, reports to the CEO and Board, and coordinates cross-functionally.  
* **CTO**: Ensures secure development practices, infrastructure resilience, and technical innovation.  
* **CFO**: Approves security budgets, evaluates financial risk, and supports compliance cost management.  
* **Business and Department Heads**: Implement applicable policies and support security initiatives in their areas.

**5\. Key Principles**

* **Risk-Based**: Prioritise efforts based on business impact and threat landscape.  
* **Business-Aligned**: Enable, not hinder, innovation and growth.  
* **Continuous Improvement**: Regularly assess and enhance controls.  
* **Transparency and Accountability**: Clear ownership and reporting of security posture.

**6\. Reporting Structure**  
The Director of Information Security Governance reports directly to the CEO and provides a quarterly written report to the Board. The report includes key metrics, risk updates, and progress against strategic goals.  
**7\. Review and Approval**  
This Charter shall be reviewed annually by the Director of Information Security Governance and the CEO. Any material changes require approval by the CEO. The Charter is effective upon signature.

2.2 Justification Memo to Marcus Thorne (CFO)  
**To:** Marcus Thorne, CFO  
**From:** Gift Ovat, Director of Information Security Governance  
**Date:** March 16, 2026  
**SUBJECT: ALIGNMENT OF SECURITY CHARTER WITH STRATEGIC GOALS AND ACCOUNTABILITY**  
Dear Marcus,  
I’ve attached the completed Information Security Charter. It directly addresses your concerns about clear directives and accountability in several ways:

1. **Purpose & Scope** explicitly tie the security program to GHC’s strategic goals (e.g., protecting PHI supports “Maintain Customer Trust,” and a defined scope ensures no ambiguity about where we invest).  
2. **Authority** section grants me the power to enforce policies and conduct audits, ensuring that spending is tied to a clear mandate and can be traced back to Board-approved objectives.  
3. **Roles & Responsibilities:** Assign ownership to each executive to ensure that accountability is always clear and not ambiguous. For example, the CFO is listed as a consulted party for risk assessment and budget decisions, which formalises your role in evaluating ROI.  
4. **Reporting Structure** guarantees that the Board receives regular metrics, giving you confidence that resources are used effectively.

The charter also aligns with our 2026 goals:

1. **Expand Market Share**: A strong security program is a competitive indicator for reputational trust and goodwill.  
2. **Enhance Operational Efficiency**: Standardised processes will reduce overhead costs and ensure clear accountability and ownership of tasks.  
3. **Maintain Customer Trust**: Charter enforces the protection of patient data.  
4. **Foster Innovation**: Security is framed as an enabler, not a blocker.  
5. **Regulatory Excellence**: Charter mandates compliance with HIPAA, GDPR, and HITECH regulations.

This document gives us the formal directive we need to move forward with confidence. I welcome your feedback.

Warm regards,

**Gift Ovat**  
***Director of Information Security Governance***

**TASK 3: BOARD REPORTING AND METRICS**  
3.1 Board Executive Summary  
**Information Security Report**

**To**: Board of Directors

**3.1.1 Overall Security Posture: RED**

Over the last six months, key threat indicators have worsened: phishing attempts, malware detections, and high-risk incidents all increased, while patching compliance declined. Although security training participation improved, the overall risk trend is negative. Immediate attention is required to strengthen defences.

**3.1.2 Key Security Metrics**

| Metric | Current Status Feb 2026 | Trend: Last 6 Months | Commentary |
| :---- | ----- | :---- | :---- |
| **Phishing Attempts** | 320 per month | Up | External attackers are targeting GHC more aggressively. Likely due to our growth and visibility. |
| **Malware Detections** | 50 per month | Up | Increase correlates with phishing; many malware payloads arrive via email. |
| **Patching Compliance** | 55% | Down | Critical vulnerabilities are not being remediated quickly enough; the backlog is growing. |
| **Security Training Completion** | 70% | Up | Positive trend engagement is improving, but still below target (90%). |
| **High-Risk Incidents** | 7 per month | Up | Actual security events are rising; includes successful phishing, policy violations, and minor data exposures. |

**3.1.3 Key Risks and Issues**

* **Growing phishing and malware volume**: Current email filters and user awareness may be insufficient.  
* **Patch backlog**: Only 55% of critical vulnerabilities are patched on time, increasing exposure to exploits.  
* **Incident trend**: The rise in high-risk incidents suggests that existing controls are not keeping pace with threats.

**3.1.4 Recommendations**

* **Deploy advanced email security**: Implement DMARC enforcement and sandboxing to reduce phishing and malware.  
* **Accelerate patch management**: Establish a formal patch policy with SLAs; consider automated patching for non-production systems.  
* **Enhance security training**: Introduce phishing simulations and role-based modules to improve retention and behaviour.

3.2 Rationale for Metric Selection  
These five metrics provide a balanced view of GHC’s security posture:

* Phishing Attempts and Malware Detections measure external threat volume and the effectiveness of our perimeter controls.  
* Patching Compliance reflects our internal vulnerability management discipline a leading indicator of potential breaches.  
* Security Training Completion tracks the human factor; increased completion is a positive sign, and it needs to be paired with behavioural change.  
* High-Risk Incidents is an indicator that captures real impact. Together, these metrics show that while awareness is improving, our technical controls are under stress and need reinforcement.

**TASK 4: THE SECURITY STEERING COMMITTEE**  
4.1 SSC Terms of Reference  
**GlobalHealth Connect Security Steering Committee Terms of Reference**

**1\. Purpose**

The SSC exists to provide cross-functional governance for information security initiatives. It ensures that security decisions align with business objectives, resolves conflicts between departments, and oversees the implementation of the security program.

**2\. Scope**

The SSC oversees all security-related matters, including:

* Policy and standard approval.  
* Risk treatment decisions.  
* Security project prioritisation and funding.  
* Review of incident response and lessons learned.  
* Alignment of security with regulatory requirements and industry best practices.

**3\. Membership**

* **Chair**: Director of Information Security Governance will be the convener, non-voting facilitator.

* **Members**:

  * **CEO**: strategic direction, tie-breaking vote if needed  
  * **CTO**: technical feasibility and innovation impact  
  * **CFO**: financial implications and ROI  
  * **IT Manager**: operational implementation  
  * **Compliance Officer**: regulatory alignment  
  * **HR Manager**: people and training aspects  
  * **Development Lead**: developer perspective  
* **Secretary**: A designated administrative support person to take minutes of meeting and scheduling.

**4\. Roles and Responsibilities of Members**

* **All members**:

  * Represent their department’s interests and constraints.  
  * Bring relevant data and perspectives to discussions.  
  * Support decisions once made, even if they initially disagreed.  
  * Escalate unresolved issues to the CEO if consensus cannot be reached.

**5\. Meeting Frequency and Logistics**

* **Frequency**: Monthly, with additional ad-hoc meetings as needed.  
* **Duration**: 60–90 minutes.  
* **Chair**: Director of Information Security Governance.  
* **Minutes**: Distributed within one week of the meeting; approved at the next meeting.

**6\. Decision-Making Authority**

* The SSC operates by consensus. If consensus cannot be reached, the CEO makes the final decision after hearing all views.  
* The SSC has the authority to approve security policies, allocate up to $50,000 per initiative without Board approval (above that, Board approval is required).  
* All decisions are documented and communicated to relevant stakeholders.

**7\. Reporting**

* The SSC Chair provides a summary of decisions and key discussion points to the Board quarterly, integrated into the regular security report.

4.2 Sample SSC Meeting Agenda  
**GlobalHealth Connect Security Steering Committee – Sample Meeting Agenda**

**Date:** March 20, 2026  
**Time:** 10:00 – 11:30 AM  
**Location:** Virtual (Zoom)  
**Chair:** Gift Ovat, Director of Information Security Governance

**Attendees:** 

1. Sarah Chen (CEO)  
2. Elena Rodríguez (CTO)  
3. Marcus Thorne (CFO)  
4. John Smith (IT Manager)  
5. Mark Johnson (Compliance)  
6. Robert Green (HR)  
7. Jane Doe (Development Lead)

**1\. Welcome and Introductions (5 min)**

* Chair opens meeting, confirms quorum.

**2\. Review and Approval of Previous Meeting Minutes (5 min)**

* Approve minutes from February SSC meeting.

**3\. Action Items Review (10 min)**

* Status update on open actions, such as drafting of data classification policy.

**4\. Strategic Security Updates (15 min)**

* Director presents Q1 metrics and highlights (Board report summary).  
* Discussion of any emerging threats or regulatory changes.

**5\. Key Discussion Topics (30 min)**

* **Proposed Password Policy Review** (20 min)

  * Elena Rodriguez (CTO) outlines concerns about the impact on developer productivity.  
  * John Smith (IT Manager) explains security rationale.  
  * Group discusses alternatives: move to password manager \+ MFA, reduce change frequency, use passphrases.  
  * Aim for a compromise that balances security and usability.  
* **Budget Request for Email Security Upgrade** (10 min)

  * Director presents proposal for advanced phishing protection.  
  * Marcus Thorne (CFO) requests cost-benefit analysis; tabled for next meeting with more data.

**6\. Risk Register Review (10 min)**

* Review the top three risks: patch backlog, phishing, third-party vendor security.  
* Mitigation progress updates.

**7\. Any other Business or Open Forum (5 min)**

* Any other business raised by members.

**8\. Action Items and Next Steps (5 min)**

* Assign new actions:  
  * Director to circulate password policy options for vote by email.  
  * IT Manager to gather metrics on current password-related helpdesk tickets.  
  * CFO and Director to refine ROI for email security proposal.

**9\. Adjournment**

4.3 Briefing Note to CEO \- Sarah Chen   
**To:** Sarah Chen, CEO  
**From:** Gift Ovat, Director of Information Security Governance  
**Date:** March 18, 2026  
**Subject:** Value of the Security Steering Committee (SSC)

Dear Sarah,

The attached Terms of Reference and sample agenda outline how the SSC will operate. The password policy conflict between Elena and John is a perfect example of why we need this committee.

The SSC will provide a structured forum where:

* All stakeholders (including developers, IT, compliance, and finance) have a seat at the table.  
* Conflicting priorities—like security vs. productivity—can be discussed openly and resolved based on data, not emotion.  
* Decisions are documented and communicated, reducing confusion and rework.  
* We ensure that security investments are aligned with business goals and budget realities.

By establishing the SSC, we move away from an ad-hoc and reactive approach to a proactive, collaborative governance model. This will resolve the current password issue and prevent future conflicts.

I recommend we convene the first meeting next week. I’ve already heard interest from Elena and Marcus.

I will be looking forward to your reply.

Warm regards,

**Gift Ovat**  
***Director of Information Security Governance***

**TASK 5: GOVERNANCE MATURITY ASSESSMENT**  
5.1 Maturity Assessment Table

| Governance Domain | Current Maturity Score (1-5) | Justification Based on Interview Summary |
| :---- | :---- | :---- |
| **Policy & Documentation** | 2 \- Initial | We have some policies, mostly inherited from acquired companies. They’re not always consistent or up-to-date. Processes exist but are not standardised. |
| **Roles & Responsibilities** | 1 \- Ad Hoc | Everyone knows security is important, but who actually owns what? There is no clear ownership. |
| **Risk Management** | 1 \- Ad Hoc | We react to incidents, but there are no proactive risk assessments. No structured systems and processes. Purely reactive. |
| **Metrics & Reporting** | 2 \- Initial | We track a lot of technical metrics, but translating them into business impact for the Board is a challenge. Data exists but lacks business context. |
| **Training & Awareness** | 2 Initial | Annual training is mandatory, but engagement is low, and it is more of a checkbox exercise. The program is defined, but it is ineffective. |
| **Compliance** | 2 Initial | “We scramble when auditors come, but continuous compliance monitoring is still a work in progress.” Reactive compliance, no continuous monitoring. |

GHC’s maturity in each domain is scored using the 1–5 scale.

5.2 Maturity Roadmap 12–18 Months

| Initiative | Objective | Key Activities | Expected Outcome |
| :---- | :---- | :---- | :---- |
| **Develop and Formalise Information Security Policy Framework** | Standardise and update all security policies | i. Review existing policies from acquisitions. ii. Draft unified policies aligned with HIPAA, GDPR, and HITECH.  iii. Obtain approval via SSC and CEO. iv. Communicate and train relevant staff. | A comprehensive, approved policy suite that is consistently applied. |
| **Establish a Formal Risk Management Program** | Move from reactive to proactive risk management. | i. Define risk assessment methodology. ii.  Conduct initial enterprise risk assessment. iii. Create and maintain a risk register. iv. Integrate risk reviews into quarterly business planning. | A living risk register, quarterly risk reports, and proactive mitigation. |
| **Implement Security Metrics Dashboard** | Translate technical data into business-friendly KPIs. | i. Identify 8–10 key performance indicators (KPIs) that map to business goals. ii. Automate data collection where possible. iii. Design a dashboard for monthly executive review and quarterly Board reporting. | Monthly dashboard showing trends, risks, and progress; improved Board communication. |
| **Enhance Security Awareness Program** | Improve engagement and behavioural change. | i. Replace annual checkbox training with ongoing, role-based modules. ii.  Introduce phishing simulations and measure click rates. iii. Reward departments with high engagement. | Higher completion rates, lower phishing susceptibility, and a security-conscious culture. |
| **Achieve Continuous Compliance Monitoring** | Reduce audit scrambling and maintain continuous readiness. | i. Implement a Governance, Risk, and Compliance (GRC) tool. ii. Map controls to HIPAA/GDPR requirements. iii. Automate evidence collection and monitoring. iv. Conduct internal audits quarterly. | Real-time compliance visibility, smoother audits, and fewer last-minute surprises. |

**5.3 EXECUTIVE SUMMARY OF ASSESSMENT**   
**To:** David Miller, Board Member  
**From:** Gift Ovat, Director of Information Security Governance  
**Date:** March 22, 2026  
**SUBJECT: SECURITY GOVERNANCE MATURITY AND ROADMAP**

David,

You asked where we stand compared to peers and how we can improve. Using a simplified maturity model based on NIST CSF and ISO 27001, I assessed six governance domains. The results show we are largely at Levels 1 and 2, informal and reactive, except for some defined processes in policy and metrics. This is typical for a company of our size after rapid growth, but it leaves us exposed.

The attached roadmap outlines five initiatives to bring us to Level 3 Defined across all domains within the next 12–18 months. Key steps include formalising policies, instituting proactive risk management, creating a business-focused metrics dashboard, revamping security training, and implementing continuous compliance monitoring. These initiatives directly support our strategic goals: they reduce risk, improve regulatory standing, and enable secure innovation.

I recommend that the Board endorse this roadmap and allocate the necessary resources. I will report progress quarterly through the SSC and Board updates.

