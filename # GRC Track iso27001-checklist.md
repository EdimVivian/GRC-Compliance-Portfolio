# ISO 27001 Compliance Checklist
**Framework:** ISO 27001:2022 Information Security Management System  
**Assessor:** [Vivian Edim]  
**Date:** [28/04/2026]  
**Control Domain:** Access Control (Annex A 5.15 to 5.18)

---

## About ISO 27001

Write 3 to 5 sentences in your own words explaining what ISO 27001 is, why organisations pursue it, and what problem it is trying to solve. Do not copy from the internet. Explain it as if you were telling a colleague who has never heard of it.

ISO 27001 is like a rulebook that helps companies keep their important informations safe, just like locking your door or house so that starangers can't walk in. It tells organisations what they must do to protect sensistive infrmation like passwords, customer data, and computer from being misused or stolen. ISO 27001 can also be describe as a safety checklist that makes sure everyone follows the same good habits.
Organisationsations pursue because ISO 27001 protects information in every form, be it paper, digital or cloud, ISO 27001 helps organizations become risk-aware and proactively identify and address weaknesses. it encourages companies to protect information by looking at everything together; like the people who use it, the rules thry follow, and the technology they rely on.
The problem ISO 27001 has come to solve or is trying to solve basically trying to offer a complete, organised way to keep information safe and businesses ans organisations resillient to cyberattacks.


## About the Control Domain You Are Assessing

Write 2 to 3 sentences explaining what Access Control means in the context of information security. Why does it matter? What could go wrong if an organisation gets it wrong?

Access control in Information Security simply means one is  making sure that only the right person/people can get or have access into the right information or system.
It is just like giving keys only to the people who should have access to a room. 
It is very important because this control helps an organisation decide who is allowed to see, use, or modify certain onformation with permission, and who is not.
If access control is weak, anyone could access anything, which can lead to data leaks, fraud, stolen information, or even full system compromise. Mistakes become harder to trace because you can’t tell who did what, and the organisation could face legal trouble, financial loss, or reputational damage.
Former employees might still have access and misuse it.

## SecureNow Ltd - Company Profile

Read this carefully before you begin. You will use this information to make your pass, fail, or partial judgments.

**Company:** SecureNow Ltd  
**Size:** 52 employees  
**Sector:** Financial technology (fintech), UK based  
**Infrastructure:** Google Workspace for email and documents, AWS for hosting customer data, Slack for internal communication, a third party payroll system, and a CRM tool used by the sales team  
**Working arrangements:** Fully remote. Staff use a mix of company issued laptops and personal devices. No policy has been issued about personal device use  
**Security team:** None. The Office Manager handles IT requests. There is no dedicated security, GRC, or IT team  
**Existing documentation:** A one page IT policy written in 2019 that covers acceptable use of company email. It has never been reviewed or updated  
**Access management:** When a new employee joins, the Office Manager creates their Google account and manually shares relevant folders. There is no formal access request or approval process. When staff leave, accounts are deactivated only when someone notices the person is no longer responding to emails, which has taken anywhere from 3 days to 6 weeks  
**Privileged access:** Three members of the leadership team have admin access to AWS. One of them left the company 4 months ago. His account was deactivated in Google Workspace but no one checked AWS  
**Passwords:** Google Workspace enforces a minimum 8 character password. MFA is enabled on Google Workspace but is optional and only 60 percent of staff have turned it on. AWS has no MFA enforced. The CRM and payroll systems have no MFA and passwords are shared in a Slack channel called passwords-internal  
**Recent incident:** A sales employee left 3 months ago. Two weeks after her departure, someone used her CRM login to export the full customer contact list. The company is not sure if it was her or someone who had access to the shared Slack channel. No formal investigation was conducted  

## Compliance Checklist

For each control below, read the requirement carefully. Then look at the SecureNow Ltd profile and decide:

