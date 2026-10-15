# Homepage Copy for `home-v7.html` (Aligned to Hospital Flyer & Banner)

**Page:** Home
**Maps to:** `output/website-copy/home-v7.html` (section order and CSS class names follow the HTML)
**Source of facts:** Client flyer (Key Features / OPD / Thursday camp / Doctors Available) + "Now Open" banner, cross-checked against `brand-context/`
**Standards applied:** Brand Voice Guide · Zero Negatives Standard · Explanation as institutional standard · No fees · No visiting-specialist names · No unverifiable superlatives

> Designer notes are in `[square brackets]`. Everything else is live copy.
> Sections marked **[NEW]** do not yet exist in `home-v7.html` and need to be built.

---

## ⚠️ FLYER vs. BRAND DOCS: DECISIONS MADE IN THIS COPY

| # | Topic | Flyer says | Brand docs said | Used in this copy |
|---|---|---|---|---|
| 1 | Evening OPD | 5:00 PM – 9:00 PM | 5:00 PM – 10:00 PM | **5 PM – 9 PM** (flyer is the latest client-printed material) |
| 2 | Thursday camp | Free check-up **for pregnant women**, 5–7 PM | Free camp for **every woman**, walk in any time | **Pregnant women, 5–7 PM** |
| 3 | Banner headline | "Best Hospital in Taloja" | Superlatives banned | **Excluded.** Replaced with "Now Open" + specifics |
| 4 | Diagnostics location | "Diagnostic Center Near Hospital" | Same building, ground floor | **Same building, ground floor.** The flyer's building photo shows Mekhale signage on Ridhisha Tower |
| 5 | Visiting doctors | Pediatrician · Medicine · Surgeon | Names withheld | **Specialties only, no names** |
| 6 | Positioning | "Delivery & Multi Specialty" | Women's & maternity hospital | **Women's & maternity first**; multi-specialty support shown through visiting doctors |

Confirm #1 and #2 with Dr. Vaibhavi before launch, since both change what patients will expect.

---

## NAVBAR

**Logo:** Vaibhavi Hospital
**Tagline under logo:** Where Healthcare Meets Humanity `[add back; it is on every flyer and banner]`

**Nav links:** Home · About · Services · Doctors · Insurance · Contact Us

**Right side:**
- 📞 7039330945
- Button: **Book Appointment**

---

## SECTION 1: HERO (`.hero`)

**Eyebrow badge** `[.hero-eyebrow]`
NOW OPEN · TALOJA PHASE 2 · BEHIND PENDHAR METRO

**H1**
Safe Delivery.
Complete Women's Care.
*All Under One Roof.*

**Sub-headline** `[.hero-sub]`
Everything from your first pregnancy scan to your baby's first vaccine happens inside one building, with a doctor who explains every step.
Led by **Dr. Vaibhavi Birle**, MBBS, MS Obstetrics & Gynaecology.

**Trust chips** `[.hero-chips]`
- Lady Gynaecologist
- NICU & ICU On-Site
- 24/7 Emergency
- Govt. Recognised MTP & TL Centre
- Mediclaim Accepted

**Buttons**
- **Free Thursday Pregnancy Check-Up** → `#thursday`
- **Call 7039330945** `[tel: link]`

### Hero form card (`.hero-form-card`)

**Heading:** Book Your Appointment
**Sub-line** `[.hfc-sub]`: Share your details. Our team will call you back to confirm a time.

**Fields:**
- Your Name
- Phone Number
- Select Service ▾
  - OPD Consultation
  - Pregnancy Check-Up (ANC)
  - High-Risk Pregnancy
  - Painless Delivery
  - PCOD / PCOS
  - Infertility
  - Periods / Menstrual Problems
  - Menopause Care
  - Family Planning / Copper-T
  - Sonography & Lab Tests
  - Vaccination (Mother or Baby)
  - Free Thursday Pregnancy Check-Up
- Anything you'd like the doctor to know? (optional)

**Button:** Request a Call Back
**Note under button** `[.hfc-note]`: Emergency? Call 7039330945, any hour, every day.

---

## SECTION 2: STATS BAR (`.stats-bar`)

| Value | Label |
|---|---|
| **6+** | Years of Clinical Experience |
| **15+** | Women's & Maternity Services |
| **24/7** | Emergency Care |
| **Every Thu** | Free Pregnancy Check-Up |

`[Fourth stat is new. On mobile it wraps to a 2×2 grid, which the existing CSS already handles.]`

---

