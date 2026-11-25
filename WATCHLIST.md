# Baker Law Storm Monitor Watch List

Last updated: 2026-11-25 (about 13:12 UTC)

Items below are leads to re-verify, not verified facts. Source pages open when fetched with curl from the shell (NWS, SPC, Iowa Mesonet, FEMA API, gov.texas.gov, TDEM, TWIA, TDI, NHC, govinfo.gov, legacy.sba.gov). "First added" is the date the item entered this file. The 2026-11-25 digest window ended 2026-11-25.

1. **El Paso County / Horizon City flood, Oct. 23 to 26** (first added 2026-11-17)
   - Status: verified draft is in the 2026-11-18 digest. No change found 2026-11-25: no FEMA major disaster declaration in FEMA data, no damage figure.
   - Look for: a FEMA major disaster declaration, a published damage or insured-loss figure, or a change in the county's count of damaged homes (more than 190 per the county on Nov. 6; an earlier article said as many as 60).
   - Post trigger: redraft only for a FEMA declaration or a damage figure. A deadline reminder is possible ahead of Jan. 12, 2027 (SBA physical damage applications); the outreach center at 15371 Kentwood Ave. closes permanently Dec. 8, 2026 at 5 p.m.
   - Last source: https://legacy.sba.gov/article/2026/11/17/sba-offers-relief-texas-businesses-private-nonprofits-residents-affected-adverse-weather (re-opened 2026-11-25; dates unchanged)
   - Drop if no change by 2026-12-18, except for the deadline reminder.

2. **Dec. 29, 2026 deadlines for the summer storms disaster, FEMA DR-4935-TX** (first added 2026-11-17)
   - Status: both dates re-read from official sources 2026-11-25, unchanged. FEMA's declarations data gives lastIAFilingDate 2026-12-29. The SBA correction notice gives the physical loan application deadline as December 29, 2026 and the economic injury deadline as July 30, 2027. Primary counties include Bexar, Kerr, Kendall, Comal, Bandera, Medina, Uvalde and others; no coastal county.
   - Look for: any extension of either date.
   - Post trigger: a deadline reminder in early to mid December. The 2026-11-25 digest told Brandon early December is the time to ask for one. That would be a reminder post, not a storm post; quote the dates from the sources, do not calculate them.
   - Last sources: https://www.fema.gov/api/open/v2/DisasterDeclarationsSummaries?$filter=disasterNumber%20eq%204935 and https://www.govinfo.gov/content/pkg/FR-2026-11-12/html/2026-23016.htm

3. **State Farm Lloyds homeowners rate filing** (first added 2026-11-17, carried from older digests)
   - Look for: a TDI order or statement approving, changing or rejecting the filing.
   - Post trigger: none for a storm post; report under insurance news if TDI acts.
   - Last source: search snippets only; nothing on the tdi.texas.gov news page 2026-11-25 (latest release there is still Nov. 18). Drop if nothing by 2026-12-17.

4. **TWIA interim board meeting on the 2027 probable maximum loss** (first added 2026-11-18)
   - Look for: a date and outcome for the interim meeting TWIA says will be scheduled before February 2027; the next listed regular meeting is Feb. 23, 2027 in Galveston.
   - Post trigger: none for a storm post; report under insurance news.
   - Last source: https://www.twia.org/ (opened 2026-11-25; no interim meeting posted). Drop if nothing by 2026-12-18.

5. **Source access** (first added 2026-11-17)
   - Status: on 2026-11-25, 11 hosts opened, 0 blocked (www.federalregister.gov and news sites were not tried). Read Federal Register notices on www.govinfo.gov (pattern https://www.govinfo.gov/content/pkg/FR-YYYY-MM-DD/html/<document number>.htm). On 2026-11-25 https://api.weather.gov/products/types/PNS/locations/<office> returned HTTP 200 with an empty list for most offices; NWS public information statements and damage surveys were read instead from https://mesonet.agron.iastate.edu/cgi-bin/afos/retrieve.py?pil=PNS<office>&limit=4&fmt=text , which worked for all twelve offices.
   - Look for: whether access holds on the next run, and whether the api.weather.gov lists fill again.
   - Post trigger: none.

Removed 2026-11-25: nothing. No new items: the only weather in the window was light South Plains snow on Nov. 24 with no damage.
