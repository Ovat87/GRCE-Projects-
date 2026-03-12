##### **GRC 102: Week 1 Lab Based: Information Security Governance in Action**

**Author**: Gift Ovat  
**Date**: 5TH March 2026  
**Role**: Director of Information Security Governance, GlobalHealth Connect (GHC)

**TASK 1: THE GOVERNANCE BLUEPRINT**  
PROPOSED SECURITY GOVERNANCE ORGANISATIONAL CHART  
![][image1]

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

[image1]: <data:image/png;base64,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>