## SECTION 3: ABOUT VAIBHAVI HOSPITAL (`.doctor-section`)

**H2:** About Vaibhavi Hospital

**Pull quote** `[.q-text, with the existing quote-mark images]`
*When a woman understands what is happening in her own body, the fear lifts. That is what I wanted every patient here to feel.*
`[Confirm this wording with Dr. Vaibhavi. It is presented as her own words.]`

**Body 1**
Dr. Vaibhavi Birle (MBBS, MS Obstetrics & Gynaecology) has spent more than six years caring for women through pregnancy, delivery, PCOD, infertility and menopause. In every consultation, she explained things until the patient understood.

**Body 2**
She built Vaibhavi Hospital to make that the standard for every patient. Every woman here leaves knowing what is happening and what comes next, whether she is 8 weeks pregnant or in for a routine check.

**Body 3**
Delivery, NICU, ICU, surgery, diagnostics and vaccination are all inside Ridhisha Tower. Your care stays in one place from your first visit to your baby's first check-up.

**Link:** Know More →

---

## SECTION 4: OUR SPECIALITIES (`.services-section`)

**H2:** Our Specialities
**Sub-line** `[new, under H2]`: Every service a woman needs, from her first period to menopause, with delivery and newborn care at the centre.

`[Grid expands from 12 to 18 items: 3 full rows of 6. The one-liners are optional hover text or the intro line for each item on the Services page.]`

| # | Icon label | One-liner |
|---|---|---|
| 1 | **Antenatal & Post-Delivery Care** | Regular check-ups from your first month to after your baby arrives. |
| 2 | **High-Risk Pregnancy** | Closer care for BP, diabetes, twins or a previous C-section, with ICU and NICU ready. |
| 3 | **Painless Delivery** | Epidural pain relief so you stay comfortable and present during labour. |
| 4 | **Caesarean Section (LSCS)** | Planned or emergency C-section in our on-site operation theatre. |
| 5 | **PCOD & PCOS** | A clear diagnosis and a treatment plan you understand. |
| 6 | **Infertility Care** | Step-by-step evaluation and treatment, explained at every stage. |
| 7 | **Menstrual Disorders** | Answers for irregular, heavy or painful periods. |
| 8 | **Menopause Care** | Support for hot flushes, sleep, mood and bone health. |
| 9 | **Family Planning & Copper-T** | Contraception guidance and Copper-T (IUCD) fitting. |
| 10 | **Laparoscopic Surgery** | Keyhole gynaecological surgery for a faster recovery. |
| 11 | **Colposcopy** | A close cervical examination for early detection. |
| 12 | **Adolescent Counselling** | A comfortable space for girls to ask about periods and growing up. |
| 13 | **Govt. Recognised MTP & TL** | Safe, regulated MTP and tubal ligation procedures. |
| 14 | **Vaccination** | Safe, complete immunisation for pregnant mothers and newborns. |
| 15 | **Sonography & Lab Tests** | Pregnancy scans, follicular monitoring, pathology, same building. |
| 16 | **NICU** | Intensive care for your newborn, right here. |
| 17 | **ICU** | Round-the-clock intensive care for mothers. |
| 18 | **Mediclaim** | All major Mediclaim providers. Our front desk handles the paperwork. |

`[New icons needed for #3–4, #7–14. Rename existing items: "Maternity" → "Antenatal & Post-Delivery Care", "Gynaecology" → "Menstrual Disorders", "Fertility" → "Infertility Care", "Diagnostics" + "Sonography" merge into #15.]`

---

## SECTION 5: THE VAIBHAVI STANDARD (`.care-section` / `.care-banner`)

**H2**
Every consultation ends
<span green>when you understand.</span>

**Body** `[.care-body]`
You may have left a clinic with more questions than answers. Every consultation at Vaibhavi Hospital follows one standard: you leave knowing what is happening, why, and what comes next.

**Four icon points** `[.care-icon-item]`
1. Diagrams and plain language, with every term explained in the words you use at home.
2. Every question answered, including the ones you hesitated to ask.
3. Your whole story considered together: pregnancy, periods, PCOD and fertility.
4. Time for your husband's and family's questions too.

---

## SECTION 6: MEET YOUR DOCTORS (`.experts-section`)

**H2:** Meet Your Doctors
**Sub-line** `[new]`: Your gynaecologist, your diagnostic specialist, and visiting specialists for the whole family, all at Ridhisha Tower.

**Card 1: Dr. Vaibhavi Birle**
Obstetrician & Gynaecologist · MBBS, MS OBG

