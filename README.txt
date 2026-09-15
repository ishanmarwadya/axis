SAARTHI — CUSTOMER APP DEMO
===========================

START
1. Extract this ZIP completely.
2. Open index.html in a current Chrome, Edge, Firefox or Safari browser.
3. Explore the Axis Bank home, then select SAARTHI in the bottom navigation.
4. Choose Set up my financial picture, select accounts and confirm permissions.
5. Explore the app. No installation, internet, API key or sign-in is needed.

DISPLAY CONTROLS
----------------
Three controls are available from the Axis Bank home screen and beside
notifications throughout the experience:
  Phone / monitor   Switch between desktop and a 430px live mobile preview.
  Moon / sun        Switch between light and dark themes.
  EN / हिंदी        Switch core navigation, onboarding and key app content
                    between English and Hindi.

The display choices persist in this browser. On an actual phone, responsive
mode applies automatically; the mobile-preview button remains available so a
presenter can return to the desktop canvas. Hindi is a product-demonstration
localization: financial values, account/provider names and some detailed legal
or explanatory copy remain in English to preserve the source terminology.

Keep index.html, styles.css, app.js, companion.css and companion.js together.
Also keep axis-shell.css, axis-shell.js and saarthi-cashflow.png with them.
You can place all eight files together on any static web host.
All icons and charts are embedded vector UI elements; no image downloads,
font downloads or external dependencies are required.

PRESENTATION WALKTHROUGH
------------------------
1. Onboarding: Select all 17 sample records (or choose individual accounts).
   Review the optional transaction permission and displayed access settings.
2. Overview: ₹49L financial assets less ₹4L loan = ₹45L net financial wealth.
   August income ₹1.40L less ₹1.00L spending = ₹40,000 available to allocate.
3. Spending: Change month, search transactions, filter by category, inspect
   a transaction, edit budgets, and download the transactions as CSV.
4. Investments: Inspect allocation and individual holdings. The portfolio
   includes savings, FDs, mutual funds, stock baskets, EPF, NPS, bonds and gold.
5. Goals: Open a goal to adjust the monthly contribution/horizon, select a
   priority, or add a new goal. Complete-history contributions cannot exceed
   the visible surplus. Lower an existing contribution before allocating more.
6. Scenario: Move the home-goal slider. Diverting ₹5,000/month changes the
   fixed schedule from 48 months to approximately 59 months. Save a comparison.
7. Insights: Open an explanation, see its calculation and assumptions, and
   mark an action complete. Actions never transfer funds.
8. Reports: Download a standalone HTML report, or choose Print / Save PDF
   and select your browser's PDF destination. Reports reflect shared accounts.
9. My review: Save notes, prepare a handover, book a sample appointment,
   reschedule, or cancel. No invitation is sent.
10. Data & privacy: Revoke an account and return to Overview to show the
    recalculated totals. Revoke all, reconnect, or reset for the next demo.

Before step 1, begin on the Axis Bank home. Show the SAARTHI 360-degree card,
the fourth bottom-navigation action and general Ask Axis guidance. The bottom
navigation is Home, Services, Pay, SAARTHI and More, with Pay as the central
primary action. Open the
SAARTHI entry screen, then choose Set up my financial picture to reach consent.

Ask SAARTHI opens a scripted, local companion. Suggested questions work
without a network or AI API. Free-text replies route to spending, reserve,
goals, investment information, insurance or permission explanations.

DATA MODEL
----------
Fictional profile: Arjun Mehta, 34, Bengaluru. Snapshot: 5 September 2026.
Financial assets:
  Bank savings       ₹2,40,000
  Fixed deposits     ₹8,00,000
  Mutual funds      ₹16,00,000
  Stock baskets      ₹5,60,000
  Retirement        ₹12,00,000
  Bonds              ₹3,00,000
  Gold ETF           ₹2,00,000
  Total             ₹49,00,000
  Loan principal     ₹4,00,000
  Net wealth        ₹45,00,000

Employer health cover: ₹5L, excluded from assets and net wealth.
Personal insurance is unverified. The portfolio intentionally spans more
categories than the slide persona while preserving its overall balance sheet.

Goal balances are manual earmarks of existing assets, never additional assets.
The home and reserve goals start with the same ₹8L and ₹2.4L sample earmarks.
The home scenario assumes contributions of ₹20,000/month for months 1–12,
then ₹26,666.67/month. Diversion reduces those home contributions only.
No returns or inflation are added. The flat goal calculator is separate.

