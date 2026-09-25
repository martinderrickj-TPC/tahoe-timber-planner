# Tahoe Timber Planner

A working demo from [Tahoe Wood](https://tahoewood.org). You sketch a backyard home or ADU built from nail-laminated timber (NLT) panels made locally from Tahoe forest-thinning wood on a 4-ft plywood module. The planner then:

- checks what a Lake Tahoe lot allows (TRPA coverage, California ADU size and height)
- screens the roof for ASCE 7-22 snow loads
- lists every panel
- shows a tiered price guide (timber kit, weathertight shell, move-in ready)
- lists the Tahoe-specific savings that apply to the lot

The public version includes six real sample lots from TRPA's public parcel service. Addresses and parcel numbers are left out.

The rules, snow loads, panel depths and prices are illustrative placeholders for discussion. They are not code determinations, engineering or quotes.

It's a single static page (`index.html`) that loads three.js from cdnjs/jsDelivr and fonts from Google Fonts.

Also included: `nlt.html`, an NLT producer calculator for prospective panel makers. It covers cost per panel, margin, breakeven and volume, based on Tahoe Wood's draft NLT financials with lumber counted for the whole panel.
