# Feature status — Sports, fitness & class businesses

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 196 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 3 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 2 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 0 | 0 | Native records/view |
| Activity & audit trail | audit | 2 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Classes | records | 2 | 0 | Native records/view |
| Schedules | records | 1 | 0 | Native records/view |
| Enrollment | records | 1 | 0 | Native records/view |
| Attendance | records | 2 | 0 | Native records/view |
| Studios | records | 1 | 0 | Native records/view |
| Students | records | 2 | 0 | Native records/view |
| Teachers | records | 1 | 0 | Native records/view |
| Families | records | 1 | 0 | Native records/view |
| Volunteers | records | 1 | 0 | Native records/view |
| Recitals | records | 1 | 0 | Native records/view |
| Competitions | records | 1 | 0 | Native records/view |
| Tickets | records | 1 | 0 | Native records/view |
| Trial Classes | records | 1 | 0 | Native records/view |
| Summer Intensives | records | 1 | 0 | Native records/view |
| Makeup Classes | records | 1 | 0 | Native records/view |
| Merchandise | records | 1 | 0 | Native records/view |
| Financial Reports | records | 1 | 0 | Native records/view |
| Costumes | records | 1 | 0 | Native records/view |
| Costume Risk | records | 1 | 0 | Native records/view |
| Props | records | 1 | 0 | Native records/view |
| Music | records | 1 | 0 | Native records/view |
| Videos | records | 1 | 0 | Native records/view |
| Photos | records | 1 | 0 | Native records/view |
| Achievements | records | 1 | 0 | Native records/view |
| Measurements | records | 1 | 0 | Native records/view |
| Waitlist | records | 1 | 0 | Native records/view |
| AI Student Placement | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Recital Program | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Parent Communication | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Competition Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recital Choreography Copilot | records | 1 | 0 | Native records/view |
| Smart Class Scheduling Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Student Progress Report Card | records | 1 | 0 | Native records/view |
| Costume Budget Forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Talent Show / Showcase Matcher | records | 1 | 0 | Native records/view |
| Multilingual Parent Portal | records | 1 | 0 | Native records/view |
| AI Photo Tagging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Video Highlight Suggestions | records | 1 | 0 | Native records/view |
| Teacher Workload Balance | records | 1 | 0 | Native records/view |
| Class Description Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Costume Design Brief | integration | 1 | 0 | Provider request records only |
| Routine Scoring Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program Book Content | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive talent identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recital competition optimization | records | 1 | 0 | Native records/view |
| Student progression tracking | records | 1 | 0 | Native records/view |
| Teacher workload balancing | records | 1 | 0 | Native records/view |
| Parent engagement automation | records | 1 | 0 | Native records/view |
| Schedules competitions recitals lack ai endpoints for schedu | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music videos photos lack ai curation suggestion endpoints | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attendance lacks ai no show churn prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No video streaming recording platform integration | integration | 1 | 0 | Provider request records only |
| No parent portal for attendance grades messaging | records | 1 | 0 | Native records/view |
| Limited mobile app for students teachers | records | 1 | 0 | Native records/view |
| No music licensing integration for public performances | integration | 1 | 0 | Provider request records only |
| No webhooks | integration | 1 | 0 | Provider request records only |
| Workouts | records | 1 | 0 | Native records/view |
| Golf | records | 1 | 0 | Native records/view |
| Running | records | 1 | 0 | Native records/view |
| Team | records | 1 | 0 | Native records/view |
| Recovery | records | 1 | 0 | Native records/view |
| Load Balance | records | 1 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Progress | records | 1 | 0 | Native records/view |
| Export | records | 3 | 0 | Native records/view |
| Contact public | records | 1 | 0 | Native records/view |
| Timer | records | 1 | 0 | Native records/view |
| Feedback | records | 2 | 0 | Native records/view |
| Admin | records | 3 | 0 | Native records/view |
| Integrations marketplace | integration | 1 | 0 | Provider request records only |
| Tee Time Management | records | 1 | 0 | Native records/view |
| Membership Management | records | 2 | 0 | Native records/view |
| Handicap Tracking | records | 1 | 0 | Native records/view |
| Tournament Management | records | 2 | 0 | Native records/view |
| Pro Shop & Inventory | records | 1 | 0 | Native records/view |
| Golf Cart Fleet | records | 1 | 0 | Native records/view |
| Driving Range | records | 1 | 0 | Native records/view |
| Lesson Booking | records | 1 | 0 | Native records/view |
| Course Maintenance | records | 1 | 0 | Native records/view |
| Weather Monitoring | records | 1 | 0 | Native records/view |
| Food & Beverage | records | 1 | 0 | Native records/view |
| League Management | records | 1 | 0 | Native records/view |
| Financial Reporting | records | 1 | 0 | Native records/view |
| Member Directory | records | 1 | 0 | Native records/view |
| Caddie Management | records | 1 | 0 | Native records/view |
| Locker Management | records | 1 | 0 | Native records/view |
| Bag Storage | records | 1 | 0 | Native records/view |
| Marshal Scheduling | records | 1 | 0 | Native records/view |
| Pace of Play | records | 1 | 0 | Native records/view |
| Practice Facilities | records | 1 | 0 | Native records/view |
| Greens Fee Management | records | 1 | 0 | Native records/view |
| Dynamic Pricing | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Course Conditions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Handicap Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Product Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Member Communications | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance Optimization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Round Pairing | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Facility Utilization Forecast | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Member Retention | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tournament Format Recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| agentic course marshal monitoring pace a | records | 1 | 0 | Native records/view |
| dynamic pricing engine adjusting by seas | records | 1 | 0 | Native records/view |
| member ltv churn prediction with targete | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| personalized swing analysis from member | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| course condition feedback loop using cou | records | 1 | 0 | Native records/view |
| statistical leaderboard add on for tourn | records | 1 | 0 | Native records/view |
| round pairing optimization for fourso | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| facility utilization forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| member retention intervention ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| tournament format recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| swing analysis vision ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| payment processing surface | integration | 1 | 0 | Provider request records only |
| webhook integration with usga ghin | integration | 1 | 0 | Provider request records only |
| real time course status feed | records | 1 | 0 | Native records/view |
| on course mobile messaging | records | 1 | 0 | Native records/view |
| file upload for swing videos | records | 1 | 0 | Native records/view |
| Turf stress irrigation planner | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Instructors | records | 1 | 0 | Native records/view |
| Belt progressions | records | 1 | 0 | Native records/view |
| Tests | records | 1 | 0 | Native records/view |
| Private lessons | records | 1 | 0 | Native records/view |
| Equipment | records | 1 | 0 | Native records/view |
| Waivers | records | 1 | 0 | Native records/view |
| Contracts | records | 1 | 0 | Native records/view |
| Video library | records | 1 | 0 | Native records/view |
| Instructor certifications | records | 1 | 0 | Native records/view |
| Betting Analyzer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Fantasy Optimizer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Game Strategy | records | 3 | 0 | Native records/view |
| Esports Tracker | records | 3 | 0 | Native records/view |
| Referee Assistant | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Charts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Injury Impact | records | 1 | 0 | Native records/view |
| Performance Regression | records | 1 | 0 | Native records/view |
| Live Betting Optimize | records | 1 | 0 | Native records/view |
| News Sentiment | records | 1 | 0 | Native records/view |
| Favorites | records | 1 | 0 | Native records/view |
| Getting Started | records | 2 | 0 | Native records/view |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Picks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Model performance | records | 1 | 0 | Native records/view |
| cross sport player valuation for daily fantasy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| injury timeline and performance decay prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| live betting optimization with real time win probability updates | records | 1 | 0 | Native records/view |
| referee decision prediction based on context history | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| sentiment analysis on sports news correlated with line | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| social leaderboards and pick following | records | 1 | 0 | Native records/view |
| ai driven injury impact prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| player performance regression modeling | records | 1 | 0 | Native records/view |
| live betting probability updates | records | 1 | 0 | Native records/view |
| integration with official league data apis espn | integration | 1 | 0 | Provider request records only |
| multi sport cross impact modeling | records | 1 | 0 | Native records/view |
| live chat for user discussion tips | records | 1 | 0 | Native records/view |
| social features following picks leaderboards | records | 1 | 0 | Native records/view |
| webhooks for downstream notifications | integration | 1 | 0 | Provider request records only |
| third party integrations beyond import export | integration | 1 | 0 | Provider request records only |
| Injury risk | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Volunteer match | records | 1 | 0 | Native records/view |
| Recruitment pipeline | records | 1 | 0 | Native records/view |
| Fair play bias | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spectator experience | records | 1 | 0 | Native records/view |
| Postgame summary | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Ltad alignment | records | 1 | 0 | Native records/view |
| Sponsor match | records | 1 | 0 | Native records/view |
| Players | records | 1 | 0 | Native records/view |
| Teams | records | 1 | 0 | Native records/view |
| Facilities | records | 1 | 0 | Native records/view |
| Games | records | 1 | 0 | Native records/view |
| Referees | records | 1 | 0 | Native records/view |
| Seasons | records | 1 | 0 | Native records/view |
| Standings | records | 1 | 0 | Native records/view |
| Team balancing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Referee matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Player development | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Game predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Communication generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 196 feature pages were visited in the browser; 194 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 57 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

57 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