**Card 2: Dr. Rasik Mekhale**
Diagnostic & Ultrasound Specialist · Mekhale Diagnostic Center, Ground Floor

### Visiting Specialists [NEW] (from the flyer's "Doctors Available")
`[3 smaller cards or a single strip below the photo cards. Use an icon or illustration, not a photo, and no names.]`

**Strip heading:** Visiting Specialists, Available at Vaibhavi Hospital

| Specialty | Line |
|---|---|
| **Paediatrician** | Newborn check-ups, baby care and child vaccination. |
| **Physician (General Medicine)** | Fever, BP, diabetes, thyroid and everyday health for your whole family. |
| **General Surgeon** | Surgical consultations and procedures in our on-site operation theatre. |

`[If added as slider cards, update the slider script: total = 5.]`

---

## SECTION 7: WHY VAIBHAVI HOSPITAL (`.facilities-section`)

**H2:** Why <green>Vaibhavi Hospital</green>
**Sub-line** `[.facilities-header p]`: Every facility your family needs is in one building, ready at every hour.

### 7a. What You Get [NEW] (from the flyer's "What You Get From Vaibhavi Hospital")
`[Use the existing but unused .why-stats-grid, 4 cards, above the facility cards.]`

| Card | Headline | Line |
|---|---|---|
| 1 | **An Experienced Team** | Led by an MS Obstetrician & Gynaecologist, with a paediatrician, physician and surgeon on call. |
| 2 | **Modern Equipment** | NICU, ICU, operation theatre and a full diagnostic lab, equipped and ready. |
| 3 | **Friendly, Caring Service** | Every question answered. Every step explained. Every visit, the same warmth. |
| 4 | **Affordable Treatment** | Fair, clear pricing. Mediclaim accepted. Your paperwork is handled by our front desk. |

### 7b. Facility Cards (`.facility-card`, 8 cards)

| Name | Sub-line |
|---|---|
| **NICU** | Newborn Intensive Care · On-Site |
| **ICU** | Intensive Care for Mothers · 24/7 |
| **Operation Theatre** | LSCS · Laparoscopic · Gynaecological Surgery |
| **24/7 Emergency** | Fast Response · Every Hour, Every Day |
| **Labour & Delivery Suite** | Normal & Painless Delivery |
| **Mekhale Diagnostics** `Same Bldg` | Pregnancy Ultrasound · Follicular Monitoring · Radiology · Pathology & Biochemistry Lab |
| **Deluxe Rooms** | Private Recovery for You & Your Family |
| **Vaccination** | Complete Immunisation for Mother & Newborn |

`["Antenatal Care" card replaced by "Vaccination". Antenatal care now lives in Our Specialities.]`

### 7c. Emergency Banner [NEW] (from the flyer's red emergency block)
`[Use the existing but unused .address-banner. Blue background.]`

**Title:** Emergency care, every hour of every day.
**Sub:** Fast, reliable emergency care for urgent medical needs. Our team is here 24 hours a day, 7 days a week.
**Chips:** ✓ 24/7 Emergency ✓ ICU ✓ NICU ✓ OT
**Button:** Call 7039330945

---

## SECTION 8: FREE THURSDAY CHECK-UP [NEW] (`.thursday-section`, `id="thursday"`)

`[The hero button already links to #thursday, but this section is missing from the HTML. Build it with the existing .thursday-* CSS.]`

**Badge** `[.thursday-badge]`: Every Thursday · Free · 5 PM – 7 PM

**H2:** Free Check-Up for Pregnant Women

**Sub-head** `[.thursday-subhead, serif italic]`: Every Thursday evening, at Vaibhavi Hospital.

**Main line** `[.thursday-main]`
Pregnant and want to know that everything is on track? Come in any Thursday between 5 and 7 PM for a free check-up with our team.

**Supporting copy** `[.thursday-support]`
Bring your previous reports and every question on your mind: your baby's growth, your diet, a symptom that has been worrying you, or what to expect in the weeks ahead. You leave with clear answers and a plan you understand.

Every expecting mother in Taloja is welcome.

`[GAP: confirm exactly what the free check-up includes, e.g. BP, weight, Hb, consultation. Add as a short list once confirmed.]`

**Location** `[.thursday-location]`
📍 Vaibhavi Hospital, Ridhisha Tower, Sector 23, Behind Pendhar Metro Station, Taloja Phase 2

**Side card** `[.thursday-card]`
- `[.every-thursday]` **Every Thursday**
- **5:00 PM – 7:00 PM**
- Free check-up for pregnant women
- `[.tc-note]` Walk in, or call ahead on 7039330945

