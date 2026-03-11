GRC 102 

**Author**: Gift Ovat  
**Date**: March 2026  
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
| **Develop and Formalise Information Security Policy Framework** | Standardise and update all security policies | i. Review existing policies from acquisitions.ii. Draft unified policies aligned with HIPAA, GDPR, and HITECH.iii. Obtain approval via SSC and CEO.iv. Communicate and train relevant staff. | A comprehensive, approved policy suite that is consistently applied. |
| **Establish a Formal Risk Management Program** | Move from reactive to proactive risk management. | i. Define risk assessment methodology.ii.  Conduct initial enterprise risk assessment.iii. Create and maintain a risk register.iv. Integrate risk reviews into quarterly business planning. | A living risk register, quarterly risk reports, and proactive mitigation. |
| **Implement Security Metrics Dashboard** | Translate technical data into business-friendly KPIs. | i. Identify 8–10 key performance indicators (KPIs) that map to business goals.ii. Automate data collection where possible.iii. Design a dashboard for monthly executive review and quarterly Board reporting. | Monthly dashboard showing trends, risks, and progress; improved Board communication. |
| **Enhance Security Awareness Program** | Improve engagement and behavioural change. | i. Replace annual checkbox training with ongoing, role-based modules.ii.  Introduce phishing simulations and measure click rates.iii. Reward departments with high engagement. | Higher completion rates, lower phishing susceptibility, and a security-conscious culture. |
| **Achieve Continuous Compliance Monitoring** | Reduce audit scrambling and maintain continuous readiness. | i. Implement a Governance, Risk, and Compliance (GRC) tool.ii. Map controls to HIPAA/GDPR requirements.iii. Automate evidence collection and monitoring.iv. Conduct internal audits quarterly. | Real-time compliance visibility, smoother audits, and fewer last-minute surprises. |

**5.3 EXECUTIVE SUMMARY OF ASSESSMENT**   
**To:** David Miller, Board Member  
**From:** Gift Ovat, Director of Information Security Governance  
**Date:** March 22, 2026  
**SUBJECT: SECURITY GOVERNANCE MATURITY AND ROADMAP**

David,

You asked where we stand compared to peers and how we can improve. Using a simplified maturity model based on NIST CSF and ISO 27001, I assessed six governance domains. The results show we are largely at Levels 1 and 2, informal and reactive, except for some defined processes in policy and metrics. This is typical for a company of our size after rapid growth, but it leaves us exposed.

The attached roadmap outlines five initiatives to bring us to Level 3 Defined across all domains within the next 12–18 months. Key steps include formalising policies, instituting proactive risk management, creating a business-focused metrics dashboard, revamping security training, and implementing continuous compliance monitoring. These initiatives directly support our strategic goals: they reduce risk, improve regulatory standing, and enable secure innovation.

I recommend that the Board endorse this roadmap and allocate the necessary resources. I will report progress quarterly through the SSC and Board updates.

