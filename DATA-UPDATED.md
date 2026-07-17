# ✅ Data Files Updated with Weebly Content

## Files Now Using Local JSON:

### 1. People Page (/views/people.html)
**Fetches from:** `../src/people.json`

**Updated with:**
- ✅ **Postdoc:** Dr. Anupama Sahu (Battery materials specialist)
- ✅ **7 PhD Students:**
  - Aditya Choudhary (PMRF, 6 pubs, Best Poster Award NSC-51)
  - Uma Kurakula (5 pubs)
  - Anamika Gogoi (2 pubs)
  - Devendra Dewangan (2 pubs)
  - Abothu Shanmukha Rao
  - Yuganti Bai
  - Subhash Kumar Chakradhari
- ✅ **MSc Students:** Ashish Verma, Saumya Ranjan
- ✅ **Alumni:** Dr. Akansha Ekka (PhD 2025), and others

---

### 2. PI Profile Page (/views/raghavender.html)
**Fetches from:** `../src/medishetty.json`

**Updated with:**
- ✅ Name: Dr. Raghavender Medishetty
- ✅ Position: Assistant Professor, Chemistry
- ✅ Head of Department: Materials Science & Metallurgical Engg
- ✅ Office: Science Building SD1, Level 3, Room 411
- ✅ Phone: +91-771-255-1300, Ext 6142
- ✅ Email: [email protected]
- ✅ Top 2% cited scientist globally

---

### 3. Homepage (/index.html)
**Fetches from:** `./src/achievements-data.json`

**Updated with:**
- ✅ Dr. Akansha Ekka PhD Defense (May 2025)
- ✅ Best Poster Award - Aditya Choudhary (Dec 2024)
- ✅ Faculty achievements (Top 2% scientist, SERB funding)

---

### 4. Publications (/views/publications.html)
**Fetches from:** `../src/publications.json`
- ✅ Using local publications data

---

### 5. Lab Facilities (/views/lab.html)
**Fetches from:** `../src/lab.json`
- ✅ Lab equipment data loaded locally

---

### 6. Gallery (/views/gallery.html)
**Fetches from:** `../src/gallery.json`
- ✅ Gallery images loaded locally

---

## 🔄 How to See the New Data:

1. **Hard Refresh your browser:**
   - **Windows/Linux:** Ctrl + F5 or Ctrl + Shift + R
   - **Mac:** Cmd + Shift + R

2. **Or Clear Browser Cache:**
   - Open Developer Tools (F12)
   - Right-click the refresh button → "Empty Cache and Hard Reload"

3. **Check the Network Tab:**
   - Open DevTools (F12) → Network tab
   - Refresh the page
   - Look for requests to `people.json`, `medishetty.json`, etc.
   - Should NOT see any requests to Google Sheets script URL

---

## ✅ Verification Checklist:

Go to each page and verify the new data:

- [ ] **People page** → Should show Dr. Anupama Sahu, Aditya Choudhary, Uma Kurakula, etc.
- [ ] **Raghavender page** → Should show Room 411, correct phone number
- [ ] **Homepage** → Should show recent achievements
- [ ] **Footer** → Should show SD1-411, correct contact info

---

## 🚫 No More Google Sheets!

All pages now load data from local JSON files in `/src/` directory.
No external API calls to Google Sheets.

---

*If you still see old data after hard refresh, check browser console (F12) for errors.*
