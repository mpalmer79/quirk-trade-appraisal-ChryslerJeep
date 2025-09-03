# Quirk Chrysler Jeep Braintree Trade Tool

This repository was cloned from the Quirk Mazda trade tool and retargeted to **Quirk Chrysler Jeep Braintree**.
Key changes performed automatically:

- Replaced dealership name to **Quirk Chrysler Jeep Braintree**.
- Updated domain references to **www.quirkchryslerjeep.com** (with `https://www.` where appropriate).
- Converted plain "Mazda" occurrences to "Chrysler Jeep" in text files.
- Duplicated any files with `mazda` in their filenames to `cdjr` equivalents (non-destructive copy).
- Left images/logos as-is; swap in Chrysler Jeep logos when available (see below).

## What you should verify or tweak

1. **Logos & Branding**
   - Replace any Mazda-specific images under `assets/` with Chrysler Jeep versions (Chrysler/Dodge/Jeep/Ram or a combined Chrysler Jeep lockup).
   - If your HTML references a Mazda brand logo file, it should now also have a `cdjr` twin file from this script. Point references to the Chrysler Jeep file.

2. **Success Page Buttons/Links**
   - Confirm the "Back to Quirk ..." buttons point to **https://www.quirkchryslerjeep.com/**.

3. **Netlify / Forms**
   - If you deploy to Netlify, ensure the form names and environment variables are correct for the Chrysler Jeep property.

4. **VIN decoder / API keys**
   - This template uses NHTSA VPIC (no key needed). If you add other services, update `.env` or function params accordingly.

## Script summary

- 5 files modified with textual replacements.
- 0 brand asset copies created (mazda -> cdjr).

Refer to this file for migration pointers.