[image1]: <data:image/png;base64,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DIJW4whaCJgCAAAGQatxBC0ETAEAAIOg1TiCFgKmAACAQdBqHEELAVMAAMAgaDWOoIWAKQAAYBC0GkfQQsAUAAAwCFqNI2ghYAoAABgErcYRtBAwBQAAjN4OWg8//HAydepU1z99xozkkUceqfLjDNp662TWrFnJJn37mumzRNBCwBQAADB6M2jpmYZbbLllMnTHHd3rRx97LNlt992TzTbf3FHtmmuvTZ555plk68GDk3nz5iWXXnqpmU9WCFoImAIAAEZvBa2nn346Ofnkk2tqClo7DxtWU1MY6+51lghaCJgCAABGbwWteoFJQevFF19MXnjhhS7Hi19niaCFgCkAAGDkLWhxRgsFYQoAABi9FbR23HHH5OWXX66+HrnPPnWDls5ujR8/3vVPnjy55kfyWSNoIWAKAAAYvRW05Igjj3RnqGTgVlu5oOVfh2eunp07172+Z+ZMM48sEbQQMAUAAIzeDFpFQ9BCwBQAADAIWo0jaCFgCgAAGAStxhG0EDAFAAAMglbjCFoImAIAAAZBq3EELQRMAQAAg6DVOIIWAqYAAICRh6D1+OOPm1p3Hpo929SyQNBCwBQAADB6GrSuvuaa5IorrzT1ZnR3t/cvbbttzY1N5fnnnzfjZYGghYApAAA62FprrZVssMEGyWWXXZYsW7YsWbBgQfLoo4/2OGiddfbZyRNPPFFTUzB66aWXqgFJQUrhSLWrr77a1efNm+eea+iHq6Zuv/79a+alO8MP22WXmprmNXfuXDfMh7S9R46szmeX4cNr3lfdTfr2rZlHKwhaCJgCAKADKFAdffTRLkwtXbrUhYzLL7/cjOf1NGjJzJkzzVknCYNWPCys++4OQ4cmsx9+uO44ofCM1r333mvGi+d74oknJtdff72ZT7MIWgiYAgCgwNZff/3kwAMPdOFFIerpp59OrrrqquTzn/+8GbcZaQQtzweb40aNcl19Vp1JCkOQzkIdeNBBNeP77pYDByZz5sypmad+v3X66afX1MKgdeutt1bfKxwnnO9uu++e3HTTTWZ4swhaCJgCACDndDZq6623Tu677z4XppYsWZJMnz492Xbbbc24aelp0NKlvoMPPjgZN26cuxyomp5buPEmm7jw07dfv5qgpdpmm29eU+8uaPnhg4cMSY46+ujknnvu6TJo7bX33m7eEs6XoIU2MAUAQE6st956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aKFRBK3yi9ugXQha7UXQKpZ4mbbIFJATBC00iqBVfnEbtAtBq70IWsUSL9MWmQJygqCFRhG0yi9ug3YhaLUXQatY4mXaIlNAThC00CiCVvnFbdAuBK32ImgVS7xMW2QKyAmCFhpF0Cq/uA3ahaDVXgStYomXaYtMATnRqUFr4cKVz2PU/b30qB7161E78Xhd0X3D4lrZFS1o6f5Gu+62W1Xad2bXvDTfhx9+uKEHRnd1Hy3/PLY8iNugXdIKWpMmTar233333WZ4mobtsotr73PPOy+59dZbXb9/wHQ8bm8rYtDyN/NtdHnecOONyWGHHWbqXRlSOdbFNT0MfuiOO5p6d8J7b8U3uG1VvExbZArIiU4NWtqY437f1Q1J6w0X3VQ0rnWKIgatuBbuxM8+5xwXfvZc9VBZH5zCcb66//7Jc889l2w+YEC38/L95557ruvfbffdq8OuueYat3P2QUvdKVOmuJtiqn+bL33J1b/xjW+4af144fz9Dn2HoUNd3d8gVf2ebrQZf8ZmxW3QLmkFrXrLSH7yk58kV119dfW1njmpUOafazdz5szkhRdeMHd2v2tVWNt3331dO/Tr39+850knnZRM+NGPaj7DI48+mtx3333V2rHHHuvq/nEveszLlgMHuvXg4osvdvN9+umnk6222qo6jZ7Dp5p/YHVP6L3jZd4uaQStO+64IxlYWRbfPPHE6vp87XXXuWG3TZxY94uMgtaoUaNcOykw+fpjjz3mti1/g1JPQUvbmsbfZfhwV9P7nHX22a5fNzjV+uG3Lb3ntGnTaqbX+GHQmjx5svlcrYiXaYtMATnRiUFLD4EO77yuu6frTup6iLM2pHf++B+urv6wKz5o6eHQy157w8y7zIoYtPxO+7TTTnM1f1DVwWy//fZz/fdWDpB6KK2GaWevmg7E6h5xxBE104V8TfP2B/nzzjvPdXU3anW1sz7kkENcfxi0wvlo56956MxYODx8Tz//++6/33V3Hjas5oBc7/O1Im6DdkkjaOnApxCsg+wll1xilsGZY8a4u3+rPxymkOv71d7hMB+04jYK1Qta6o6trENTp051/RMmTKh5LwWtRythTP0KWnqAdTit7mju59fdezdK842XebukEbTCNgj7tSz05UL98dkjBa2jjz66Zho95iqcNhxf64sexRPOa/z48dWgFYY5P9yfBd+h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psUrXyviQHXTTTeZceLxZs+ebYbnWdGC1ty5c5Orrr7a9e88bJgZ3oowaLXT888/n4wbN871P/TQQ8msWbNcf7ye9bYsD9hZBK3TTjutWlPIjacLl3/e2qIZWbZbGkHrxRdfdP0/njo1efjhh804zcg6aHW1nhC0UCCm0LR45WtFvDF1F7QGbb21mUY7db32B9cf/vCHbuei2u233+5q/ludPwBsvMkm7rXowKzac889VzPO448/Xv2WHn+WZhUtaNX7m++9997q8unXv39ydSWIHTdqlKtdf/311eV5+OGHJyN23dWdLdJrdTW9D1oDt9rK1Q859NDkuuuuq07n30dt9eJLL9XUdJYkbBvt5OLpuvrs/nU4ftzvx71t4kT32u+I9Zn9uFpnptxxR3Lqqae61/2/+EXz3s3QPOK2a5esg5a2pXg6jXfPPfdU+88880zXr21Dr9XVay37H65an9Tuqj322GM14/h5hO14Y2W/Eb4+6uijkwkTJlRfpyXLdkszaIlfFn65yF577+22uXicY77xDdcfhmYftIbtskvNshad+Q7H1xWIK6+80tVGjx5txtdwvfb7+2eeeaY6zkknn5zccMMN1dfxGec4aIWfp2+/fq7m9xnaN/nx/Djh39sqghYaZApNi1e+VoQbn3QVtAZssYXbQHYZPjw555xzkiuuuKI6zG+06lfQqjfv2ZVvc9PuvNP1hzsPbZDaUMP30nQKWtttv31NvVVFClrbfOlLdb/xnXLKKdV+LR8FrWNXXSIKl7OWrYKWgple68A8s3JgDs9o6dKRgpb6dcBV+yl0hfPa/2tfS26++ebkmyeeWPM5tEMPz7I9/fTT1X6Fn3h98q/D+g5Dh1b7delQ3fvuuy85rBISw3mFy0HTK2j19ODnaX5x27VL2kHrgQceSA497DDHL1cFLX8g22+//cx0d/z4xzVtEC7bpyrt/8gjj7jtLaz7YCYTJ01y2+TwESOSa665plr381Rg8DWtEwpat1YOhuFnSEOW7dbTda2roHXEkUeamg+1++y7b7L3yJHJ9BkzzDg+aIXt6PvD7VtfxLRNq+a/1Pphov243+60L1CQUtCK5xlP58VBK7wsHU6j9cCHqjCk19u/NYughQaZQtPila8V8cbUVdASnX3yG4m+NYcHVt+Ng9bmAwZUg9WWAwe67kEHH+x2LJrXMccc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>