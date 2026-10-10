# SPMS Claims Builder

A one-page tool for preparing SPMS House claims: from events, or general purchases made with House budget.

**Use it:** https://intrinzix.github.io/spms-claims/

## What it does

1. Add one card per payment: the shop, each receipt's amount, and photos of the receipts and the proof of payment.
2. Files are named to the claims procedure automatically:
   - `[Company] Receipt - $[Amount]`, `[Company] Proof of Payment - $[Amount]`
   - Several receipts, one payment: `Receipt 1`, `Receipt 2`, ...
   - Several payments at the same shop: `Receipt 1.1`, `Receipt 1.2`, `Proof of Payment 1`, ...
3. Download:
   - **Claim zip**: the named files, ready to email to the Finance Controller.
   - **Claim pack PDF**: a summary page plus each receipt shown beside its proof of payment.
4. Copy the two claim emails (Email 1: documents; Email 2: authorise claim) with the total and receipt list filled in.

## Sending a claim

1. Download the claim zip.
2. Email 1 to the Finance Controller, CC the House Director and VP (Student Life), zip attached.
3. Mark Email 1 as important (!).
4. Email 2 from the claimant to the Finance Controller's school email.
5. Text the Finance Controller that the claim has been sent.

## Privacy

Everything runs in your browser. Photos, amounts and names are never uploaded or stored anywhere.

## Credits

PDF and zip generation: [pdf-lib](https://pdf-lib.js.org/), [@pdf-lib/fontkit](https://github.com/Hopding/fontkit), [JSZip](https://stuk.github.io/jszip/). Embedded fonts: Carlito (SIL Open Font License 1.1) and DejaVu Sans Mono (Bitstream Vera license), subset to Latin characters.
