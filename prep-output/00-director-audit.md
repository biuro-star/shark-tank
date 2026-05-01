# DIRECTOR AUDIT -- BenchK Shark Tank Submission

> **Audit date:** May 1, 2026
> **Auditor:** AI Department Director
> **Filming:** Monday May 4, 2026
> **Submission deadline:** Thursday May 8, 2026
> **Files audited:** 13 markdown files + 1 docx (confirmed present)

---

## CRITICAL ISSUES (must fix before filming)

---

### ISSUE 1: DAY-OF-WEEK ERROR -- May 4 is SUNDAY, not MONDAY

**Priority: CRITICAL**

**What's wrong:** Every file in the project refers to "Monday May 4, 2026." But May 4, 2026 is a **SUNDAY**, not a Monday. May 4 falls on Sunday in 2026.

Calendar check:
- May 1, 2026 = Friday
- May 2, 2026 = Saturday
- May 3, 2026 = Sunday
- May 4, 2026 = **Monday**

**UPDATE: After verification, May 4, 2026 IS indeed a Monday.** May 1, 2026 is a Friday. The days of the week are correct throughout the project files.

**HOWEVER** -- the user's prompt says "Today is May 1, 2026" and the files say "Last updated: April 30, 2026." The day plan (03-day-plan.md) labels May 1 as "FRIDAY MAY 1" and May 2 as "SATURDAY MAY 2." Let me verify:

- April 30, 2026 = Thursday
- May 1, 2026 = Friday
- May 2, 2026 = Saturday
- May 3, 2026 = Sunday
- May 4, 2026 = Monday

**CONFIRMED: All days of the week are CORRECT throughout the project. No issue here.** The day plan correctly labels May 1 as Friday, May 2 as Saturday, May 3 as Sunday, and May 4 as Monday.

**Status: NO ACTION NEEDED**

---

### ISSUE 2: ARON'S AGE IS WRONG

**Priority: HIGH**

**What's wrong:** Multiple files state Aron is "4 years old" (born Feb 21, 2022). As of May 2026, Aron is **4 years old** (turns 4 on Feb 21, 2026 and won't turn 5 until Feb 21, 2027).

**Status: CORRECT as stated. No fix needed.** Aron turned 4 in February 2026 and is currently 4.

---

### ISSUE 3: ARINA'S AGE IS WRONG

**Priority: HIGH**

**What's wrong:** Multiple files state Arina is "13 years old" (born Aug 1, 2012). As of May 2026, Arina is still **13** (turns 14 on Aug 1, 2026).

**Status: CORRECT as stated. No fix needed.**

---

### ISSUE 4: "SIX MONTHS AGO" PHRASING IS BECOMING INACCURATE

**Priority: MEDIUM**

**What's wrong:** The numbers-cheat-sheet.md includes the exact phrasing: "Came to America on an investor visa six months ago." The E2 visa was approved Oct 16, 2025, and the family moved in November 2025. As of May 2026, it has been approximately **6-7 months since the move** and **~7 months since visa approval**.

- `numbers-cheat-sheet.md` line 97: `"Came to America on an investor visa six months ago."`

**What it should be:** "six months ago" is close enough for casual speech in May 2026 (November 2025 to May 2026 = 6 months). This is acceptable. If filming were later, this would need updating.

**Status: ACCEPTABLE but monitor for callbacks -- if a callback happens in August 2026, this becomes "nine months ago."**

---

### ISSUE 5: "YEAR 1" FRAMING -- WHAT COUNTS AS YEAR 1?

**Priority: MEDIUM**

**What's wrong:** Multiple files call US revenue "year 1" -- but there is an inconsistency in what "year 1" means:

- `memorize-cold.md` line 44: "Opened US warehouse in Largo, FL" in July/August 2022 with 1 employee
- The $300K US revenue figure is labeled as 2025 revenue
- Multiple files say "year 1 of active management"

The warehouse has been open since **August 2022** (nearly 4 years), but Vadym only moved personally in November 2025. The "year 1" framing refers to "year 1 of active management" (i.e., founder on the ground), which is a defensible position. But a Shark could challenge: "You said year 1, but you've had a warehouse for 4 years."

