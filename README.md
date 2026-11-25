# GNPPAC Website Redesign

Full public-site redesign concept for [Grand New Party PAC](https://www.gnppac.us/), built by Kirk Automations.

## Scope

- 18 redesigned routes covering the complete public sitemap and five published statements
- Three persistent visual themes
- Seven selectable copy voices
- Five background modes and Freedom Mode
- Responsive navigation and accessible interactions
- Live handoffs for donations, membership, candidate surveys, and dynamic events

## Build and QA

```powershell
node build.mjs
node qa.cjs
```

The automated suite checks every route at desktop and mobile widths for HTTP success, console errors, horizontal overflow, loading completion, theme switching, voice switching, animation controls, Freedom Mode, and the mobile menu.
