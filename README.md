# Job Plan Generator

Turn OEM equipment manuals into MxLoader-ready IBM Maximo job plans — in your browser, on your own machine.

**▶ [Open the tool](https://shaikhmuzaffar.github.io/Job-Plan-Generator/)**

---

## What it does

Equipment manuals arrive as long PDFs, and turning their maintenance procedures into Maximo job plans is slow work that usually gets done by hand.

This tool does that first pass for you: upload a PDF or paste the text, and it produces a structured job plan you can review, edit, and load straight into Maximo.

## What you get out

- A complete job plan with numbered tasks, in Maximo's own structure
- Labour, material, and tool lines against each task
- Preventive maintenance records with the frequencies stated in the manual
- An Excel workbook formatted for MxLoader — ready to load, no reformatting

## How to use it

1. Open the tool (link above).
2. Upload the equipment manual as a PDF, or paste the procedure text directly.
3. If the manual contains several procedures, choose the one you want.
4. Review what it produced. Edit anything on screen — task wording, durations, quantities.
5. Click export. You get an MxLoader-ready Excel workbook.
6. Load it into Maximo through MxLoader as you normally would.

## Your data stays with you

The tool runs entirely inside your browser. There is no server, no sign-up, and no API key. Manuals you upload are never transmitted anywhere — they are read on your own machine and stay there.

That matters if the manuals you handle are commercially confidential or covered by a client NDA.

You can also download `index.html` and run it locally by double-clicking it.

## A note on what it is

This does a first pass, not a final one. It reads a manual well, but it does not know your site, asset hierarchy, craft codes, or storeroom. Treat the output as a draft that saves you the typing — then apply your own judgement before it goes near production.

---

**Muzaffar Shaikh** · IBM Maximo / MAS Techno-Functional Consultant & Integration Architect · MAS 9 Certified (C1000-183)