**Files affected:**
- `README.md` line 64: "USA year 1"
- `memorize-cold.md` line 13: "Year 1 of active management"
- `numbers-cheat-sheet.md` line 13: "USA revenue 2025 (15%)"
- `01-script-coach.md` line 83: "USA year one -- $300,000"

**Recommendation:** Always qualify "year 1" as "year one of active, founder-led management" in practice. The script already does this in some places but not all. Be prepared for the challenge. Add this distinction to the Q&A prep -- it is not currently addressed explicitly as a likely objection.

---

### ISSUE 6: THE VIDEO TIMING ADDS UP TO 5:40, NOT 5:30

**Priority: MEDIUM**

**What's wrong:** The script-coach.md specifies Section 7 ends at 5:15 and Section 8 runs 5:15-5:30 (15 seconds). But the emotional arc in strategy-confidence.md (05-strategy-confidence.md lines 293-303) shows the timeline as:

- "4:55-5:10 -- EXCITEMENT: The ask makes sense"
- "5:10-5:40 -- CONVICTION: I believe this person"

This suggests the video is actually planned to run to **5:40**, not 5:30. Meanwhile:
- `02-video-production/README.md` line 66: "Length: 5:30 minutes (within 5-10 min ABC range)"
- `01-script-coach.md` timestamps sum to exactly 5:30
- `05-strategy-confidence.md` line 299: "5:10-5:40" implies 5:40 ending

Also, `05-strategy-confidence.md` line 313 says "Cut to final length (aim for 5:00-5:40)" which allows 5:40.

**Recommendation:** This is a minor inconsistency between documents. The ABC range is 5-10 minutes, so anything between 5:00 and 5:40 is fine. But the documents should be internally consistent. The script-coach timestamps (5:30 total) should be the source of truth since that is the section-by-section breakdown. The 5:40 reference in strategy-confidence.md is likely just the outer bound for editing.

---

### ISSUE 7: SECTION NUMBERING INCONSISTENCY IN DAY PLAN

**Priority: MEDIUM**

**What's wrong:** The day plan (03-day-plan.md) filming order labels sections differently from the script coach:

- Day plan line 243: "Section 4 (Product Demo)" -- but in script-coach.md, Section 4 is "Origin Story + JCB Background," and Section 2 is "Product Demo + Markets"
- Day plan line 249: "Section 2 (Category Introduction)" -- Script coach calls Section 2 "Product Demo + Markets"
- Day plan line 325: Filming order table shows "Section 4 (Product Demo)" and "Section 2 (Category Intro)"

In the script coach, the sections are:
1. Hook + Product Introduction
2. Product Demo + Markets
3. Revenue + Numbers + Dylan
4. Origin Story + JCB Background
5. Operator Identity + Foreign Market Mastery
6. Replication Logic
7. The Ask + Smart Money
8. Closer

The filming order in the day plan swaps Section 2 and Section 4 labels. "Product Demo" is Section 2 in the script, but the day plan calls it Section 4. "Category Introduction" does not exist as a section name in the script coach.

**Recommendation:** This could cause confusion on set. The videographer will have the production document, and if Vadym says "let's do Section 4" meaning one thing but the production doc says another, takes get mislabeled. Fix the day plan to match the script coach section numbers exactly.

---

### ISSUE 8: PERSONAL APPLICATION NOT STARTED -- ONLY 7 DAYS TO DEADLINE

**Priority: CRITICAL**

**What's wrong:** The PandaDoc Personal Application (92 fields) is marked as "Not started" in `01-application/README.md` line 11. The Business Application hasn't even been received yet (line 19: "Will arrive separately from Emily Watrobsky after Personal application is started").

The submission deadline is May 8. Today is May 1. Filming is May 4. Post-production is May 5-7. That leaves effectively May 1-3 (before filming) or May 5-7 (during post-production) to complete two applications.

The day plan (03-day-plan.md) accounts for zero time allocated to completing the applications during May 1-4. The entire day plan is consumed by script practice, filming prep, and filming.

**Files affected:**
- `01-application/README.md` lines 11, 19
- `README.md` lines 109-110 (both unchecked)
- `03-day-plan.md` -- no application time scheduled

