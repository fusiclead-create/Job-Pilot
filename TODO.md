# JobPilot AI implementation checklist

## Deliver the responsive dashboard shell and white-and-blue visual system
- Use a simple, professional, modern, responsive interface in a white and blue theme.
- Provide a left-rail command-center layout on desktop, collapsing to a top bar on smaller screens.
- Include the JobPilot signal mark, wordmark, navigation, top utility bar, notifications entry point, user identity block, and clear page hierarchy.
- Use accessible status colors and visible workflow progress without decorative motion competing with job data.

## Deliver a dashboard that explains job-search momentum
- Show profile completeness, connected portals, new matches, applications in progress, submitted applications, and recent activity.
- Surface the next best action and honest product status without claiming real portal connections or application submissions.
- Use realistic cybersecurity-job demo data without inventing the user's actual identity or job history.

## Deliver Find Jobs and saved-search interactions
- Support search by job title, keywords, skills, location, country, experience, salary, date posted, remote/hybrid/onsite, company, and visa sponsorship in the interface.
- Show result cards with title, company, location, country, work model, date posted, salary, experience required, important skills, source, visa sponsorship, profile match, and original link.
- Provide View Job, Apply with JobPilot, Save, and Ignore actions; saved/ignored actions may update local demo state.
- Include saved rules for SOC Analyst and related roles across Bengaluru, India, Germany, and Switzerland with 0–3 years experience and last 24 hours or 7 days.

## Deliver the transparent AI-assisted application workflow
- Show steps for reading the job description, checking availability, checking profile match, tailoring resume, generating a cover letter, opening/filling the application, uploading documents, answering known questions, submission confirmation, and tracker update.
- Never invent personal details, experience, companies, job titles, dates, certifications, technologies, achievements, metrics, or unknown answers.
- Make unknown questions and CAPTCHA/MFA/unsupported manual interaction explicit with Needs your input / Manual Action Required states.
- Do not show Submitted unless submission success is confirmed by mock evidence; surface confirmation text, application ID, date/time, confirmation number, and source when available.

## Deliver the application tracker and detail states
- Support Preparing, Applying, Needs Information, Submitted, Failed, Manual Action Required, and Outcome Unknown states.
- Provide filterable application list or board and detail panels with job, source, document versions, timestamps, workflow steps, and evidence fields.
- Make it possible to inspect the selected job/application without losing the surrounding context.

## Deliver job portal connections, career profile, and documents
- Show LinkedIn, Naukri, Indeed, Foundit, Glassdoor, Wellfound, Instahyre, Dice, StepStone, and other supported portals with status, connected account, last sync, resume status, profile status, last search, and last resume update.
- Provide Connect, Reconnect, Disconnect, Open Profile, Sync Profile, Update Resume, and Search Jobs affordances without pretending an external connection completed.
- Include the Career Profile fields for identity, contact, LinkedIn, location, current title, summary, experience, education, skills, tools, certifications, projects, languages, compensation, notice period, preferred locations/countries, work model, authorization, visa sponsorship, and target roles.
- Support master resume PDF/DOCX upload/review UI, separate role-specific resume versions, cover-letter previews, and non-destructive master resume copy.

## Deliver watchlist, notifications, and settings surfaces
- Include Company Watchlist entries for Microsoft, IBM, Cisco, Palo Alto Networks, CrowdStrike, and SonicWall with career URL, country, preferred roles, keywords, location, and monitoring frequency.
- Include new-job, sync, manual-action, and unknown-question notifications with read/dismiss interactions.
- Include monitoring cadence, daily resume refresh, notification preferences, and integration/safety settings.

## Deliver route manifest and implementation quality
- Add `client/public/manus-routes.json` matching every user-facing route; exclude APIs, assets, and 404-only routes.
- Use typed demo data, reusable components, and clear future seams for OAuth, storage, LLM tailoring, ATS workflows, scheduled monitoring, and database persistence.
- Run the configured type check, tests/build, start the configured Preview server, verify the route manifest, and inspect the main views responsively before delivery.