**Buttons:**
- **Call to Confirm: 7039330945**
- **Get Directions** `[Google Maps link, same as the flyer QR code]`

---

## SECTION 9: TESTIMONIALS (`.social-section`)

**H2:** What Women Say

**Story image** `[.story-quote-img]`: keep as-is.
`[If this image carries the "Baby Named Vaibhavi" story, it requires confirmed patient consent before launch.]`

**Review cards:** keep the three existing cards.
`[⚠️ All three are placeholders. Replace them with verified Google reviews before launch. Do not publish invented reviews as "Verified Patient".]`

---

## SECTION 10: OPD HOURS & BOOKING [NEW] (`.appt-section`, `id="appt"`)

`[The navbar "Book Appointment" button links to #appt, but this section is missing. Build it with the existing .appt-* CSS.]`

**Badge** `[.appt-badge]`: Now Open

**H2:** Your Care Is Ready When You Are.

**Body** `[.appt-body]`
Call, WhatsApp or walk in during OPD hours. Bring your Mediclaim card, and our front desk will handle the paperwork from admission to discharge.

Your family stays focused on you. Our team handles the rest.

**Buttons:**
- **Call 7039330945**
- **WhatsApp Us** `[confirm that 7039330945 is the WhatsApp number]`

**Info card** `[.appt-info-card]`

**Heading:** OPD Timings

| | |
|---|---|
| ☀️ Morning OPD | 9:00 AM – 12:00 PM |
| 🌙 Evening OPD | 5:00 PM – 9:00 PM |
| 🤰 Free Pregnancy Check-Up | Thursday, 5:00 PM – 7:00 PM |
| 🚨 Emergency | 24 / 7 |

**Address** `[.appt-address]`
Vaibhavi Hospital, Ridhisha Tower, Sector 23
Behind Pendhar Metro Station, Taloja Phase 2
Navi Mumbai – 410 208 · Near Prathmesh Society

---

## FOOTER

**Logo:** Vaibhavi Hospital
**Tagline:** Where Healthcare Meets Humanity

**About** `[.footer-about]`
A women's and maternity hospital in Taloja Phase 2 where delivery, NICU, ICU, surgery and diagnostics are all inside one building, and every patient leaves understanding her care.

**Badge** `[.footer-legal]`: Govt. Recognised MTP & TL Centre

**Button:** Book Appointment

**Quick Links:** Home · About · Services · Doctors · Insurance · Contact Us

**Contact**
- 📞 7039330945
- ✉️ info@vaibhavihospitaltaloja.in `[confirm the address exists before launch]`
- 📍 Ridhisha Tower, Sector 23, Behind Pendhar Metro Station, Taloja Phase 2, Navi Mumbai – 410 208
- 🕘 OPD: 9 AM – 12 PM · 5 PM – 9 PM
- 🚨 Emergency: 24/7

**Follow Us On:** Facebook · Instagram · LinkedIn · YouTube `[add real profile URLs]`

**Bottom line:** © 2026 Vaibhavi Hospital, Taloja Phase 2. All rights reserved. · Privacy Policy

---

## SEO METADATA

`[For the developer. These go in the page <head>.]`

**Title:**
`Lady Gynecologist & Maternity Hospital in Taloja | Vaibhavi Hospital`

**Meta description:**
`Now open behind Pendhar Metro, Taloja Phase 2. Dr. Vaibhavi Birle, MS OBG. Painless delivery, NICU & ICU on-site, 24/7 emergency. Free pregnancy check-up every Thursday. Call 7039330945.`

**Keywords naturally covered:** lady gynecologist Taloja · maternity hospital Taloja Phase 2 · hospital near Pendhar Metro Station · maternity hospital with NICU Taloja · painless delivery Navi Mumbai · PCOD treatment Navi Mumbai · govt recognised MTP centre Navi Mumbai · free pregnancy check-up Taloja

---

## PRE-LAUNCH CHECKLIST

- [ ] Evening OPD end time: 9 PM (flyer) or 10 PM (earlier notes)
- [ ] Thursday camp: pregnant women only, 5–7 PM? What does it include?
- [ ] About-section pull quote approved by Dr. Vaibhavi as her words
- [ ] Patient consent for the "Baby Named Vaibhavi" story image
- [ ] Replace the 3 placeholder reviews with verified Google reviews
- [ ] WhatsApp number and email address confirmed
- [ ] Google Maps link (same as the flyer QR code)
- [ ] Social media profile URLs