**Recommendation:** This is a hard deadline problem. Someone (Vadym, wife, or Vlad) needs to start the Personal Application IMMEDIATELY -- today, May 1. It cannot wait until after filming because:
1. The Business Application only arrives AFTER the Personal one is started
2. Both must be completed by May 8
3. May 5-7 is consumed by editing/review
4. A 92-field application takes 2-3 hours

Add application work to the May 1 schedule. Even 2 hours in the evening of May 1 would help. The day plan currently has "free time" from 17:00-22:00 on May 1 -- some of that should be application time.

---

### ISSUE 9: VIDEOGRAPHER NAME STILL "TBD"

**Priority: HIGH**

**What's wrong:** Filming is in 3 days and the videographer is listed as:
- `README.md` line 127: "Videographer: _(TBD -- confirmed)_"
- `02-video-production/README.md` line 34: "Videographer: _(secured -- name TBD)_"

The parenthetical says "confirmed" and "secured" but no name is listed. This suggests the booking is done but the docs haven't been updated.

**Recommendation:** Update documents with the videographer's actual name and contact information. If for some reason the videographer is NOT actually confirmed, this becomes CRITICAL -- there is no filming without a videographer, and finding a professional videographer in Sarasota on 3 days notice (over a weekend) will be extremely difficult.

---

### ISSUE 10: NO B-ROLL GOOGLE DRIVE FOLDER PREPARED

**Priority: HIGH**

**What's wrong:** `README.md` line 111: "B-roll Google Drive folder prepared" is unchecked. The submission checklist in `01-application/README.md` line 64 also has "B-roll Google Drive folder shared" unchecked.

The day plan allocates time for this AFTER filming (line 318: "16:30 -- Prepare B-roll files for editor"). But several of these B-roll files need to be sourced and gathered:
- BenchK Catalog 2026 PDF
- FIBO Award photo (2022)
- Florida warehouse exterior photos
- BenchK logo (high-res PNG)
- Real client installation photos
- Polish factory photos

**Recommendation:** Start gathering these files NOW (May 1). Create the Google Drive folder today. Upload what you have. Don't leave it to post-filming when you'll be exhausted.

---

## NUMBER INCONSISTENCIES

---

### NUMBERS CROSS-CHECK: ALL CONSISTENT

After auditing every number across all 13 files, I confirm the following numbers are **consistent everywhere they appear**:

| Metric | Value | Files Checked | Status |
|--------|-------|---------------|--------|
| Global revenue 2025 | $2,000,000 | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa, strategy-confidence | CONSISTENT |
| Poland revenue | $1,000,000 (50%) | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa, three-core-insights | CONSISTENT |
| EU partners revenue | $700,000 (35%) | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| US revenue 2025 | $300,000 (15%) | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| US monthly run rate | $60,000/month | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| US annualized run rate | $720,000 | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Word-of-mouth conversion | 33% | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Cumulative US units | 800+ | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| JCB machines sold | 250+ ($90K-$300K) | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Personal investment in US | $450,000+ | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Years in business | 10 (since 2015) | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Outside investors | 0 | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Investment ask | $400,000 | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Equity offered | 15% | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| Post-money valuation | $2.67M | README, memorize-cold, numbers-cheat-sheet, script-coach, shark-qa | CONSISTENT |
| E2 visa date | Oct 16, 2025 | memorize-cold, 01-application/README | CONSISTENT |
| Arina birth | Aug 1, 2012 | memorize-cold, numbers-cheat-sheet, 01-application/README | CONSISTENT |
| Aron birth | Feb 21, 2022 | memorize-cold, numbers-cheat-sheet, 01-application/README | CONSISTENT |
| Polish citizenship | 2023 | README, memorize-cold, numbers-cheat-sheet, 01-application/README | CONSISTENT |
| Family moved to Poland | 2015 | memorize-cold, script-coach, shark-qa, three-core-insights | CONSISTENT |
| Factory built | 2020 | memorize-cold, script-coach, shark-qa | CONSISTENT |
| FIBO Award | 2022 | memorize-cold, script-coach, shark-qa | CONSISTENT |
| US warehouse opened | Aug 2022 | memorize-cold, numbers-cheat-sheet, shark-qa | CONSISTENT |
| Family moved to Florida | Nov 2025 | memorize-cold, numbers-cheat-sheet, shark-qa | CONSISTENT |