- **PASS** - The company clearly meets this requirement with evidence to support it  
- **PARTIAL** - The company has something in place but it is incomplete, outdated, or inconsistently applied  
- **FAIL** - The company does not meet this requirement at all  

Do not guess. Base every judgment on specific details from the company profile above. If you are unsure, explain why it is difficult to judge and what additional information you would need.

### Control A.5.15 - Access Control Policy

**What this requires:** The organisation must have a documented policy that defines rules for granting, managing, and revoking access to systems and information. The policy must be reviewed regularly and communicated to staff.

| Field       | Your Response |
| **Status**  | PARTIAL|

| **Evidence from the profile** | What specific detail from SecureNow Ltd supports your judgment? |
There is a one-page IT policy writtten in 2019 that only covers how the company can use email but has never being updated. 
Former employees still have access to systems
Passwords are shared in Slack
MFA is optional
Also, I noticed there is no mention of formal access request or any approval process.

| **Your reasoning** | Why did you choose this status? Be specific |
No recent written IT policy, the writtren policy of 2019 that only exist on paper which is only limited in scope and is outdated too.
No indicationn that an access control policy is being enforced in their day-to-day practice and non is communicated to staff as well which can lead to data leak or stolen information.
It doesnt set or define clear rules for granting, revoking, managing to system and information, and its not regularly reviewed.
SecureNow Ltd as a Fintech company that has customer PII is not followiing the standard set by ISO 27001 of protecting data and customer information. 
This is nowhere close to a compliant access control policy. To me, the right judgement is PARTIAL, no PASS.

| **Gap (if any)** | What exactly is missing or insufficient? |
A big gap exist in SecureNow Ltd, no up-to-date acess control policy in place taht covers how access is requested, granted, reviewed and revoked for all sysytems.
There is no dedicated security, GRC, or IT team.  

**Think about this:** The company has a 2019 IT policy. Does having any written document automatically mean this control passes? What would a proper access control policy need to include that this one likely does not?

NO. absolutly not. Following the ISO 270001 statndard that cares about qaulity and actual standard performance, an 2019 outdated one-page IT policy that only talks about email
use and has never being reviewed **does nOt** meet the requirement for an Access Control Policy.
A real caccess control should clearly state and explained how access is managed from start to finisg, clearly outlining its aim and scope, 
for example What systems and data the policy applies to Google Workspace, AWS, CRM, payroll, Slack, personal devices, etc. It should include roles ond
responsibilities of who approves, grants, review or revoke access, access request and approval process with documented evidence, how access is assigned and denied, 
how personal devices at work place, how access is can be tracked to help detect suspicious activities and lastly how often policies are reviewed.

### Control A.5.16 - Identity Management

**What this requires:** The organisation must have a defined process for the full lifecycle of user identities. This includes how accounts are created, modified, and removed. Every user must have a unique identity and shared accounts must be controlled and justified.

| Field        | Your Response |
| **Status**   |FAIL |

| **Evidence from the profile** | What specific detail from SecureNow Ltd supports your judgment? |
Staff accounts remain nactive long \fter people leave the organisation
A former senior colleague leader still has AWS admin access four months fter leaving
No structured process for requesting or having access to system or information
New accunt are creted by the office manager with no documented procedure or approvals
No IT or GRC team exists in the company to oversee user account or identity related risks and issues.

| **Your reasoning** | Why did you choose this status? Be specific |
SecureNow’s approach to managing user identities is almost entirely informal. 
Accounts are created and removed whenever someone remembers, rather than following a defined process.
Because there’s no joiner–mover–leaver workflow, the company cannot reliably say who has access to what — or whether that access is still appropriate. 
The fact that an ex‑employee still has admin‑level access to AWS shows that identity management is not functioning in a safe or controlled way. 
For these reasons, the requirement is not met.

| **Gap (if any)** | What exactly is missing or insufficient? |

They also need someone responsible for managing this process, plus regular reviews to make sure access stays accurate and up to date.
To meet this control, SecureNow would need a clear identity lifecycle process that covers how accounts are created, approved, changed, and removed across all systems. 

