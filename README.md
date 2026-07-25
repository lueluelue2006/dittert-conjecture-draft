# dittert-conjecture-draft

Public **draft** snapshot of the final technical package for

> **Dittert’s Conjecture in Dimensions Six through Fifteen**  
> (exact computer-assisted proof; not refereed)

This repository contains **only** the seven release artifacts from the post-audit final package.

## Files

| File | Description |
|------|-------------|
| `Dittert_Conjecture_6_15_revised_final.pdf` | Final manuscript PDF (51 pages) |
| `Dittert_Conjecture_6_15_revised_final.tex` | Final LaTeX source |
| `Dittert_Conjecture_6_15_final_submission.zip` | Full submission / reproduction package |
| `Dittert_6_15_AUDIT_RESOLUTION_74_plus_1.md` | 74+1 audit disposition matrix |
| `Dittert_6_15_verification_manifest.json` | Machine-readable verification manifest |
| `Dittert_6_15_verification_output.txt` | Full human-readable verification log |
| `Dittert_6_15_SHA256SUMS.txt` | SHA-256 checklist for the package |

## Quick check

Unzip the submission package and run:

```bash
unzip Dittert_Conjecture_6_15_final_submission.zip
cd Dittert_Conjecture_6_15_final_submission
python3 -m pip install -r requirements.txt
python3 run_all_certificates.py
```

Expected: `status: passed`.

## Notes

- Not a journal publication. Author / affiliation / ORCID / funding fields may still be placeholders.
- Source conversation: `https://chatgpt.com/c/6a63bcb4-5054-83eb-8fd9-a5198d9c4222`