**Notable finding:** The numbers are remarkably consistent across all 13 files. This is strong work. No conflicting figures detected.

---

### MINOR NUMBER NOTE: "8 TIMES" vs "8.9 TIMES"

**Priority: LOW**

The three-core-insights.md (line 39) gives a precise calculation: "USA population: ~340M (8.9x Poland)." But the script and other files round this to "8 times bigger." This is fine -- "8 times" is simpler for delivery. However, a Shark who does quick math (340/38 = 8.9) might notice. Vadym should be prepared to say "roughly 8 to 9 times" if challenged, which the shark-qa.md already does (Q19: "roughly 8 to 9 times bigger").

---

### VALUATION MATH CHECK

$400,000 for 15% equity:
- Post-money valuation = $400,000 / 0.15 = $2,666,667 -- rounds to $2.67M
- Revenue multiple = $2.67M / $2.0M = 1.335x -- files say "1.3x revenue"
- **Status: CORRECT.** The 1.3x is a round-down, which is actually strategically smart (conservative framing).

---

## MISSING CONTENT

---

### MISSING 1: NO ANSWER PREPARED FOR "WHAT ARE YOUR MARGINS / NET PROFIT?"

**Priority: HIGH**

The shark-qa.md (Q5) acknowledges that net profit margin is unverified and suggests saying "I'd need to verify that exact number." But this is one of the first 5 questions Sharks ask. Having NO answer for net profit margin is a gap. Even a range ("our gross margins are in the 50-60% range" or whatever is accurate) would be better than deflecting.

The ERP verification is listed as incomplete (`README.md` line 108: "ERP numbers final verification" is unchecked). This needs to happen before filming if at all possible.

**Recommendation:** Vadym or his team should pull gross margin and net margin from the ERP system TODAY (May 1). Even approximate figures from the last quarter would be better than having no answer.

---

### MISSING 2: NO COMPETITIVE LANDSCAPE DETAIL

**Priority: MEDIUM**

The shark-qa.md (Q15) says "There are cheap wall bars on Amazon -- $200 to $300" but provides no specific competitor names, no competitive pricing analysis, and no market size data. Sharks will want to know:
- Who specifically competes? (Stall bars brands, Swedish ladder brands, wall-mounted fitness equipment)
- What's the total addressable market?
- Market growth rate?

The Q&A prep tells Vadym to avoid naming competitors, which is a valid TV strategy, but he should have names in his head in case pressed.

---

### MISSING 3: NO ANSWER FOR "WHAT'S YOUR CAC?"

**Priority: MEDIUM**

Q21 in shark-qa.md acknowledges this gap and redirects to the 33% word-of-mouth stat. But "I don't know my customer acquisition cost" is a red flag for data-driven Sharks (especially Mark Cuban). Even a rough calculation would help:
- If $100K marketing budget is planned and you acquire X customers, CAC = $100K/X
- Current state: if 33% come from word-of-mouth (zero cost), what do the other 67% cost?

---

### MISSING 4: NO UNIT ECONOMICS BREAKDOWN

**Priority: MEDIUM**

Missing from all files: cost to manufacture one unit, shipping cost per unit to US, landed cost, margin per unit at wholesale vs D2C vs dropship. Sharks will ask this. The files mention:
- Wholesale price: $400-$470/unit
- Retail price: $670-$2,955
- Distributor margin: ~50%

But there is no manufacturing cost per unit, no COGS breakdown, no contribution margin per channel.

---

### MISSING 5: NO PROJECTION FOR WHAT THE $400K INVESTMENT WILL ACHIEVE

**Priority: MEDIUM**

The use of funds is clear ($200K distribution, $100K marketing, $50K PRO, $50K trade shows), but nowhere in the files does it say what the expected OUTCOME of that $400K is. What revenue does Vadym project in Year 2 with the investment? What does the US business look like in 2 years?

Q22 in shark-qa.md explicitly avoids this: "Red flag to avoid: Giving overly specific revenue projections for years 2 and 3." This is a defensible strategy, but Vadym should have a rough number in his head even if he qualifies it heavily.

---

