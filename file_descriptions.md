* [Scored outreach workbook (.xlsx)](sandbox:/mnt/data/vet_outreach_scored_framework.xlsx)
* [Original 100-contact CSV](sandbox:/mnt/data/vet_clinic_contacts_100_public_emails.csv)

## What’s inside

### `Scored_Contacts`

All 100 contacts with:

* basic syntax validity
* generic inbox flag
* free-email-domain flag
* university / emergency / specialty flags
* heuristic scores for fit, buyer access, simplicity, pain proxy, and economic value
* formula-based total score, priority, and recommended send wave
* a suggested personalization angle
* a draft opener line

### `Wave1_Top25`

A deduped first-wave list of 25 clinics to work first.

### `Outreach_Sequence`

A 4-touch email sequence with timing and copy.

### `Verification_Framework`

A simple bucketed SOP for what to verify first and what to hold.

## How I would use it now

1. Start with `Wave1_Top25`.
2. Run only those 25 through an email verifier.
3. Send only the ones that come back clean.
4. Do not send the whole 100 at once.
5. Use reply/bounce data to tighten the message before touching Wave 2.

## Important limitation

This workbook does **not** include live SMTP/MX verification. It is a prioritization system, not proof that every inbox is deliverable.

## My blunt read

The right move is **not** “verify everything.”
The right move is:

* verify the top 25,
* send a tight first batch,
* learn fast,
* then expand.

Most of the list is usable. Some rows are clearly weaker:

* free-mail inboxes
* generic front-desk aliases
* university / specialty / emergency institutions

Those should not be your first swing.
