# VIJAY FIT — Offline Web App v2.0

## Run it
- Extract the ZIP and open `index.html` for basic local use.
- For installable PWA and service-worker offline caching, serve this folder from `localhost` or HTTPS. Example: `python -m http.server 8000`, then visit `http://localhost:8000`.
- On Android Chrome, use the browser menu → Install app / Add to Home Screen when available.

## Your selected programme
- 5 resistance-training days: Monday, Tuesday, Wednesday, Friday and Saturday.
- Recovery / walking day: Thursday. Full rest: Sunday.
- Balanced physique: chest, back, shoulders, arms, legs and core receive planned work.
- Six monthly programme blocks with purposeful exercise/accessory variations. Key movement patterns recur so performance can be compared; exercises are not changed randomly every week.
- Walking is the chosen cardio. Suggested daily step guides progress conservatively from about 3,000 toward 6,000 across the programme. These are adjustable guides, not compulsory medical targets.
- Set-by-set logging captures load, reps and RIR (reps in reserve). Progression is suggested only when every recorded set reaches the rep ceiling with at least 2 RIR and the clinician-clearance gate is recorded.

## Existing tracking retained
- Today dashboard, water, steps, sleep and daily habits
- Workout date selection, exercise completion, notes, warm-up checklist and per-set logs
- Vegetarian meal checklist and affordable protein reference
- Weight, waist, chest, arm, thigh and hip measurements
- Weight/waist trend charts, session/set totals and training streak
- 180-day roadmap, safety settings, JSON backup/restore and local reset

## Data and privacy
- Records are stored in browser `localStorage` under `vijayFit.v1` to preserve existing VIJAY FIT data on this device.
- No account, analytics, remote API, cloud sync or external libraries are used.
- Export JSON backups regularly. Import replaces current local records.
- Clearing browser/site data or switching browsers/devices can remove or separate records. Keep backups somewhere safe.

## Medical safety — important
- The clearance gate remains locked by default. It prevents a workout from being marked complete and prevents load progression suggestions until the user self-records clinician clearance.
- The checkbox is not medical verification. Only tick it after a clinician has assessed the reported exertional breathlessness and explicitly cleared the relevant activity. Enter any restrictions and follow them; if the clinician has not cleared a movement, do not perform it even if the app lists it.
- Stop exercise for chest pain, faintness, unusual/severe breathlessness, dizziness, severe headache, or new/worsening back/hip pain; seek appropriate medical care. Urgent symptoms require urgent medical attention.
- The app is not a medical device or a substitute for a physician, physiotherapist or qualified in-person trainer. Exercise selection and load suggestions are conservative planning aids, not prescriptions.

## Scope
This is a personal offline-first app build, not a clinically validated or publicly hardened production product. Test in your own browser, keep backups, and have exercise technique reviewed in person. The 180-day plan is a framework; adjust volume, exercise choice and walking to symptoms, recovery and clinician advice.