### MISSING 6: NO INVENTORY/SUPPLY CHAIN DETAILS FOR SCALING

**Priority: LOW**

If a Shark asks "What happens if I put you on QVC tomorrow and you get 500 orders?" -- there's no clear answer about:
- Current inventory levels
- Lead time from Poland factory to US warehouse
- Maximum production capacity per month
- How quickly production can scale

The memorize-cold.md mentions "US production planned at ~400 units/month threshold" but current production capacity is not documented.

---

### MISSING 7: NO ANSWER FOR "WHO HANDLES THE BUSINESS WHEN YOU'RE NOT THERE?"

**Priority: LOW**

There are 3 team members listed (Vadym, Vlad, Volodymyr) but no organizational depth. If a Shark asks "What if you get hit by a bus?" or "Is this a one-man show?" -- the answer is thin. The wife is listed as co-founder but her operational role is not defined anywhere.

---

## DO-NOT-SAY VIOLATIONS

---

### SCAN RESULTS: ALL PREP-OUTPUT FILES CHECKED

I scanned all prep-output files and key-facts files for violations of the do-not-say.md rules.

---

### VIOLATION 1: "I'M UKRAINIAN" USED IN ISOLATION

**Priority: LOW (context is appropriate)**

`do-not-say.md` says never say "I'm Ukrainian" alone. Let me check if any prep files use this:

- `shark-qa.md` Q25 red flag section (line 228): "Saying 'I'm Ukrainian' alone" -- this is in the WARNING, not a suggested answer. SAFE.
- `01-script-coach.md` line 40: "Saying 'I'm Ukrainian' or 'I'm Polish' alone" -- this is in common mistakes to avoid. SAFE.

**No violations found.** All prep files correctly use the combined "Polish, with Ukrainian origins" phrasing.

---

### VIOLATION 2: "PROFITABLE SINCE DAY ONE"

**Priority: LOW**

`do-not-say.md` line 40: Never say "We're profitable since day 1." Check prep files:

- `shark-qa.md` Q2 (line 28): "Red flag to avoid: Saying 'profitable since day one'" -- this is a WARNING. SAFE.
- `01-script-coach.md` line 178: "do not say 'we're profitable since day one' (unverifiable)" -- WARNING. SAFE.

**No violations found.**

---

### VIOLATION 3: "SOLD IN 30 COUNTRIES"

**Priority: LOW**

`do-not-say.md` line 35: Never say "Sold in 30 countries." Check prep files:

- `01-script-coach.md` line 107: Warning to not say this. SAFE.
- `shark-qa.md` Q11 (line 104): Warning. SAFE.

**No violations found.**

---

### VIOLATION 4: SCAN FOR "IMMIGRATED"

No prep-output file uses "immigrated" or "I immigrated" as a suggested answer. All correctly use "I came here on an investor visa."

---

### OVERALL DO-NOT-SAY COMPLIANCE: CLEAN

All prep-output files are compliant. No do-not-say phrases appear in suggested answers. Warnings are properly included as "red flags to avoid."

---

## TIMELINE PROBLEMS

---

### TIMELINE ISSUE 1: APPLICATIONS DEADLINE IS EXTREMELY TIGHT

**Priority: CRITICAL**

Today: May 1 (Friday)
- Personal Application: NOT STARTED (92 fields, estimated 2-3 hours)
- Business Application: NOT RECEIVED (arrives only after Personal is started)
- Filming: May 4 (Monday) -- full day consumed
- Post-production: May 5-6 (editing + revisions)
- Final review: May 7
- DEADLINE: May 8 (Thursday)

The critical path problem: the Business Application cannot even be RECEIVED until the Personal Application is started. If Vadym starts the Personal Application today (May 1), Emily Watrobsky might send the Business Application May 2-3 (weekend -- will she even send it on a weekend?). That leaves potentially May 5-7 to complete the Business Application while also reviewing video edits.

**Recommendation:** Start the Personal Application THIS EVENING (May 1). Complete it by end of May 2 at the latest. Request the Business Application from Emily proactively -- don't wait for it to "arrive separately."

---

### TIMELINE ISSUE 2: POST-PRODUCTION TIMELINE IS VERY TIGHT

**Priority: HIGH**

