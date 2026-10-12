# The Origin Point: pre-call page

This is a single page you send in the DM after someone replies "origin". It teaches the C-S-B-R chain, tells your story, filters for coachability, and ends with an application. Every application is emailed to you.

## Before it goes live

1. **Connect the application to your inbox.**
   Go to https://web3forms.com, enter `business@tzonkovski.com`, and a free access key arrives by email.
   Open `index.html`, find `YOUR_ACCESS_KEY_HERE` near the bottom, and replace it with your key.
   Until you do this, the form shows "Applications aren't connected yet", so nothing is lost silently.

2. **Add your photo (optional).**
   Save a portrait as `images/miro.jpg`. A 4:5 crop works best, for example 880 × 1100.
   If the file isn't there, the photo slot disappears on its own.

3. **Deploy to Vercel.**
   - Push this folder to a new GitHub repo, for example `MiroTzonkovski/origin-point`.
   - On vercel.com, choose **Add New → Project**, import the repo, set Framework Preset to **Other**, and leave the build command empty.
   - Alternatively, run `npx vercel` from inside this folder.

4. **Fix the link preview.**
   In `index.html`, replace `YOUR-DOMAIN.vercel.app` in the `og:image` line with your real address. That's what makes the link show the green preview card in Instagram DMs.

5. **Send yourself a test application** and check that the email arrives.

## What's in the email

You get the person's name, Instagram handle (with a link), and email if they gave one. You also get their answers, which link of the chain they picked, their Teachability Index (learn × change, out of 100), whether they're ready to invest, and anything else they added.

## Files

- `index.html`: the whole page, including the styles and the form logic
- `images/og.png`: the preview image for DMs and social shares
- `images/favicon.svg`: the browser tab icon
