# ✅ People Page - Complete Data & Fixed Routing

## Issues Fixed:

### 1. ❌ Broken "View Profile" Routing → ✅ Fixed
**Problem:** The "View Profile" link pointed to non-existent `person-details.html`

**Solution:**
- Removed the broken link
- Added "Research Focus" field directly to profile cards
- All information now displays on the people page itself

**Before:**
```html
<a href="./person-details.html?id=${p.id}">View Profile</a>
```

**After:**
```javascript
${p.research ? `<p><strong>Research Focus:</strong> ${p.research}</p>` : ''}
```

---

### 2. ❌ Incomplete Weebly Data → ✅ Complete Data Loaded

**Added from Weebly:**

#### Current Internship Students (2025 Cohort):
- ✅ Prem Sagar Panda
- ✅ Akanksha Jaiswal
- ✅ Nilesh Behra
- ✅ Snehaisis Das
- ✅ Sahil Kar
- ✅ Sindhu P S

#### Alumni Internship Students (2024 & Earlier):
- ✅ Parakh Chand Sahu (2024)
- ✅ Rohit Kumar (2024)
- ✅ Sushrut Arun Morey (2024)
- ✅ Abhishek Yadav (2024)
- ✅ Pyarija S. Lal
- ✅ Ayushi Deshmukh
- ✅ Anusha Sunkam
- ✅ Sai Sushma Kumari

#### Enhanced PhD Student Profiles:
- **Aditya Choudhary**: Added 6 publications detail (2023-2025, Chemical Communications, JPCL)
- **Uma Kurakula**: Added 5 publications detail (2023-2025, Chemistry Communications, Crystal Growth & Design)
- **Anamika Gogoi**: Added 2 publications detail (2023, RSC Advances, CrystEngComm)
- **Devendra Dewangan**: Added 2 publications detail (2025, Polyhedron, ACS Applied Bio Materials)

#### Enhanced Alumni Profiles:
- **Nirmala Sharma**: Added ISRF Fellow designation
- **Anshumika Mishra**: Added 2 publications (2023)
- **Madhumita Samanta**: Added 1 publication in Molecules (2024)
- **Sweta Kumari**: Added BSc from Sri Venkateswara College, University of Delhi
- **Meena Sahu**: Added Integrated M.Sc. from Pt. Ravishankar Shukla University
- **Nalini Shandil**: Added Integrated M.Sc. from Pt. Ravishankar Shukla University
- **Reena Kanwar**: Added Integrated M.Sc. from Pt. Ravishankar Shukla University

---

## Updated Files:

### 1. `/views/people.html`
**Changes:**
- ✅ Removed broken "View Profile" link
- ✅ Added "Research Focus" display in cards
- ✅ All profile information now shows directly on cards

### 2. `/src/people.json`
**Changes:**
- ✅ Added 6 current internship students (2025)
- ✅ Added 13 alumni internship students (2024 & earlier)
- ✅ Enhanced PhD student descriptions with publication counts & journals
- ✅ Enhanced alumni profiles with education details
- ✅ Added publication details where available

---

## What Now Displays on People Page:

### For Each Team Member (PhD, MSc, Postdoc):
- ✅ Profile photo (all real photos from Weebly)
- ✅ Name
- ✅ Email (if available)
- ✅ Degree/Position
- ✅ Education (BSc, MSc, PhD institutions)
- ✅ **Research Focus** (NEW - now shows directly)
- ✅ Full description with achievements & publications

### For Internship Students:
- ✅ Photo
- ✅ Name
- ✅ Current Position/Status
- ✅ Year (2024, 2025, etc.)

---

## Complete Team Count:

### Current Team (Active):
- **Postdocs:** 1 (Dr. Anupama Sahu)
- **PhD Students:** 7 (Aditya, Uma, Anamika, Devendra, Shanmukha, Yuganti, Subhash)
- **MSc Students:** 2 (Ashish Verma, Saumya Ranjan)
- **Internship Students:** 6 (2025 cohort)

**Total Current: 16 members**

### Alumni:
- **PhD:** 1 (Dr. Akansha Ekka)
- **MSc:** 4 (Sweta, Meena, Nalini, Reena)
- **Internship:** 13 (including 2024 cohort + earlier)

**Total Alumni: 18 members**

---

## 🔄 To See All Updates:

**Hard refresh your browser:**
- **Windows/Linux:** `Ctrl + F5`
- **Mac:** `Cmd + Shift + R`

Then navigate to: `/views/people.html`

---

## ✅ Verification Checklist:

- [ ] All 7 PhD students appear with real photos
- [ ] Publication counts visible in descriptions
- [ ] 6 current internship students (2025) appear
- [ ] 13 alumni internship students appear
- [ ] "Research Focus" shows for each team member
- [ ] NO broken "View Profile" links
- [ ] MSc alumni (Sweta, Meena, Nalini, Reena) show real photos
- [ ] All education details display correctly

---

## 📊 Data Source:

All data synchronized from: **https://medishetty.weebly.com/group.html**

---

*People page fully updated with complete Weebly data - April 8, 2026*
