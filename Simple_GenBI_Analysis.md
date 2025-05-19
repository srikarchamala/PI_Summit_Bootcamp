# Generative BI Bootcamp: Critical Potassium Case Study

## Objective

Equip clinical professionals with hands-on experience using **Generative BI tools like ChatGPT** to:

* Explore real clinical lab data (Potassium values)
* Ask questions in natural language
* Automatically generate insights, plots, and summaries
* Understand how LLMs can support quality improvement and lab analytics

---

### Build a Prototype

#### ChatGPT + Excel + Prompts

* Use ChatGPT with pasted or summarized Excel data
* Ask natural language questions

---

## Resources

* Excel file: 🔗 [PI_Bootcamp_LabTest_Data_V04.xlsx](https://github.com/srikarchamala/PI_Summit_Bootcamp/blob/main/PI_Bootcamp_LabTest_Data_V04.xlsx)

* Access to ChatGPT
---
### Part 1: Hands-On Analysis

#### Clinical Scenario: Potassium Spike Investigation in Clinic_3

The pathology laboratory at a hospital — servicing four offsite ambulatory clinics (**Clinic1**, **Clinic2**, **Clinic3**, and **Clinic4**) — received a notification from a **Clinic_3 clinician** reporting a **notable rise in critical potassium values** over recent weeks.

To address this concern, the **laboratory leadership** assigned one of their **fellows** to collaborate with the **Data Analytics Team** to:

1. **Validate the observation** from Clinic_3 and confirm whether there is indeed a rise in critical potassium values.
2. **Investigate potential causes** behind any confirmed increases in critical value incidents.

**📊 Data Provided:**  
You are given **potassium test results and related metadata from May 2022** across all four clinics — the period when **Clinic_3 clinicians** reported the spike in critical potassium values.


#### Tasks & Prompts

##### Task 1: Upload the Data File

```plaintext
Step: Drag and drop the Excel file (`PI_Bootcamp_LabTest_Data_V04.xlsx`) into the ChatGPT interface.
Prompt: "Can you load this file and show me a summary of potassium results by clinic?"
```

Outcome: ChatGPT parses and previews data structure (clinic names, result flags, draw dates, etc.)

##### Task 2: Explore Dataset

```plaintext
Prompt: "Show me the total number of potassium tests performed at each clinic in May 2022."
```

Outcome: Simple pivot summary grouped by `Clinic_Name`

##### Task 3: Identify Critical Incidents

```plaintext
Prompt: "Which clinic had the most critical potassium results?"
```

Outcome: ChatGPT returns a table or chart showing CRIT values per clinic

##### Task 4: Investigate Root Cause

```plaintext
Prompt: "Who drew the most critical potassium samples in Clinic_3?"
```

Outcome: Reveal that one phlebotomist drew 22 out of 23 criticals

##### Task 5: Visualize Pattern

```plaintext
Prompt: "Plot a horizontal stacked bar chart with a nested organization clinics first, followed by weeks."
```

Outcome: A clear, hierarchical view of how potassium result flags are distributed over time within each clinic.

##### Task 6: Generate Summary for Leadership

```plaintext
Prompt: "Write a 3-bullet executive summary explaining the critical potassium spike in Clinic_3."
```
Outcome:

- Clinic_3 reported the highest number of critical potassium results (23 CRIT flags), accounting for nearly 19% of its total potassium tests — significantly higher than other clinics.

- Two distinct spikes in CRIT results were observed on May 16 and May 22, indicating a potential cluster of abnormal values within a short timeframe.

- 22 out of the 23 CRIT samples were drawn by a single phlebotomist (Michael Thomas), suggesting a strong possibility of pre-analytical error, such as improper draw technique or hemolysis.


---

## 👨‍⚕️ Takeaways

* Generative BI enables **non-programmers** to extract clinical insights
* Enhances quality review, root cause investigation, and lab operations
* Empowers clinicians, fellows, and informaticists to engage with data

---