**Think about this:** The company shares passwords in a Slack channel. Shared credentials mean multiple people can act under one identity. 

What does this mean for accountability? What happens when something goes wrong and you cannot trace who did what?

> Your answer here
lack is a work place messaging app.
> Its basiically a group chat where multiple people in the company can see and send messages.
> Its like a shared room where everyone can poats information,so if a password is posted in slack channel, everyone in that channel can see it.
> when a company shares the password in a slack channel, everyone who uses that login looks exactly the same inside the system.
> ISO 270001 requires organistantion to be able to identify user individually, but shared passwords or credentials make that impossible and one cannot trace action back to a spcific person.
>What this means for accountability is that you cannot take corrective actions
> You cannot meet ISo 270001's requirement for traceability and responsibility and when accountability disappears
in an organisation so does the ability to detect misuse, respond to incidents or demonstrate compliance.

### Control A.5.17 - Authentication Information

**What this requires:** The organisation must manage authentication information such as passwords and MFA tokens securely. This includes having a policy on password strength, protecting credentials from disclosure, and ensuring staff do not share authentication details.

| Field      | Your Response |
| **Status** | FAIL |

| **Evidence from the profile** | What specific detail from SecureNow Ltd supports your judgment? |
AWS has no MFA enforced.
MFa is optional on Google workspace and only 605 of staff have enabled it
Google worrkspace enforces only a minimum of 8 character password.
password are resused and shared, no control n place or management policy controlling aunthenticatoion practices.
CRM and payroll systems ahve no MfA and their credential are shared in a an open workplace messaging app called slack.

| **Your reasoning** | Why did you choose this status? Be specific |
> At secureNow, anyone with acces to the slack channel or a reused password can log in as another ''user'' or a shared account.
> That alone has destroyed accountability, undermines audit logs and amke incident investigation impossible.
> Moreso, ISO 270001 expects authenticatio to relaibly prove who a user is so actions can be traced to an individusl.
> The current setup at SecureNow means authentication is weak in controlling weak passwords, incosistent multifactor protection and shared credential.

| **Gap (if any)** | What exactly is missing or insufficient? |
> Shared passwords in slack must be prohibited ans replaced with uniques user accounts.
> No secret managemnt.
> No enforcemnent of multi‑factor authentication for all accounts
> Stronger password policy and authentication hardening.
> Centralised authentication logging and monitoring should be prioritised.
> Policy, ownership and mandatory training for staff.

**Think about this:** MFA is enabled on Google Workspace but only 60 percent of staff use it. Does enabling a security feature count as implementing it if uptake is voluntary and incomplete? How would you argue this in a real audit?
NO. 
> Having a security feature available is not the same as actually implementing it.
> Turning a control on but leaving it optional does not satisfy ISO 27001 auditors expect controls to be enforced,
> measurable, and auditable, not merely present and unused.
> If only 60% of staff use MFA, an auditor will treat that as an
> implementation gap unless the organisation can show a documented,
> risk‑accepted exception process and evidence of compensating controls.

### Control A.5.18 - Access Rights

**What this requires:** The organisation must ensure that access rights are granted based on the principle of least privilege, meaning staff only have access to what they need to do their job. Access must be reviewed regularly and removed promptly when no longer needed.

| Field      | Your Response |
| **Status** | FAIL |

| **Evidence from the profile** | What specific detail from SecureNow Ltd supports your judgment? |
>At secureNow Ltd, access isgranted informally, that is the office manager creates Google workspace accounts and manually shared folders with no approval workflow.
>accounts for people who no longer work at securenow are only deactiv\ted when someone notices, taking between 3 days and 6 weeks.
>previlege access to systems and informations exist without control, 3 leaders have AWS admin right and one ex leader still retains that acccess 4 months after leaving.
>No formal role definiitions and payroll credentials are shared in slack channel, enabling multiple people to use the same identity.

