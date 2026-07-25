# dittert-conjecture-draft

Public **draft** snapshot of the final technical package for

> **Dittert’s Conjecture in Dimensions Six through Fifteen**  
> (exact computer-assisted proof; not refereed)

## Author

- **Hongyuan Lu**
- ORCID: [0009-0008-9446-9016](https://orcid.org/0009-0008-9446-9016)

This repository contains **only** the seven release artifacts from the post-audit final package.

**Scope of this repo:** dimensions **6 ≤ n ≤ 15** only. It does **not** contain a proof for `n = 5`.

## Related work: dimension 5

For the **n = 5** case, see the independent working proof by **Pedro Paulo Marques do Nascimento** (`pedromnasc`):

- Repository: [pedromnasc/dittert-conjecture-proof](https://github.com/pedromnasc/dittert-conjecture-proof)
- n = 5 package: [n5/](https://github.com/pedromnasc/dittert-conjecture-proof/tree/main/n5)
- PDF: [dittert_n5_exact_proof.pdf](https://github.com/pedromnasc/dittert-conjecture-proof/blob/main/n5/dittert_n5_exact_proof.pdf)
- LaTeX: [dittert_n5_exact_proof.tex](https://github.com/pedromnasc/dittert-conjecture-proof/blob/main/n5/dittert_n5_exact_proof.tex)

That repository’s stated coverage is dimensions **4, 5, and 8–16** (not a substitute for the 6–15 package here). Materials there are likewise working proofs and have not undergone formal peer review.

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

- Not a journal publication. Affiliation / funding / acknowledgements may still be incomplete.
- Compiled PDF title page / metadata use author **Hongyuan Lu** and ORCID `0009-0008-9446-9016`.
