<div align="center">

# Hi, I'm Bulga

**I build backend-heavy products end to end: APIs, AI and media pipelines, billing, and the UI on top.**

Brazil · Open to freelance projects · [@LinkyDevv on X](https://x.com/LinkyDevv)

</div>

## What I can build for you

- **Backends and APIs.** Go and Python services with clean data models, background jobs that survive crashes, and auth and billing (Stripe) that handle money carefully.
- **AI features that are dependable and affordable.** Streaming chat, structured generation with automatic review, cost metering against plan budgets, and pipelines whose output can be inspected and reproduced.
- **Media pipelines.** Audio and video processing with ffmpeg, speech-to-text, translation and voice synthesis behind small, swappable provider interfaces.
- **Product UI.** Server-rendered Go or Next.js interfaces with light and dark themes, built to be fast and clear.
- **Systems tools.** Small, fast Rust utilities that sit close to the operating system.

## Featured projects

Both are commercial products, so their code is private. Each repository below is a public showcase with the product tour, screenshots and an engineering write-up.

<table>
<tr>
<td width="50%" valign="top">

### [Learnix](https://github.com/bulgadev/learnix)

An AI study tutor for Brazilian ENEM students: tutor chat, versioned notes, adaptive practice and flashcards. [Live at learnix.app](https://learnix.app).

<a href="https://github.com/bulgadev/learnix">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bulgadev/learnix/main/assets/hero-dark.jpg">
  <img alt="Learnix study workspace" src="https://raw.githubusercontent.com/bulgadev/learnix/main/assets/hero-light.jpg">
</picture>
</a>

**Highlights:** durable chat turns with a live event stream · exam questions written, then blind-reviewed by a second pass · real-cost usage metering per plan.

`Go` `SQLite` `htmx` `Stripe`

</td>
<td width="50%" valign="top">

### [Dubbline](https://github.com/bulgadev/dubbline)

AI video dubbing with cloned voices and a transcript-first editor, where you fix single lines and only pay to re-voice what you touched.

<a href="https://github.com/bulgadev/dubbline">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bulgadev/dubbline/main/assets/studio-dark.jpg">
  <img alt="Dubbline studio" src="https://raw.githubusercontent.com/bulgadev/dubbline/main/assets/studio-light.jpg">
</picture>
</a>

**Highlights:** translation with a per-line time budget and a fit loop that never cuts speech · content-addressed take cache · lease-based job queue.

`Python` `FastAPI` `PostgreSQL` `Next.js` `ffmpeg`

</td>
</tr>
</table>

## Stack

`Go` `Python` `Rust` `TypeScript` `PostgreSQL` `SQLite` `FastAPI` `Next.js` `htmx` `Docker` `ffmpeg` `Stripe`

## How I work

- Keep the backend modular so any frontend can sit on top of it.
- Make expensive or irreversible operations explicit, quoted before they run, and safe to retry.
- Write down the design: each product above has docs that match the code.
- Ship a working slice first, then harden it with tests and real usage.

## Get in touch

Have a project in mind? Message me on [X (@LinkyDevv)](https://x.com/LinkyDevv). A short description of what you want built and your timeline is plenty to start with.
