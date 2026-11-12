# USE CASE TEMPLATE:
# Use Case: [Brief Title / Persona Goal]

### Who is the User?
*   **Persona/Role:** [Name/Job Title]
*   **Context:** [Brief background on who they are within the ecosystem]

###  What Do They Want to Do with the Tool?
*   **Primary Tasks:** 
    *   [Task 1]
    *   [Task 2]
*   **Operational Workflows:**
    *   *Standard Operations:* [How they interact under normal conditions]
    *   *Edge/Exception Operations:* [How they interact during anomalies or emergencies]

### What Needs and Desires Do They Have for the Tool?
*   **Functional Needs:** [What the interface/system *must* provide or expose to them]
*   **Desires / Experience Preferences:** [How they expect the tool to behave or guide them]

### What is Their Skill Level?
*   **Technical Proficiency:** [Low / Medium / High / Expert]
*   **Domain Knowledge:** [What specific operational skills or domain-specific knowledge they possess]


Use case: 
Researchers: Priority on understanding model and results to aid research and development of similar tools.

Lucy Draft:
access timeseries of water quality parameters
- parameters include N, P, DO, temp, bacteria, dominant algea, dominant plankton

user:
-Jill works at KCDNR
-She wants to pull water quality data to investigate a correlation between water quality in the lake and dominant plankton populations

Primary Tasks:
- list in understandable way, which parameters are relevant in the lake
- identify which parameters are 'non-normal' from 'typical' levels
- easily access data

Operational Workflows:
- computer: load package
- user: select dataset for observation
- computer: extract relevant parameters
- user: download data

Implied:
- datasets are preloaded and ready to be accessed by package