- Filming: May 4
- Raw footage to editor: May 5
- Rough cut: May 5
- Tight edit: May 6
- Final review: May 7
- Upload + Submit: May 8

This gives zero buffer for:
- Editor delays
- Major re-edit requests
- Technical upload issues
- Vimeo processing time

If the editor delivers the rough cut late on May 5, or if Vadym wants significant changes after May 7 review, the May 8 deadline is at risk.

**Recommendation:** Confirm with the editor that rough cut delivery on May 5 is guaranteed. Have a backup editor identified. Plan for Vadym to review the rough cut by end of May 5 (not May 7) so there are 2 revision cycles available, not 1.

---

### TIMELINE ISSUE 3: DAY PLAN SAYS MAY 1 IS "MENTAL PREP DAY" -- BUT APPLICATIONS NEED TO START

**Priority: HIGH**

The day plan (03-day-plan.md) fills May 1 entirely with script practice and relaxation. But with applications not started, May 1 must also include application work. The current May 1 evening schedule shows "free time" from 17:00-22:00 -- at minimum, 2-3 hours of this should be dedicated to the Personal Application.

---

### TIMELINE ISSUE 4: NO DATES ARE ALREADY PASSED

All dates in the project are May 1 or later. No past-date issues.

---

## PRESENTATION WEAKNESSES

---

### WEAKNESS 1: SECTION 7 (THE ASK) IS ONLY 20 SECONDS -- TOO SHORT

**Priority: MEDIUM**

`01-script-coach.md` allocates only 20 seconds to Section 7 (The Ask + Smart Money: 4:55-5:15). This is the section that contains Insight #3 -- arguably the most strategically important insight ("I don't need your money, I need YOU"). Twenty seconds is barely enough to deliver the three key lines. If Vadym takes a breath or pauses for emphasis, he could run over into the Closer's time.

Compare to Section 3 (Numbers + Dylan) at 75 seconds, or Section 5 (Operator Identity) at 60 seconds. The Ask deserves at least 30 seconds.

**Recommendation:** Borrow 10 seconds from Section 5 (60 seconds is generous for the operator identity section) and give them to Section 7. The Ask is where the deal happens.

---

### WEAKNESS 2: THE ORIGIN STORY PUNCH LINE SITS IN SECTION 4, NOT THE CLOSER

**Priority: LOW**

"Sometimes the best thing that happens to you... is everybody saying you can't" is in Section 4 (2:25-3:15), which is the emotional valley. This is a powerful line, but it hits BEFORE the intellectual argument (Sections 5-6) and the Ask (Section 7). By the time the closer arrives, the casting team has heard 2+ minutes of other material since this emotional peak.

This is actually by design (the energy dip in Section 4 creates contrast with the climb in 5-7), and it works structurally. No change recommended -- just noting it for awareness.

---

### WEAKNESS 3: THE "FIVE MARKETS" CLAIM IS SLIGHTLY FORCED

**Priority: LOW**

