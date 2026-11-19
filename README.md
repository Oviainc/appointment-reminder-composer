# Appointment Reminder Composer

**A trilingual appointment reminder kit for service businesses — local-first, no account, no subscription.**

**Live tool:** https://oviainc.github.io/appointment-reminder-composer/

![Workflow: book, confirm, remind, show up](assets/workflow.svg)

![Preview of the tool: reminder composer and appointment record side by side](assets/preview.svg)

## What we built

We built this composer for the moment every appointment-based business knows well: the slot is booked, the day is planned around it, and then the client simply does not come — most often because the appointment was forgotten, not refused.

With this tool, we:

- Save **clients and services once** — name, contact details, preferred language, service name and duration — and book each new appointment in a few taps
- Compose a **confirmation at booking**, written in the client's own language, with the date, time, place, and a way to reply and move the appointment instead of vanishing
- Follow the sequence that works — **confirmation, 24-hour reminder, morning-of reminder, on-the-way message** — each step written in English, French, and Spanish, ready to copy and send
- **Send the message where the client actually reads it** — one click opens the composed message in email (addressed to the saved client email when we have it) or in WhatsApp; copy stays available for any other channel
- Download a **calendar file (.ics)** for every appointment, with reminders set a day and two hours before, so the appointment lands in the client's own calendar with its own alerts
- Keep a **message history on every appointment**: each message we compose is logged with its step and date, so we always know what was sent and when
- See the **suggested next step on every booking** — confirmation, 24-hour, morning-of, on-the-way, or record the outcome — worked out from its time and the messages already logged, with that step pre-selected in the composer, so what to send next is decided before the moment arrives
- **Record the outcome on every appointment** — attended, no-show, or cancelled, plus rescheduling in place — so the record reflects what actually happened, not what was planned
- **Record the client's confirmation when they reply**: the reminders ask the client to reply and confirm; one tap on the appointment records that confirmation, with the date. A confirmed badge shows on the booking, the suggested next step stops treating it as unanswered, and the per-client history counts confirmations alongside attendances and no-shows — so we know who answers, not only who arrives. Rescheduling clears the confirmation, because the new time needs a fresh answer
- **Work the still-to-confirm list, not the whole book**: the dashboard counts how many upcoming bookings are confirmed ahead, with the rate, and lists every upcoming booking that has not confirmed yet — when, client, service, contact, and whether the confirmation was sent — so the day-before follow-up calls go only to the clients who have not answered, the short list the current guides prescribe, instead of the whole book or nobody at all
- See **upcoming, today, attended, and no-show totals at a glance**, with the **no-show rate** worked out from completed appointments
- See **history by client**: every client's bookings, attendances, and no-shows in one view, with their no-show rate — so a repeat pattern is visible before the next slot is given away
- **Act on the repeat pattern, targeted — not blanket**: the per-client record flags itself. At two no-shows a client carries a warning badge (one more miss and a deposit applies); at three or more, a deposit flag. For a flagged client, a new booking's suggested next step is the **deposit request** — a ready-made message in the client's language explaining that a deposit now holds their slot, that it comes off the bill in full when they come, and that it only stays with the business if the appointment is missed again without notice. Once the request is logged, the normal confirmation rhythm resumes. The policy lands on the few clients who earned it; everyone else books as usual
- **Fill a freed slot from the waitlist**: clients who wanted a slot and could not get one join a waitlist with the service they want and the times that suit them; when a cancellation or a gap opens a slot, we offer that exact slot with a ready-made message written in the client's language (English, French, or Spanish), send it by email or WhatsApp in one click, and log every offer on their entry — so a freed slot goes to someone already waiting instead of staying empty, and nobody is asked twice about the same opening
- **Follow up kindly after a no-show**: a first message soon after the missed slot, and a second two days later offering a new time — both written in the client's language, firm about the cost of the empty slot without closing the door
- **State the cancellation policy where the client reads it**: when a policy is saved for the business, it travels with the confirmation and the 24-hour reminder, under a label in the appointment language (English, French, or Spanish) — stated in the message itself, not remembered from an earlier conversation
- Export and import a **JSON backup** of everything

## Who we built it for

Salons, barbers, clinics, studios, consultants, trades, and small service teams who work by appointment — especially teams who serve clients in more than one language and are tired of losing booked slots to simple forgetting, and of rewriting the same reminders from scratch.

## Trilingual, properly

The interface switches between **English, Français, and Español**. More importantly, each appointment carries its own language: a client who receives French messages gets a French confirmation and French reminders, even if we work in English day to day. The message templates are written in each language — confirmation, 24-hour, morning-of, on-the-way, and both post-no-show follow-ups — not passed through word-for-word machine translation.

## How the moat works

- **Your data accumulates here.** Every client we save, every service in the library, and every appointment in the history makes the next booking faster. That growing, structured history is a switching cost no blank template can match.
- **Language depth is the niche.** Global scheduling tools often add languages as a thin translation layer. We wrote the full workflow — interface, confirmations, all four reminder steps, and both follow-ups — in English, French, and Spanish from the start.
- **The history compounds.** Every logged message and every recorded outcome builds a per-client record of who confirms, who comes, and who does not. That record drives the suggested next step on every booking and the per-client no-show rate — knowledge a blank template starts from zero on.
- **It embeds in the daily workflow.** Confirming, reminding, and following up are not one-off tasks; they are the daily rhythm of running a full calendar. A tool that sits in that rhythm stays.
- **Clients see it.** Every confirmation, reminder, calendar file, and follow-up a client receives came from here — counterparties discover the kit through the messages themselves.
- **The waitlist is demand on record.** Every client waiting for a slot is a name, a service, and a preferred time already captured, with every offer logged. When a slot frees, the business fills it from its own list instead of hoping the phone rings — and that list, like the client history, only exists because the business built it here.
- **The confirmation record is a work list too.** Confirmations were already counted per booking and per client; now they also sort the upcoming book into confirmed and still to confirm, with the confirmed-ahead rate on the dashboard — so the record tells the desk exactly who to call today, instead of leaving that list to memory.
- **The flag is part of the record too.** Repeat no-shows are counted from the outcomes already logged — no separate list to maintain, nothing to remember at the desk. The warning at two and the deposit flag at three are worked out from the same history that drives the reminders, so the consequence a guide recommends is the consequence the record actually applies.
- **The policy is part of the record too.** The cancellation policy saved for the business travels with the confirmation and the 24-hour reminder, in the appointment's own language, so the terms were stated where the client read them — not remembered differently afterwards.

## Local-first and private

There is no account and no server. Everything is stored only in the browser's local storage on the device where it is used. Nothing is sent anywhere. Export a backup regularly, and import it on another device whenever needed.

## The managed version

This kit is the free, hands-on version of work we run as a managed service: client conversations answered, appointments scheduled and reminded automatically, and follow-up that happens without anyone having to remember it. The kit shows the rhythm; the managed version runs the rhythm for the business, across every booking, every day.

## Use it

Open the live tool, add the business details once, save the first client and service, and book the first appointment. No sign-up step stands in the way.

## Licence

MIT — see `LICENSE`.
