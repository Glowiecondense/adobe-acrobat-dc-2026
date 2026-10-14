# adobe acrobat pro dc

People type this exact string for one of two reasons: they saw the name on a button somewhere and want to know what it is, or they remember the product by a name Adobe stopped using. Both are worth answering, because "Acrobat Pro DC" and "Acrobat Pro" are the same thing at different points in its life, and the difference between Acrobat Pro and everything else Adobe ships under the Acrobat name is where most of the confusion lives.

![Acrobats performing at Look Mum No Hands](assets/cover.jpg)
*The other kind of acrobat: Mimbre performing at Look Mum No Hands. Adobe borrowed the word for agility, not for tumbling. (sasastro, CC BY)*

## What the "DC" stood for

DC is Document Cloud. Adobe introduced it in April 2015 when it moved Acrobat from a numbered release to a continuously updated subscription product. The desktop app became **Acrobat Pro DC** (and a cheaper **Acrobat Standard DC**), the free viewer became **Acrobat Reader DC**, and the whole family got tied to cloud storage and a browser-based set of PDF tools.

In 2020 Adobe quietly dropped the suffix. The paid desktop application is now just **Acrobat Pro**; the free one is **Acrobat Reader**. The engine, the file format, and the feature set didn't change with the name — only the marketing did. So if you're looking at a tutorial, a license page, or an installer that says "Acrobat Pro DC," you are looking at the same product line, described by someone using the 2015–2020 label. Nothing is missing and nothing is extra.

## Pro versus Reader versus Standard

This is the distinction that actually matters, and it has nothing to do with DC.

**Acrobat Reader** is free and does four things: open PDFs, comment on them, fill in and sign forms, and print. That's it. It cannot change a word of text in a PDF, cannot reorder pages, cannot merge two files.

**Acrobat Pro** adds the editing and production tools:

- **Edit PDF** — rewrites text and swaps images inside the page, matching the surrounding font where it can.
- **Scan & OCR** — turns a scanned page into searchable, selectable text.
- **Combine Files** — merges documents, spreadsheets, images, and web captures into one PDF.
- **Preflight** — validates a file against print and archive standards such as PDF/X and PDF/A, and reports what would fail on a press.
- **Redaction** — marks areas for removal and then permanently applies the removal to the content, not just draws black boxes over it.
- **Action Wizard** — records a sequence of steps (optimise, add headers, run OCR, save) and replays it across a folder.
- **Forms authoring, accessibility tagging, Compare Files, Optimize PDF, and the JavaScript console.**

**Acrobat Standard** sits between them. It creates and combines files and does basic editing, but it leaves out Preflight, redaction, the Action Wizard, PDF/A validation, and scripted automation. If you're doing prepress work or handling documents that need material genuinely removed, Standard will stop you at the point where it matters.

![Second view of the same performance](assets/photo.jpg)
*Same troupe, different frame. The naming history below is a bit like this — the same act, photographed under several different labels. (sasastro, CC BY)*

## The naming lineage, in order

If you're trying to work out which version a document, a screenshot, or a colleague is talking about, this is the sequence:

1. **Acrobat 7 Professional** and **Acrobat 8 Professional** — the era when the box said "Professional," which is why so many people still search for "acrobat professional."
2. **Acrobat 9 Pro** — Adobe shortened the name and dropped the word Professional.
3. **Acrobat X Pro** and **Acrobat XI Pro** — the last numbered releases.
4. **Acrobat Pro DC** (2015) — subscription, continuous updates, Document Cloud branding.
5. **Acrobat Pro 2017** and **Acrobat Pro 2020** — perpetual-licence builds sold alongside the subscription. These are frozen: they receive security fixes, not new features.
6. **Acrobat Pro** (2020 onward) — the current name for the subscription track, plus a browser-based version with a reduced feature set.

That lineage explains almost every odd search string in this space. "Adobe acrobat professional dc" is someone merging step 1 with step 4. "Adobe pdf pro dc" is someone who remembers the file format rather than the product. "Acro pro" is shorthand. "Adobe pro" on its own is genuinely ambiguous — Adobe also sells Premiere Pro, Photoshop, and a long list of other applications with "Pro" in the name, so a bare "adobe pro" search can land almost anywhere.

## Practical things that trip people up

**Editing a scanned PDF doesn't work until you OCR it.** Acrobat sees a picture of text, not text. Run Recognize Text first, then edit.

**Edit PDF is a repair tool, not a word processor.** It substitutes fonts when the original isn't embedded, and complex multi-column layouts can reflow in ways you didn't ask for. For heavy rewriting, go back to the source document and re-export.

**Marking redactions isn't redacting.** The markup step only draws the boxes. If you don't apply them, the underlying text is still in the file and still selectable. This is the single most common serious mistake made with the product.

**Fill & Sign and certificate signatures are different tools.** Fill & Sign puts a drawn or typed signature image on the page for convenience. A certificate signature applies a cryptographic signature with an identity behind it and can detect later modification. Use the right one for the stakes involved.

**Check which track you're on before comparing features.** A 2020 perpetual install and a current subscription install open the same files, but menus, cloud features, and newer tools differ. Tutorials rarely say which one they're using.

**Reader's protected mode and Acrobat's protected view are not the same setting**, and turning one off does not turn off the other. If a file is being blocked, check both.

## Before you install or update

- Decide whether you need Pro at all. If you only read, comment, and sign, Reader plus the browser-based tools covers it.
- Check your operating system version against the build you're installing — older perpetual releases stop supporting newer OS versions, and newer builds drop older ones.
- Confirm whether the files you handle are scans. If they are, OCR quality is the feature you'll judge the product on.
- If you work with a print shop or an archive, ask which PDF standard they want (PDF/X-4, PDF/A-2b, and so on) before you start, and use Preflight to check against it rather than guessing.
- Keep one known-good copy of any document you're about to edit heavily. Acrobat's undo history is per-session, and a bad reflow saved over the original is not recoverable from inside the app.

---
Photos: sasastro · CC BY by; sasastro · CC BY by