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

# use case: historical time series analyzer (katie draft)
### user:
* historian, data-driven researcher
* this is a researcher who is less interested in predictive future scenarios and more focused on historical record, especially for integration with external research
### what do they want to do:
* primary tasks:
   * view historical ecological / water-quality data through multiple visualizations
   * query specific historical subsets, download raw or filtered datasets in structured formals
   * perform light data transformations within the tool
* operational workflows: interactive charting dashboards, structured data queries
   * edge operations: handling gaps in the record, managing memory limits, managing custom uploaded datasets against the tool's standard format
### what needs and desires:
* functional needs:
   * robust querying support
   * viewable functions to show internal data transformation, plotting logic
   * data export
* desires / preferences:
   * ability to upload own dataset to use in conjunction with the tool
### skil level:
* technical proficiency: medium to high (basic programming, SQL-esque database concepts)
* domain knowledge: strong in historical data analysis, trend interpretation

# Use Case: Casual Viewers (Izzy draft)

### Who is the User?
* **Persona/Role:** recreationalists, non-technical enthusiasts
* **Context:** these are people who do not need very technical or extensive amounts of information from the tool, but simply want to answer basic questions that they are curious about

### What Do They Want to Do with the Tool?
* **Primary Tasks:**
     * input simple commands to answer specific questions they are curious about
     * get general summary information about current lake status
* **Operational Workflows:**
     * *Standard Operations:* using tool’s standard formatting, dataset, and inputs; inputting simple queries or generating summary information well within the bounds of the tool
     * *Edge/Exception Operations:* may occasionally pursue questions/prompts outside the constraints of the tool, especially due to a lack of understanding of its abilities

### What Needs and Desires Do They Have for the Tool?
* **Functional Needs:** ability to input simple prompts to answer simple questions without needing a deep understanding of the tool, ability to provide a simple prompt to generate a range of summary information
* **Desires/Experience Preferences:** user-friendly interface, built-in instructions for how to use the tool

### What is Their Skill Level?
* **Technical Proficiency:** low to medium
* **Domain Knowledge:** few specific skills and little specific knowledge

# Use case: Relationship to Algea and Shad (Ewan Draft)

### Who is the user?
* **Persona/Role:** Researchers, students, professionals
* **Context:** Individuals who are interested in understanding how plankton populations may effect or be effected by algea and shad populations. These individuals may have varying levels of expertise and understanding of the model.

### What do they want to do with this tool?
**Primary Tasks:**
 *Learn about the dynamics between these populations in order to support their work or interest.
 *Produce figures or data related to algea and shad populations in past, present, and potential future conditions.

### Operational Workflow: 
 *Standard operation: manipulate inputs and recieve output related to shad and algea populations
 *Edge/Exceptions: study populations with similar dynamics but not supported in data set. 

 ### What Needs and Desire Do They Have for the Tool?
 *Funtional Needs: Ability to input data and export results and figures.
 *Desire/Experience Preferences: user-friendly interface, ability to customize for specific project

 ### What is their skill level?
 *Technical Proficiency: high
 *Domain Knowledge: high
