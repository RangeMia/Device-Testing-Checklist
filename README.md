# Device Testing Checklist

A simple, interactive checklist for testing refurbished devices before they go out the door.

Built for hardware teams who need a consistent, repeatable way to check that every device meets quality standards — whether it's a laptop, desktop, tablet, phone, all-in-one, or monitor.

## What it does

- **One checklist, all device types** — select the device type and the checklist adapts automatically, showing only the checks that are relevant. Monitors get display and port checks. Laptops get battery, keyboard, and trackpad checks. No wasted time on things that don't apply.

- **Pass / Fail / N/A for every check** — no ambiguity. Each checkpoint gets a clear status, and you can add a comment to any item if something needs a note.

- **Cosmetic grading** — grade the device from A (like new) through D (heavy wear) right inside the physical condition section.

- **Live progress tracking** — a progress bar and counter show how far through the checklist you are, with a verdict at the bottom: Incomplete, Pass, or Fail.

- **Print anytime** — hit the print button at any stage and get a clean, simplified summary of everything you've filled in so far. Attach it to the device, file it, or hand it to someone.

- **Specifications and notes** — a dedicated area to write down the device specs, OS installed, cosmetic issue locations, and any other observations.

## Sections covered

- Pre-test checks (locks, charger, parts-only flag)
- Physical condition and cosmetic grade
- Display and ports (for monitors/TVs)
- Power and battery
- Performance and connectivity
- Operating system
- Ports and functionality
- Data erasure
- Final checks and tech notes

## How to run it

You need [Node.js](https://nodejs.org/) installed. No other dependencies.

1. Clone this repo
2. Run `node server.js`
3. Open `http://localhost:3322` in your browser

That's it. Everything runs in a single HTML file served by a tiny Node.js server.

## Who is this for

Anyone refurbishing, reselling, or redeploying used devices who wants a structured way to make sure nothing gets missed. It's designed to be practical — not flashy — and works well on both desktop and mobile browsers.

## License

MIT — use it however you like.
