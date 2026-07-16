# 👀 What happens when the wrong part slips into the wrong bin?

On a manufacturing line, that question usually gets answered the expensive way — at the client's site, weeks later, when someone finally notices.

This repo holds a working demo of a station designed to answer it the cheap way: **before the part ever leaves the bench.**

**🔗 Live demo — [munjal-proposal.vercel.app](https://munjal-proposal.vercel.app/)**

No install, no login. Open it and start clicking.

---

## What you're actually looking at

This is an interactive prototype of the touchscreen an operator would use at a real **Bin Control & Part Verification** station — a concept built for Sanden Vikas. Pick a part, set a target count, scan parts into a bin, and watch what happens when everything goes right.

Then try to make it go wrong on purpose.

## Things worth trying

- Fill a whole bin one scan at a time, and read the "what just happened" explanation that appears after each one — it tells you exactly what the controller is doing behind the scenes.
- Use the wrong-part test button and watch the line stop itself, mid-count, without losing what's already been counted.
- Hit **auto-run** and watch the station fill an entire bin hands-free — with one scan deliberately rigged to fail, just so you can see the catch happen.
- Try to switch parts mid-count. See if it lets you.

## Why this exists

Some mistakes are cheap to catch early and expensive to catch late. This prototype is an argument for where, exactly, that line should be drawn on the shop floor — made in a way you can click through yourself instead of just reading about.

It's a **design demonstration**, not production software — a single self-contained HTML page with no backend, built to show what the real thing could feel like to use.
