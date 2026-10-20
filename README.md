# aiventure-identity

Masterul unic al identității AiVenture S.R.L. Tot ce privește firma (date legale, contact, profiluri, rețea, texte, logo, favicon-uri, ofertă, decizii) se editează **doar aici**. Site-urile, Workerul de rețea și schema.org/meta se generează din acest depozit.

## Structură
- `identitate/aiventure-identity.json` — masterul. `null` = lipsă (nimic nu se inventează); lista `lipsuri` arată ce rămâne de completat.
- `brand/` — logo (512, 256 în WebP/JPG/PNG), favicon-uri, manifest, `head-snippet.html`; `brand/variante/` = variante neoficiale.
- `decizii/decizii.json` — registrul deciziilor.

## Reguli
1. Un singur e-mail oficial: contact@5thelement.ai.
2. Fișierele se modifică prin pull request, din browser; nu se ține nicio copie locală.
3. Numele de bază al fișierelor nu se schimbă; versiunea stă în câmpul `_meta` și în istoricul Git.
4. Tot conținutul este public.

## Stare
v1.0 (2026-10-20). Urmează: acțiune GitHub care publică masterul în KV și pe un URL public, Workerul de rețea care îl citește, validator de completitudine.