| **Your reasoning** | Why did you choose this status? Be specific |
>Least privilege means giving people only the permissions they neeed to do their job, for the minimum time required.
>At SecureNow, access is granted on an ad-hoc basis, remains active for a long time after people leave and credentials are shared  which create over previleged accounts (including unmamanaged AWS admin access) and secers the link between access and job function.
>Because there are no role‑based assignments or scheduled reviews, the company cannot demonstrate that users hold only the rights they need,
>—therefore the control is not satisfied.

| **Gap (if any)** | What exactly is missing or insufficient? |
>Crontol for priviledged accounts:admin accounts should be seperated and stricter approvals should be applied to whoever have access to it
>Eliminiation of shared user credentials and clear handling for service accounts.
>Regualar access review process: following documented processes frequency, owners, and remediation steps
>Role or job based access definition: not able to map duties to minimum required previleges
>
**Think about this:** A former employee still has active AWS admin access four months after leaving. The recent CRM incident may have involved a former employee's credentials. These two facts together tell a story. What story is that, and what does it mean for this control?

>Practically, it elevates insider-risk and external-compromise scenarios, undermines auditability, and creates regulatory and contractual exposure.
> Those two facts together tell a single, worrying story: SecureNow’s identity lifecycle is broken.
> An ex‑employee retaining AWS admin rights four months after leaving, plus a CRM breach that may have used a former employee’s credentials,
> shows deprovisioning is unreliable, credentials are effectively shared or reused, and monitoring or alerting failed to detect or prevent misuse.
> For the Access Control domain this means the organisation cannot enforce least privilege, cannot attribute actions to individuals, and cannot
> investigate or contain incidents — all core ISO 27001 requirements. 

# Overall Summary

Write a short paragraph (4 to 6 sentences) summarising your overall assessment of SecureNow Ltd against the Access Control domain. Do not just repeat what you said in each section. Step back and look at the bigger picture. What is the overall maturity level of this organisation when it comes to access control?

>SecureNow’s access control posture is at a low maturity level: practices are informal, inconsistent, and largely reactive rather than governed.
>Privileged access is unmanaged and deprovisioning is slow, creating clear opportunities for misuse and undetected data exposure.
>Remediation is straightforward and urgent: enforce unique identities, ban shared passwords, mandate MFA, define role‑based privileges, and implement timely deprovisioning with audit trails.
>Shared credentials, optional MFA, and manual, ad‑hoc provisioning mean the company cannot reliably prove who has access to sensitive systems or that those rights are appropriate.
>Until those basecis are in place and demonstrably operating, Securenow cannot meet ISO 270001 expectations for acess control.

## Critical Thinking Questions

Answer each question in 3 to 5 sentences. These require your own judgment. There is no single correct answer but your reasoning must be logical and grounded in what you know about the framework and the company.

**Question 1:** If you were a GRC analyst presenting to the board of SecureNow Ltd, what would you say is the single highest priority risk they need to address this month and why? What would happen if they did not act on it?

>The single highest  - priority is uncontrolled identity and previleged access, where stale or shared credentials and ad‑hoc provisioning allow anyone to act with elevated rights and evade attribution.
>This gap creates an immediate threat of data exfiltration or destructive changes (whether malicious or accidental) and prevents reliable incident investigation or regulatory reporting.
>Remediation must be immediate and focused: revoke any former‑employee access, rotate exposed credentials, remove passwords from Slack, and enforce unique accounts plus mandatory MFA for all privileged systems.
>Until identity lifecycle and privileged‑access controls are fixed and demonstrably operating, SecureNow remains exposed to high‑impact insider misuse and external compromise.

**Question 2:** The company has MFA enabled on Google Workspace. A senior leader argues this means the company is compliant with authentication requirements. How would you respond to that argument? What would you show them to prove your point?

