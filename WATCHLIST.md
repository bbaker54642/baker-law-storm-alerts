# Baker Law Storm Monitor Watch List

Last updated: 2026-11-18 (second run of the day, about 22:00 UTC)

Items below are leads to re-verify, not verified facts. In the second run on 2026-11-18 most source hosts opened when fetched with curl from the shell (NWS, SPC, Iowa Mesonet, FEMA API, SBA, gov.texas.gov, TDEM, TWIA, TDI, KFOX, Yahoo, NHC). "First added" is the date the item entered this file.

1. **El Paso County / Horizon City flood, Oct. 23 to 26** (first added 2026-11-17)
   - Status: SBA declaration, storm dates and deadlines confirmed on the SBA page 2026-11-18. Verified draft is in the 2026-11-18 digest.
   - Look for: a FEMA major disaster declaration, a published damage or insured-loss figure, or a change in the county's count of damaged homes (190 per the county on Nov. 6; an earlier article said as many as 60).
   - Post trigger: redraft only for a FEMA declaration or a damage figure. A deadline reminder is possible ahead of Jan. 12, 2027 (SBA physical damage applications); the outreach center at 15371 Kentwood Ave. closes Dec. 8, 2026.
   - Last source: https://legacy.sba.gov/article/2026/11/17/sba-offers-relief-texas-businesses-private-nonprofits-residents-affected-adverse-weather (opened 2026-11-18)

2. **FEMA DR-4935-TX Individual Assistance deadline** (first added 2026-11-17)
   - Status: FEMA's declarations data gives lastIAFilingDate 2026-12-29 (opened 2026-11-18). The fema.gov/disaster/4935 page returned 403.
   - Look for: any extension of the date; the fema.gov page if it opens.
   - Post trigger: a deadline reminder in early to mid December.
   - Last source: https://www.fema.gov/api/open/v2/DisasterDeclarationsSummaries?$filter=disasterNumber%20eq%204935 (opened 2026-11-18)

3. **SBA loans under FEMA-4935-DR** (first added 2026-11-17)
   - Look for: the physical damage and economic injury deadlines in the Federal Register notice or an SBA release. A search summary gave Dec. 29, 2026 for physical loans.
   - Post trigger: confirmed deadline within three weeks.
   - Last source: https://www.federalregister.gov/documents/2026/11/12/2026-23016/presidential-declaration-of-a-major-disaster-for-the-state-of-texas (blocked 2026-11-18; try sba.gov instead)

4. **State Farm Lloyds homeowners rate filing** (first added 2026-11-17, carried from older digests)
   - Look for: a TDI order or statement approving, changing or rejecting the filing.
   - Post trigger: none for a storm post; report under insurance news if TDI acts.
   - Last source: search snippets only; nothing new on tdi.texas.gov news page 2026-11-18. Drop if nothing by 2026-12-17.

5. **TWIA interim board meeting on the 2027 probable maximum loss** (first added 2026-11-18)
   - Look for: a date and outcome for the interim meeting TWIA says will be scheduled before February 2027; next regular meeting is Feb. 23, 2027.
   - Post trigger: none for a storm post; report under insurance news.
   - Last source: https://www.twia.org/twia-board-votes-on-2027-operating-budget-at-corpus-christi-meeting/ (opened 2026-11-18)

6. **Source access** (first added 2026-11-17)
   - Status: on 2026-11-18 (second run) 12 hosts opened, 3 blocked (www.federalregister.gov, www.ktsm.com, cw39.com). Fetching with curl from the shell worked where earlier runs reported every host refused. NWS survey statements are readable at https://api.weather.gov/products/types/PNS/locations/<office>.
   - Look for: whether access holds on the next run.
   - Post trigger: none.

Removed 2026-11-18: Gaines and Dawson county tornadoes (resolved: NWS survey read, EF1 north of Lamesa destroyed one outbuilding, not post-worthy); Nov. 15 to 16 coastal cold front (resolved: no storm reports in the data); TWIA Nov. 10 board follow-up (resolved: summary read); Governor's 11/11/26 severe storm proclamation (resolved: renewal of a July 2026 proclamation, not a new event).
