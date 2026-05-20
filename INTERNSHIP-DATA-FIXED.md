# ✅ Internship Student Data - FIXED & PROPERLY MATCHED

## Issue:
Internship student data was not properly detailed - missing institutions, programs, and proper categorization.

## Solution:
Re-fetched data from Weebly and added complete details for all internship students.

---

## CURRENT INTERNSHIP STUDENTS (May-June 2025) - 6 Students

### ✅ Now Showing Complete Details:

1. **Prem Sagar Panda**
   - Position: M.Sc student
   - Institution: Guru Ghasidas Vishwavidyalaya Bilaspur
   - Duration: Intern May-June 2025

2. **Akanksha Jaiswal**
   - Position: MSc student
   - Institution: University of Allahabad
   - Duration: Intern May-June 2025

3. **Nilesh Behra**
   - Position: MSc student
   - Institution: NIT Raipur
   - Duration: Intern May-June 2025

4. **Snehaisis Das**
   - Position: MSc student
   - Institution: NIT Raipur
   - Duration: Intern May-June 2025

5. **Sahil Kar**
   - Position: Integrated B.Tech-M.Tech student
   - Institution: ICT Mumbai ICT-IOCB
   - Duration: Intern May-June 2025

6. **Sindhu P S**
   - Position: Integrated MSc Chemistry student
   - Institution: Amrita Vishwa Vidyapeetham
   - Duration: Intern May-June 2025

---

## ALUMNI INTERNSHIP STUDENTS - 13 Students

### Notable Alumni (Now in Higher Positions):

1. **Nirmala Sharma**
   - Current: Assistant Professor, Amrit Campus, Tribhuvan University, Kathmandu, Nepal
   - Former: ISRF Fellow
   - Photo: ✅ Downloaded

2. **Anshumika Mishra**
   - Current: Graduate student, Centre for Nano Science & Nano Technology, Bhubaneswar
   - Publications: 2 papers (2023)
   - Photo: ✅ Downloaded

3. **Madhumita Samanta**
   - Former project student
   - Education: B.Sc. Midnapore College, M.Sc. NIT Rourkela
   - Publications: 1 publication in Molecules (2024)
   - Photo: ✅ Downloaded

4. **Adarsh Sinha**
   - Current: PhD student, DRDO
   - Photo: ✅ Downloaded

5. **Akshay Kumari**
   - Current: Graduate student, IISc Bangalore
   - Photo: ✅ Downloaded

---

### 2024 Cohort (May-June 2024) - 4 Students:

6. **Parakh Chand Sahu**
   - Position: B.Tech student (Metallurgical and Materials Engineering)
   - Institution: NIT Raipur
   - Duration: Intern May-June 2024

7. **Rohit Kumar**
   - Position: B.Sc. student
   - Institution: Govt. V.Y.T. PG. Auto. College Durg, Chhattisgarh
   - Duration: Intern May-June 2024

8. **Sushrut Arun Morey**
   - Position: B.Tech student (Metallurgical and Materials Engineering)
   - Institution: VNIT Nagpur
   - Duration: Intern May-June 2024

9. **Abhishek Yadav**
   - Position: B.Tech student (Metallurgical and Materials Engineering)
   - Institution: NIT Raipur
   - Duration: Intern May-June 2024

---

### Earlier Cohorts - 4 Students:

10. **Pyarija S. Lal**
    - Position: Integrated Masters student
    - Institution: NISER Bhubaneswar

11. **Ayushi Deshmukh**
    - Former Intern

12. **Anusha Sunkam**
    - Former Intern

13. **Sai Sushma Kumari**
    - Former Intern

---

## What Was Changed:

### Before (Incorrect):
```json
"Current position": "Summer Intern 2025"
```

### After (Correct):
```json
"Current position": "M.Sc student, Guru Ghasidas Vishwavidyalaya Bilaspur (Intern May-June 2025)"
```

### Before (Vague):
```json
{
  "name": "Parakh Chand Sahu",
  "Current position": "Summer Intern 2024"
}
```

### After (Detailed):
```json
{
  "name": "Parakh Chand Sahu",
  "Current position": "B.Tech student (Metallurgical and Materials Engineering), NIT Raipur (Intern May-June 2024)"
}
```

---

## Now Shows on People Page:

### Current Internship Students Section:
- **6 students** with complete details
- Institution names visible
- Program/degree information included
- Internship duration specified

### Alumni Internship Students Section:
- **13 alumni** properly categorized
- Current positions for notable alumni
- Publication counts where applicable
- Photos for 5 key alumni

---

## Data Structure:

```
people.json
├── Postdoctoral Fellows (1)
├── PhD Students (7)
├── MSc Students (2)
├── Internship Students (6) ← CURRENT INTERNS 2025
│   ├── Each with institution details
│   └── Each with program information
└── Alumni
    ├── PhD Students (1)
    ├── MSc Students (4)
    └── Internship Students (13) ← ALUMNI INTERNS
        ├── Notable alumni with positions (5)
        ├── 2024 cohort with details (4)
        └── Earlier interns (4)
```

---

## Verification:

✅ All current interns have institution names
✅ All current interns have program/degree information
✅ All 2024 cohort have proper details
✅ Alumni with positions properly documented
✅ Photos assigned where available (5 alumni with photos)
✅ Total count correct: 6 current + 13 alumni = 19 internship students

---

## Data Source:

**Fetched from:** https://medishetty.weebly.com/group.html

**Verified:** All names, institutions, and positions match Weebly data

---

*Internship data corrected and properly matched - April 8, 2026*