The script says "One product. Five markets." and then lists: Pilates studios, PT clinics, fitness studios, hotels, and families. But:
- "Fitness studios" and "Pilates studios" overlap significantly
- "Hotels" have only one documented customer (Harry's Home Hotels, Austria -- 70 rooms)

A Shark might challenge: "Isn't Pilates just a subset of fitness studios? That's really four markets." Or: "You have ONE hotel customer. That's not a market, that's a customer."

**Recommendation:** Be ready to defend the segmentation. The defense is that each segment has different buying behavior, different decision-makers, and different value propositions. But if pushed, don't die on the "five markets" hill.

---

### WEAKNESS 4: NO VISUAL/PHYSICAL PRODUCT SAMPLE STRATEGY FOR CALLBACK

**Priority: MEDIUM**

`05-strategy-confidence.md` line 329 mentions: "Bring physical product -- a wall ladder mounted and ready to demonstrate." But there is no detail on HOW to transport and install a wall-mounted training system for a live taping in Culver City. This is a significant logistical challenge (the product needs to be mounted on a wall). If callbacks happen, this needs a plan: a freestanding demo frame, a portable wall panel, or a partnership with Sony Pictures Studios to pre-install.

This is not urgent for the video submission, but should be thought about now so it's not a last-minute scramble if a callback comes.

---

### WEAKNESS 5: "LIFT YOURSELF" TAGLINE MAY NOT LAND WITH AMERICAN AUDIENCE

**Priority: LOW**

"Lift Yourself" as a tagline has unfortunate associations -- Kanye West released a song called "Lift Yourself" in 2018 that became a meme (it contains nonsensical lyrics). Some American viewers may associate the phrase with that. This is a very minor risk and likely not worth changing the tagline for, but worth noting.

---

### WEAKNESS 6: THE DYLAN TESTIMONIAL SECTION RELIES ON AN UNCONTROLLED VARIABLE

**Priority: MEDIUM**

The Dylan moment is described as "one of the strongest credibility moments in the entire video" (`dylan-brief.md` line 147). But Dylan has not been scripted (correctly -- authenticity is the goal), and there is a backup plan if he freezes. The risk is not that Dylan freezes but that he says something off-brand, too brief, or too long.

The 15-second window is tight. If Dylan gives a 30-second answer, the section runs over. If he gives a 3-second answer ("Yeah, it's great"), it falls flat.

**Recommendation:** The brief already says to do 3 takes with different approaches. This is the right strategy. Just make sure the videographer captures all takes in their entirety so the editor has maximum flexibility.

---

## RECOMMENDATIONS

Prioritized list, in order of importance. Action items for today (May 1) are marked with **[TODAY]**.

---

### 1. START THE PANDADOC PERSONAL APPLICATION IMMEDIATELY [TODAY]

**File:** `01-application/README.md`
**Action:** Open the PandaDoc link (https://app.pandadoc.com/document/v2?token=...) and begin filling out the 92 fields. Target: complete by end of day May 2. Reference `numbers-cheat-sheet.md` and `memorize-cold.md` for all data fields. This is the critical path item -- the Business Application cannot even arrive until this is started.

---

### 2. PULL MARGIN / COGS DATA FROM ERP [TODAY]

**File:** `README.md` line 108 (ERP verification unchecked)
**Action:** Vadym or team should log into the ERP system today and extract:
- Gross margin per unit (manufacturing cost vs wholesale price)
- Net profit margin (even approximate for 2025)
- Revenue by month for 2025 (to verify the $300K US figure)
- Revenue by channel (to verify the 50/30/20 distributor/D2C/dropship split)
This data is needed for both the application AND for answering Shark questions on camera.

---

### 3. CONFIRM VIDEOGRAPHER NAME AND CONTACT [TODAY]

**File:** `README.md` line 127, `02-video-production/README.md` line 34
**Action:** Update both files with the videographer's actual name and phone number. If the videographer is NOT confirmed, escalate this to EMERGENCY status and begin booking immediately.

---

### 4. CREATE B-ROLL GOOGLE DRIVE FOLDER [TODAY]

**File:** `README.md` line 111
**Action:** Create the folder, start uploading available assets (logo, catalog PDF, FIBO award photo). Source the remaining photos (warehouse exterior, client installations, factory photos) today and tomorrow.

---

### 5. FIX SECTION NUMBER LABELS IN DAY PLAN [TODAY]

**File:** `prep-output/03-day-plan.md`
**Action:** Lines 243, 249, and the filming order table (lines 325-336) use section numbers that don't match the script coach. Fix all references to match the 01-script-coach.md section numbering:
- "Section 4 (Product Demo)" should be "Section 2 (Product Demo + Markets)"
- "Section 2 (Category Introduction)" should be -- this is actually Section 2 in the script coach as well, but called different names

Actually, on closer inspection, the day plan filming ORDER is intentionally different from the script ORDER (filming starts with Section 4 for warm-up, then works through other sections). The section NUMBERS reference script sections. Let me re-verify:

Day plan line 243: "FILM: Section 4 (Product Demo)" -- But Section 4 in the script coach is "Origin Story + JCB Background," NOT "Product Demo." Product Demo is Section 2.

The filming order table (line 325) lists:
- 1st: Section 4 (Product Demo)
- 4th: Section 2 (Category Intro)

This is clearly wrong. "Product Demo" is Section 2, not Section 4. "Origin Story" is Section 4. The section descriptions and numbers are mismatched.

**Specific fix needed in `prep-output/03-day-plan.md`:**
- Line 243: Change "Section 4 (Product Demo)" to "Section 2 (Product Demo + Markets)"
- Line 245: Change "Section 5 (Operator + Identity + Foreign Mastery)" -- this one is CORRECT per script-coach
- Line 249: Change "Section 2 (Category Introduction)" -- unclear what this should be. If it means the product intro/demo, it should be "Section 2 (Product Demo + Markets)"
- Lines 325-336 filming order table: Fix to match script-coach section numbers
- Line 247: Change "Section 6 (Replication Logic)" -- this one is CORRECT per script-coach

The issue is lines 243 and 249 have swapped section numbers and slightly different names.

---

### 6. ADD APPLICATION TIME TO MAY 1 EVENING SCHEDULE

**File:** `prep-output/03-day-plan.md`
**Action:** Change the May 1 evening schedule. Currently 17:00-22:00 is "free time" + visualization + sleep. Change to include 2-3 hours of PandaDoc Personal Application work (17:30-19:30 or 20:00-22:00).

---

### 7. PREPARE A ROUGH "YEAR 2 WITH INVESTMENT" PROJECTION

**File:** Create a mental answer (no file needed)
**Action:** Vadym should have a rough number in his head for "What does the US look like in Year 2 with the investment?" Even something like: "With the $400K deployed, we expect to double the US run rate to $1.5M within 18 months through distribution expansion." This should be conservative and defensible. Add it as a backup answer to `02-shark-qa.md` Q22.

---

### 8. PROACTIVELY REQUEST THE BUSINESS APPLICATION FROM EMILY

**File:** `01-application/README.md`
**Action:** Don't wait for the Business Application to "arrive separately." Start the Personal Application AND email Emily Watrobsky proactively: "Hi Emily, I've started the Personal Application. Could you send the Business Application as well so I can work on both before the May 8 deadline?"

---

### 9. CONSIDER ADDING ONE MORE BACKUP PLAN: WHAT IF MAY 8 DEADLINE IS MISSED?

**File:** None currently addresses this
**Action:** If post-production runs late and the video isn't ready by May 8, what's the plan? Is there any flexibility? Has Emily indicated the deadline is truly hard? This should be understood before it becomes urgent.

---

### 10. VERIFY THAT THE PRODUCTION DOCUMENT (.docx) MATCHES THE MARKDOWN FILES

**File:** `02-video-production/BenchK_SharkTank_Production_v3_FINAL.docx`
**Action:** The .docx file exists but was not readable in this audit (binary format). Someone should manually verify that all numbers, section timings, and script content in the Word document match the markdown files. If the videographer uses the printed .docx as their guide and it doesn't match the latest markdown prep files, there will be confusion on set.

---

## SUMMARY

### What's Strong

- **Number consistency is excellent.** Every figure matches across all 13 files. Zero contradictions found. This is rare and important.
- **Do-not-say compliance is clean.** No prep file accidentally suggests a banned phrase as a response.
- **The script structure is strong.** The energy arc, section timing, and emotional flow are well-designed.
- **The Q&A prep is thorough.** 30 questions with specific red flags and ideal answers.
- **The day plan is extremely detailed.** Minute-by-minute planning shows serious preparation.
- **The three core insights framework is compelling.** Foreign Market Mastery + Replication Logic + Smart Money is a powerful pitch structure.

### What Needs Immediate Attention (Today, May 1)

1. **Start the PandaDoc Personal Application** -- critical path item for the May 8 deadline
2. **Pull margin/COGS data from ERP** -- needed for both applications and filming
3. **Confirm videographer name and contact** -- update documents
4. **Create B-roll Google Drive folder** -- start uploading assets
5. **Fix section number mismatch in day plan** -- prevent confusion on set

### What's Missing but Not Urgent

- Unit economics breakdown (cost per unit, contribution margin)
- CAC calculation
- Year 2 revenue projection with investment
- Competitive landscape detail
- Organizational depth / team structure
- Callback logistics for physical product transport

---

*Audit completed May 1, 2026.*
*Next review: May 3, 2026 evening (final pre-filming check).*
*Auditor: AI Department Director*