SCOPE AND STORAGE
-----------------
This is a presentation-ready front-end prototype, not a production bank app.
All financial records and team profiles are fictional. There is no Account
Aggregator integration, authentication, live AI, licensed advice service,
transaction execution, background refresh, file upload, or live booking.
Displayed consent periods are illustrative, not time-enforced bank permissions.

Permissions control which built-in records are included in calculations.
Revoking hides those records from metrics, insights and reports. Because the
mock dataset ships inside app.js, revocation does not erase that source code.
Goals, notes, budgets and sample bookings persist locally until Reset demo.

Browser localStorage remembers demo choices. File-URL storage behavior varies
by browser. If it is unavailable, the app continues with session-only state.
Do not enter real account details or sensitive information into the demo.
No analytics, cookies, external requests or data transmission are included.

RESPONSIVE AND ACCESSIBLE UI
----------------------------
Desktop sidebar; mobile bottom navigation plus a menu for all views.
The desktop phone toggle provides an in-page mobile frame for presentations.
Keyboard-operable buttons/forms, visible focus, native dialog focus behavior,
Escape/backdrop dismissal, semantic tables, chart text alternatives, and
reduced-motion support are included. Print styling is provided for reports.

FILES
-----
index.html   Entry point
styles.css   Responsive Axis-inspired visual system and print styles
app.js       Fictional data, calculations, UI and local interactions
companion.js Contextual coaching, fitness, budgets, scenarios, wrapped, rewards
companion.css Enhanced desktop/phone layouts, theme contrast and components
axis-shell.js Axis banking home, navigation, SAARTHI entry and generic chat
axis-shell.css Responsive Axis banking shell and SAARTHI entry styling
saarthi-cashflow.png Supplied financial cash-flow illustration for entry screen
README.txt   Setup and presentation guide

VALIDATION
----------
JavaScript syntax, static asset references, financial totals, scenario math,
permission filtering and page generation were checked programmatically.
This version has not been browser-automation tested. Do a rehearsal in the
browser/device you will use for the presentation, particularly PDF printing.

No commercial pricing, paid tiers or subscription screens are included.
SAARTHI is a proposed concept; no affiliation or launch is asserted.

FINAL COMPANION UPDATE — SEPTEMBER 2026
--------------------------------------
The original journeys are retained and extended. Main branding stays
YOUR FINANCIAL COMPANION; chat is SAARTHI AI — Your personal CFO.
The assistant uses local contextual rules, not a live language model.

Suggested new demonstration sequence:
1. Select all sample accounts and transaction history. Home starts with a
   financial-fitness hero, visible wealth, prioritised insights and goals.
2. Open Fitness. The starting illustrative score is 76/100, with 3/5 pillars
   assessable. Open each pillar and 'How the score works' for exact rules.
3. Confirm my profile: enter fictional personal policies, dependants, regime
   and document readiness. Protection and Taxes become assessable. They are
   checklist measures, not policy adequacy or tax-efficiency ratings.
4. Spending: set, edit and remove any category budget. Try Dining at 10,000;
   its overspending insight disappears. Custom names are planning-only until
   matching imported records exist; the demo does not invent transactions.
5. Investments: use the asset-class tiles, individual holdings and direct-stock
   sector breakdown. Missing fund fees, look-through holdings and market-cap
   data are clearly distinguished from assessed facts.
6. Insights: open 'Why this matters', inspect the source, save a next step and
   mark it done. Positive behaviour is recognised alongside areas to improve.
7. Scenarios: test expense changes, more investing, an additional EMI, equity
   falls, reduced spending, a purchase, or faster corpus-building. Save and
   reopen a scenario. Existing goal contributions are deducted before showing
   unallocated cash; the initial plan already allocates the full 40,000 surplus.
8. Money Wrapped: June–August story cards, largest categories, expense trends,
   subscription records and earlier/later comparison. No invented annual story.
9. Rewards: complete the buffer lesson for 20 points, save a scenario and
   claim its 25-point milestone. Redeem the 30-point sample wellness benefit.
   Open its demo pass; retrying cannot duplicate points or redemption.
10. Reports: score and five-pillar summary now precede the original holistic
    financial report. HTML export works offline; PDF uses browser printing.

