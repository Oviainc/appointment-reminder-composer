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
- See **upcoming, today, attended, and no-show totals at a glance**, with the **no-show rate** worked out from completed appointments
- See **history by client**: every client's bookings, attendances, and no-shows in one view, with their no-show rate — so a repeat pattern is visible before the next slot is given away
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
- **The policy is part of the record too.** The cancellation policy saved for the business travels with the confirmation and the 24-hour reminder, in the appointment's own language, so the terms were stated where the client read them — not remembered differently afterwards.

## Local-first and private

There is no account and no server. Everything is stored only in the browser's local storage on the device where it is used. Nothing is sent anywhere. Export a backup regularly, and import it on another device whenever needed.

## The managed version

This kit is the free, hands-on version of work we run as a managed service: client conversations answered, appointments scheduled and reminded automatically, and follow-up that happens without anyone having to remember it. The kit shows the rhythm; the managed version runs the rhythm for the business, across every booking, every day.

## Use it

Open the live tool, add the business details once, save the first client and service, and book the first appointment. No sign-up step stands in the way.

## Licence

MIT — see `LICENSE`.
