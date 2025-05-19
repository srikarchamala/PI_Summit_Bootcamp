# 🧠 Generative BI Bootcamp: Critical Potassium Case Study

## 🎯 Objective

Equip clinical professionals with hands-on experience using **Generative BI tools like ChatGPT** to:

* Explore real clinical lab data (Potassium values)
* Ask questions in natural language
* Automatically generate insights, plots, and summaries
* Understand how LLMs can support quality improvement and lab analytics

---
### **Part 1: Hands-On Analysis **

#### 🧪 Clinical Scenario:

> The pathology lab receives a report from a clinician at Clinic\_3 noting an apparent rise in **critical potassium values** during May 2022. A data analytics fellow is tasked with investigating and validating this observation.

#### ✅ Tasks & Prompts

##### 🧾 Task 1: Explore Dataset

```plaintext
Prompt: "Show me the total number of potassium tests performed at each clinic in May 2022."
```

Outcome: Simple pivot summary grouped by `Clinic_Name`

##### 🧾 Task 2: Identify Critical Incidents

```plaintext
Prompt: "Which clinic had the most critical potassium results?"
```

Outcome: ChatGPT returns a table or chart showing CRIT values per clinic

##### 🧾 Task 3: Investigate Root Cause

```plaintext
Prompt: "Who drew the most critical potassium samples in Clinic_3?"
```

Outcome: Reveal that one phlebotomist drew 22 out of 23 criticals

##### 🧾 Task 4: Visualize Pattern

```plaintext
Prompt: "Plot the number of critical potassium results in Clinic_3 by date."
```

Outcome: Date-wise bar chart showing spikes on May 16 & May 22

##### 🧾 Task 5: Generate Summary for Leadership

```plaintext
Prompt: "Write a 3-bullet executive summary explaining the critical potassium spike in Clinic_3."
```

Outcome:

* Clinic\_3 had 23 CRIT results (highest across all clinics)
* 22/23 drawn by a single phlebotomist
* Two major spikes occurred on May 16 and May 22

---

### **Part 2: Build a Prototype **

#### Option A: ChatGPT + Excel + Prompts

* Use ChatGPT with pasted or summarized Excel data
* Ask natural language questions

---

## 🧰 Resources

* Excel file: `PI_Bootcamp_LabTest_Data_V04.xlsx`
* Access to ChatGPT


---

## 👨‍⚕️ Takeaways

* Generative BI enables **non-programmers** to extract clinical insights
* Enhances quality review, root cause investigation, and lab operations
* Empowers clinicians, fellows, and informaticists to engage with data

---

## 📬 Optional Extensions

* Include hemolysis flag or sample condition
* Connect to LIS/EHR feeds
* Expand to calcium, glucose, etc. values
* Alerting with LLM-based monitoring