SCORING AND HISTORICAL BOUNDARIES
--------------------------------
The overall fitness index averages assessable pillars equally. Unknown pillars
are excluded, not scored zero. Full-data initial component scores are Spending
89, Borrowing 81, Wealth 59. The average rounds to 76. It is not a validated
financial-health, bureau, suitability or investment-performance score.

Spending: 60% surplus-ratio component (capped at a 30% surplus ratio) plus 40%
active-budget adherence. Borrowing: 100 minus 150 times known EMI/income.
Wealth: half cash/reserve-target coverage (capped) and half one minus the
largest shared asset-category share. Protection: presence of declared personal
health and life policies (or no dependants); adequacy is not assessed. Taxes:
four self-confirmed preparation documents after choosing a tax regime.

Three expense snapshots are available: June 89,000, July 94,000, August 100,000,
with income 140,000 in each complete sample. Historical records are scaled
fixtures, not actual observed financial behaviour. Expense rounding reconciles
exactly at category level. Any month comparison recomputes current budgets and
holds all non-spending pillar inputs constant; it is not observed score history.

No tax deduction eligibility, expected returns, fraud, duplicate subscriptions,
fund overlap, risk suitability or personal insurance adequacy is fabricated.
Early corpus-building uses the home goal as an explicit illustrative proxy;
it is not a retirement adequacy model. Financial actions remain simulations.

REWARDS RULES
-------------
Local ledger with one-time milestone ids; redemptions cannot exceed balance.
Learning 20 points; saved scenario 25; self-reported checklist completion 15.
The budget-review milestone is 5 points per met active August budget, bounded
10–40, and requires complete sample cash history. Learning does not require
financial data sharing. No rewards for buying, investing, borrowing or granting
consent. Benefits and partners are fictional; passes have no real cash value.
Reset clears the ledger, redemptions, profile, checklist and saved scenarios.

VALIDATION OF THIS UPDATE
-------------------------
Static/syntax and Node-based interaction checks cover all 12 routes across
English/Hindi, dark/light and phone/desktop state combinations; consent
filtering; score formulas; calculations; budget CRUD; profile forms; scenarios;
reward balance and duplicate-claim prevention; reset and report escaping.
These are programmatic checks, not browser rendering or touch-device tests.
Please rehearse on your intended browser before the final presentation.

No external images are needed: all artwork, score rings, charts and icons are
embedded CSS/SVG assets and remain crisp offline. New core journeys are
bilingual; inherited detailed account names and some specialist/legal text
retain English. Device-local preferences persist from the first consent screen.

AXIS BANK INTEGRATION UPDATE
----------------------------
The app now opens on a customer-facing Axis banking home rather than SAARTHI
onboarding. The home mirrors the supplied app structure: Axis header, greeting,
horizontal feature cards, visible balance, quick actions, transactions,
personalised prompts, general money chat and a fixed bottom bar. SAARTHI replaces
the Deals position and is also accessible from the 360-degree wealth card,
Invest quick action and guidance cards.

Tapping SAARTHI first opens a dedicated entry screen using the supplied
cash-flow image. Only the next explicit CTA starts SAARTHI consent. Returning
customers continue to their saved workspace. The AXIS BANK control in the
SAARTHI header returns to the main banking home without clearing data.

The Axis-level Ask interface provides general financial education and does not
use SAARTHI account context. Inside SAARTHI, Personal CFO answers can use only
the accounts and permissions the customer selected.

The tax experience is now a dedicated Tax Planner for Arjun's confirmed
FY 2026-27 old-regime profile: ₹16.8L gross salary, ₹84,000 employee EPF and
₹20,000 self-NPS contribution. It shows ₹66,000 of unsupported 80C headroom and
₹30,000 of additional NPS headroom as review items—not product recommendations
or guaranteed savings. It also flags HRA-document requirements for ₹28,000
monthly rent, personal health-premium evidence, FD interest certificates and
AIS/Form 26AS reconciliation. Users can edit the regime and values, complete
the three document checks, and see the readiness score recalculate.

Tax amounts use planning limits for the selected regime. The app does not
calculate final liability, assume HRA eligibility from rent alone, treat an NPS
balance as a current-year contribution, or infer taxable FD interest from a
balance and stated rate. The customer is directed to verify filing treatment.