If a senior leader argues “MFA is enabled, so we’re compliant,” I would push back on two fronts: governance and evidence. ISO‑style assessment treats a control as implemented only when it is applied consistently to the systems and user classes in scope,
and when the organisation can produce objective, auditable proof that the control is working as intended.
Simply having the capability switched on but allowing voluntary uptake leaves high‑risk accounts exposed and fails the “applied” requirement in Annex A (secure authentication).
Auditors now expect enforcement, coverage mapping, and an exceptions register, not a checkbox.
> To make this concretfor the board, i would show 5 (five) piecese of evidence that prove weather MFA is trly implented or merely avaialable:
> Coverage matrix: an exportable list showing which systems are in scope (Google Workspace, AWS, CRM, payroll, VPN) and whether MFA is enforced or merely available for each. This maps the control to risk and is a basic ISO artifact.
> Technical enforcement proof: screenshots or exported configuration from the IdP/SSO and from AWS showing conditional access or MFA enforcement rules (policy names, scope, and timestamps). This proves the setting is active, not aspirational.
> Uptake metrics and exception register: a current report showing the percentage of users with MFA enabled, plus a documented list of named exceptions with risk acceptance, owner, and expiry date. If uptake is 60% and exceptions are undocumented, auditors will flag non‑conformity.
> Authentication logs and alerts: exported auth logs showing successful/failed MFA events, admin logins, and any conditional‑access blocks; evidence that these logs are collected centrally and reviewed. Auditors want to see that enforcement produces observable outcomes.
> Privileged account proof: explicit evidence that privileged paths (AWS console, admin portals) require MFA and that any privileged accounts without MFA are in a time‑boxed remediation plan. Annex A treats privileged access as high priority.

**Question 3:** The recent CRM incident is concerning but no formal investigation was done. From a GRC perspective, why does that matter beyond the incident itself? What does it say about the organisation's security culture? 

> Failing to investigate the CRM incident shows SecureNow isn’t treating security as a disciplined, accountable function.
> It means the company lost the chance to understand what happened, fix the root cause, and prevent a repeat, turning one incident into an ongoing, unmanaged risk.
> It also signals a culture where issues are ignored rather than examined, which discourages reporting and weakens trust in governance.
> Ultimately, it reflects an immature security culture where accountability, learning, and continuous improvement are missing.

**Question 4:** What evidence would you ask SecureNow Ltd to provide to verify whether each control is actually working, not just documented? List at least two pieces of evidence per control.

1. Identity Management
Undsr this section i would be verifying: Joiner–Mover–Leaver (JML) processes work in practice.

List of evidence to request:
>JML logs or tickets showing who requested access, who approved it, and when it was provisioned.
>Leaver reports showing accounts disabled on or before the termination date (sample 5–10 recent leavers).
>List of all active accounts compared against HR’s list of active employees (to detect ghost accounts).

2. Access Control Policy
Here i would be verifying if the policy exists, is current, and is being followed.

Ask for at least two pieces of evidence:
>Version‑controlled policy with review history (showing last review date, approver, and change log).
>Evidence of communication and adoption, e.g., onboarding checklist, training records, or staff acknowledgement logs.
>Sample audit of compliance, such as a spot‑check showing whether actual access practices match the policy.
>
3. Access Rights
 What to verify: Least privilege, role‑based access, and regular reviews.
Evidence to ask for:
>Role‑based access matrix mapping job roles to required systems and privilege levels.
>Quarterly access review records showing who reviewed access, what was removed, and why.

4. Authentication Information
   What to verify: Authentication controls (passwords, MFA, secrets) are enforced, not optional.

Pieces of evidence:
>MFA enforcement configuration from Google Workspace, AWS, CRM, and payroll (screenshots or exported policy settings).
>MFA coverage report showing percentage of users with MFA enabled and any documented exceptions.
>Password manager/secrets vault logs showing access to shared credentials and rotation history.
>Authentication logs showing MFA challenges, failed logins, and privileged login events.


*Template provided by CyberShift With Funke | Cohort 1 Assignment*
