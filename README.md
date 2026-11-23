### Javaad Ali

Quantitative finance, unitary & Hilbert-space representation learning, state-space asset pricing, and native macOS/Swift systems for structured SEC, financial, and statutory corpora.

#### SEC EDGAR, Capital Markets & Statutory Systems
- **[SECDatasetBuilder](https://github.com/javaad101/SECDatasetBuilder)** — Zero-dependency Swift 6 distributed `'33 Act` / `'34 Act` filing and Item 16 exhibit-tree ingestion engine (`S-1`, `F-1`, `424B4`, `10-K`, `10-Q`, `8-K`), content-addressed SHA-256 `AtlasTextBlock` compiler, and 16-feature logistic boundary classifier with paralegal-in-the-loop online updates.
- **[EDGARExhibits](https://github.com/javaad101/EDGARExhibits)** — Server-side Swift 6 (Hummingbird 2) + React/ECharts **EDGAR Deal & Market Trends Observatory** classifying `116,968` registration-statement exhibits and deterministically extracting Form S-1 Facing-Page & Item 501(b) cover-page deal terms across `1,879` `333-` registration chains (companion macOS/iOS client: **[EDGARExhibitsConsole](https://github.com/javaad101/EDGARExhibitsConsole)**).
- **[SECFormStore](https://github.com/javaad101/SECFormStore)** — Zero-dependency, `Sendable` Swift taxonomy of 106 official SEC EDGAR filing and exhibit codes across 20 regulatory categories.
- **[TaxData](https://github.com/javaad101/TaxData)** — Zero-dependency Swift 6 lossless XML/JSON statutory & regulatory document tree (`DocumentNode`), Title 26 USC / 26 CFR citation parser, SQLite FTS5 engine, and multi-window native macOS `DocumentGroup` workbench.
- **[ISO20275](https://github.com/javaad101/ISO20275)** — ISO 20275 Entity Legal Forms mapped by jurisdiction for Treas. Reg. § 301.7701 entity classification.

#### Working Paper & Quantum / State-Space Research
- **[Why Common Stock Prevents State-Space Pricing](https://github.com/javaad101/Quantum-Arbitrage/blob/HEAD/paper/Why_Common_Stock_Prevents_State_Space_Pricing.pdf)** — Structural arbitrage from entity-level equity rank deficiency ($N \ll D$) and Eisenberg–Noe phantom equity ($\Delta_{\mathrm{phantom}} > 0$) under simultaneous liquidation, with pre-waterfall formula primitives for exact Arrow–Debreu state-price inversion ([Quantum-Arbitrage repo](https://github.com/javaad101/Quantum-Arbitrage)).
- **[Unitary-Equivalence](https://github.com/javaad101/Unitary-Equivalence)** — Lossless contextual equivalence via post-selected Bell states and the Ricochet / Hilbert–Schmidt identity $\langle\Phi^+|(U_1 \otimes U_2^*)|\Phi^+\rangle = \frac{1}{d}\,\mathrm{Tr}(U_1 U_2^\dagger)$, preserving non-invariant degrees of freedom in orthogonal subspaces.
- **[Quantum-Clock](https://github.com/javaad101/Quantum-Clock)** — Bare-metal Apple Silicon GPU compute kernel (`QuantumClock.metal`) implementing unitary two-level state evolution over shared ARM64 `MTLBuffer` memory.
