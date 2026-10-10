# SPMS Claims Builder

A one-page tool for preparing SPMS House claims: from events, or general purchases made with House budget.

**Use it:** https://intrinzix.github.io/spms-claims/

## What it does

1. Add one card per payment: the shop, each receipt's amount, and photos of the receipts and the proof of payment.
   - No receipt from the seller? Switch the row to **Proof of Convo** and add the chat screenshot instead.
2. Download the **claim zip**: one PDF per receipt / proof of payment, named to the claims procedure. Every photo is converted to PDF; several photos of one receipt become one multi-page PDF.
3. Copy the two claim emails (Email 1: documents; Email 2: authorise claim) with the total and receipt list filled in.
4. Optional: download the **summary receipt**, a one-page list of every file and the total.

## File names

| Case | Files |
|---|---|
| One receipt, one payment | `BBQ Wholesale Receipt - $718.78.pdf`, `BBQ Wholesale Proof of Payment - $718.78.pdf` |
| No receipt, chat instead | `K Bakery Proof of Convo - $40.pdf`, `K Bakery Proof of Payment - $40.pdf` |
| Same shop, several receipts, one payment | `Shopee Receipt 1 - $8.42.pdf`, `Shopee Receipt 2 - $17.20.pdf`, `Shopee Proof of Payment - $25.62.pdf` |
| Same shop, separate payments | `Prime Receipt 1 - $24.35.pdf`, `Prime Proof of Payment 1 - $24.35.pdf`, `Prime Receipt 2 - $90.85.pdf`, `Prime Proof of Payment 2 - $90.85.pdf` |
| Same shop, separate payments, several receipts in one | `Shopee Receipt 1a - $8.42.pdf`, `Shopee Receipt 1b - $17.20.pdf`, `Shopee Proof of Payment 1 - $25.62.pdf`, `Shopee Receipt 2 - $12.32.pdf`, `Shopee Proof of Payment 2 - $12.32.pdf` |

## Sending a claim

1. Download the claim zip.
2. Email 1 to the Finance Controller, CC the House Director and VP (Student Life), zip attached.
3. Mark Email 1 as important (!).
4. Email 2 from the claimant to the Finance Controller's school email.
5. Text the Finance Controller that the claim has been sent.

## Privacy

Everything runs in your browser. Photos, amounts and names are never uploaded or stored anywhere.

## Credits

PDF and zip generation: [pdf-lib](https://pdf-lib.js.org/), [@pdf-lib/fontkit](https://github.com/Hopding/fontkit), [JSZip](https://stuk.github.io/jszip/). Embedded fonts (summary receipt): Carlito (SIL Open Font License 1.1) and DejaVu Sans Mono (Bitstream Vera license), subset to Latin characters.
