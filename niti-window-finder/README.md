# NiTi Window Finder v1.5 — presentation demo

Self-contained, static HTML research prototype for exploring laser-power and scan-speed conditions within the original LPBF NiTi study domain.

## Open
Open `index.html` through GitHub Pages, or download and open it locally in a browser. The app contains embedded data and has no backend or external JavaScript dependencies.

## Scientific scope
- This is the archived **v1.5** prototype using the **earlier GPR-based surrogate/UQ screening**. It has **not** been updated to the November 2026 TensorSpline density / new GPR `A_f` models.
- Quantities labeled *joint screening frequency* are empirical results of residual scenario propagation, **not calibrated probabilities of manufacturing success**.
- The conditions shown are research-screening candidates, **not experimentally validated manufacturing recipes**. Experimental validation is ongoing.
- Fixed study context: pre-alloyed NiTi; SLM 280 HL; 30 μm layer thickness; 80 μm hatch spacing; only laser power and scan speed are varied.
- The code and embedded data were retained from `niti_window_finder_v1.5.html`; deployment changes only clarify the user-facing uncertainty labels and add the disclosure.

## Provenance and attribution
Original app: `niti_window_finder_v1.5.html` (September 2026 archived version).
Author credit and Elahinia Lab copyright attribution are retained in the interface. No open-source license is claimed or granted here.

## Future
The planned recipe-maker update will integrate the finalized surrogate models, recalculated uncertainty treatment, and experimental verification.
