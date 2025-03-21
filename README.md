#


# Documentation for Geetika, Siddharth, Vaishnavi

| **Variable**           | **Type**        | **Code / Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | **Dependent/Independent** |
|------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| **migration_1**        | Categorical     | **Life‐course migration indicator** <br>• **0**: No migration <br>• **1**: Childhood migration <br>• **2**: Adult migration                                                                                                                                                                                                                                                                                                                                                         | Independent                |
| **migration_2**        | Binary          | **Hard threshold indicator based on duration of residence:**<br>• **1**: Migrant (respondent has lived continuously in the current area for less than 20 (THRESHOLD) years).<br>• **0**: Non‐migrant (respondent has lived 20 (THRESHOLD) years or more in the current area).                                                                                                                                                                                                                                              | Independent                |
| **migration_3**        | Ordinal         | **Duration‐based migration indicator** (using “Since how many years living continuously in this area”):<br>• **1**: 0–2 years<br>• **2**: 3–5 years<br>• **3**: 6–10 years<br>• **4**: 11–20 years<br>• **5**: 21–40 years<br>• **6**: More than 40 years                                                                                                                                                                                                                                                                    | Independent                |
| **migration_4**        | Categorical     | **Rural/Urban migration type** (based on rural/urban codes for “Place of Birth” and “Place of Last Residence”):<br>• **1**: Rural-to-Rural<br>• **2**: Rural-to-Urban<br>• **3**: Urban-to-Rural<br>• **4**: Urban-to-Urban<br>• **0**: Missing/undefined (if either location is missing)                                                                                                                                                                                                                                  | Independent                |
| **CIDI_1**             | Numeric (Score) | **Depression score from CIDI-SF (Part 1):** Sum of “Yes” responses to items MH204–MH211.                                                                                                                                                                                                                                                                                                                                                                                           | Ignore this                |
| **CIDI_2**             | Numeric (Score) | **Depression score from CIDI-SF (Part 2):** Sum of “Yes” responses to items MH217–MH222. This score is used as a complementary measure of depression.                                                                                                                                                                                                                                                                                                                             | Ignore this                |
| **Depression**         | Binary          | **Depression outcome variable:**<br>• **1**: The respondent is considered at risk for depression (CIDI_1 score ≥ 3).<br>• **0**: Otherwise.                                                                                                                                                                                                                                                                                                                                         | Dependent                |
| **education**          | Ordinal         | **Educational attainment** (derived from DM008, with DM006 “Ever attended school” check):<br>• **0**: Did not attend school or DM006 ≠ 1<br>• **1**: Less than primary school (Standard 1–4)<br>• **2**: Primary school completed (Standard 5–7)<br>• **3**: Middle school completed (Standard 8–9)<br>• **4**: Secondary/Matriculation completed<br>• **5**: Higher secondary/Intermediate and above (Diploma, Graduate, Postgraduate, or Professional course)                | Independent and Controlling Variable                |
| **living_arrangements**| Ordinal         | **Satisfaction with current living arrangements** (from FS329):<br>• **1**: Strongly dissatisfied<br>• **2**: Dissatisfied<br>• **3**: Neither satisfied nor dissatisfied<br>• **4**: Satisfied<br>• **5**: Strongly satisfied                                                                                                                                                                                                                                                        | Independent and Controlling Variable                |
| **mpce_quintile**      | Ordinal         | **Monthly Per Capita Consumption Expenditure (MPCE) Quintile**:<br>• **1**: Lowest quintile<br>• **2**: Second quintile<br>• **3**: Middle quintile<br>• **4**: Fourth quintile<br>• **5**: Highest quintile                                                                                                                                                                                                                                                                         | Independent and Controlling Variable                |
| **age_category**       | Ordinal         | **Age group** (derived from “Age at last birthday”):<br>• **1**: 45–55 years<br>• **2**: 55–65 years<br>• **3**: 65–75 years<br>• **4**: 75–85 years<br>• **5**: Over 85 years                                                                                                                                                                                                                                                                                                       | Independent and Controlling Variable                |

---


 Project Repository

## CSV Files for File 3
The CSV files for **File 3** can be accessed from the following Google Drive link:

🔗 [Drive Link for CSV Files](https://drive.google.com/drive/folders/1bjhp5GcQb5csw0TchRRKFm50MRK5IFTt?usp=sharing)

## LASI Data
[States and UT](https://drive.google.com/file/d/1v-fmR8FvbdewiGTTrMkzCDGcEIR2NF1i/view?usp=sharing)
[Metro](https://drive.google.com/file/d/15kzxxQTinp5zOWXh-ICuJyNPw3_aE5uX/view?usp=sharing)

---

## Folder Structure

```
📂 Project Root/
│── .gitignore ✅ 
│── metro cities/ ❌ (Ignored)
│── redundant/ ✅ (Included)
│── states and ut/ ❌ (Ignored)
│── .ipynb_checkpoints/ ❌ (Ignored)
│── cl3/ ✅ (Included)
│── file3_metro.csv ❌ (Ignored)
│── file3_states.csv ❌ (Ignored)
│── input_metro.ipynb ✅ (Included)
│── input_states.ipynb ✅ (Included)
```

---

Please **include the `metro cities` and `states and ut` folders** before running the code.
