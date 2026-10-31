1. Core Ideas


- **Information** is a report, alert, indicator, or observation.
- **Intelligence** is information analysed in context to help someone make a decision.
- **An intelligence requirement** is the decision-relevant question you need to answer.
- **An IOC****** is an observable artefact—such as a file hash, domain, or IP address—that may indicate activity. It needs context and validation; by itself, it doesn’t explain the threat.
- **TTPs** describe how an adversary operates: its tactics, techniques, and procedures. They can often provide more durable context than a single indicator.
  
CTI work is cyclical: establish what a stakeholder needs, collect and analyse relevant information, share useful findings, then use feedback to improve the next round.

A useful rule of thumb: **start with the decision, not with a threat feed or a threat actor’s name.**


**Threat Intel Lifecycle**


- threat intel must add value to an organisation
- threat intelligence production is a **multi-step, cyclical process — not a point-in-time task.**
- intelligence should be actionable for everyone - whether they’re staffing a SOC, responding to security incidents, managing vulnerabilities, analyzing third-party risk, protecting your digital brand, or making high-level security decisions.


**Phases of the Intel Lifecycle**

- Traditional intelligence focuses on six distinct phases that make up what is called the “intelligence cycle”: direction, collection, processing, analysis, dissemination, and feedback.


<img width="900" height="600" alt="image" src="https://github.com/user-attachments/assets/861c56e7-9279-42ed-8737-bac156662dee" />



**1. Direction**


- Setting goals for the TI program
- Articulating: information assets and business processes that need to be protected, the potential impacts of losing those assets or interrupting those processes, types of threat intelligence that the security organization requires to protect assets and respond to emerging threats, and priorities about what to protect
- Organisation can then formulate questions that channel the need for info into discrete requirements. For eg. “Which threat actors on underground forums are actively soliciting data concerning our organization?” may be asked if the goal is to understand who the likely adversaries are. 


**2. Collection**


- gathering info to address intel requirements
- various means including: Pulling metadata and logs from internal networks and security devices, threat feeds from vendors etc, open source news/blogs, scraping websites and forums, and infiltrating closed sources such as dark web forums.
- may contain raw data such as malware signatures or leaked credentials from paste sites.

**3. Processing**


- transformation of info into usable format
- eg. extract IP address from vendor report --> CSV file for importing to SIEM
- eg. indicator enrichment --> EPP tools for auto blocking.


**4. Analysis**


- Analysis is a human process that turns processed information into intelligence that can inform decisions.
- reports for non-technical leaders should: articulate the issues in business terms (such as direct and indirect costs and impact on reputation),and include a recommended course of action
- Successful cyber threat intelligence teams provide continual technical reporting to other security teams with external context around IOCs, malware, threat actors, vulnerabilities, and threat trends.


**5. Dissemination**


- involves getting the finished intelligence output to the places it needs to go. 
- for each of the intel audiences, you should ask: What threat intelligence do they need, and how can external information support their activities, how should the intelligence be presented to make it easily understandable and actionable for that audience, how often should we provide updates and other information, through what media should the intelligence be disseminated, and ow should we follow up if they have questions.


**6. Feedback**


- it is critically important to understand your overall intelligence priorities and the requirements of the security teams that will be consuming the threat intelligence. 
- their needs tell you: what types of data to collect, how to process and enrich the data to turn it into useful information, how to analyze the information and present it as actionable threat intelligence, and to whom each type of intelligence must be disseminated, how quickly it needs to be disseminated, and how fast to respond to questions.
- regular feedback to understand requirements of each group, and to make adjustments as their requirements and priorities change.
