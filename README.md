### Javaad Ali

The corporate, securities, and tax code is used in production and is, in my view, by far the most important work of all. If the abstractions are right, then everything else simply falls into place, and watching that happen really is a tremendous joy. When you do this work with intentionality and with an amount of imagination, it is, in my view, tremendously rewarding. And it is just--this is work that I enjoy doing very much and that I am very happy to be able to present to you today.

The code presented below is code that I have spent the last four of five years writing. It is code that is being factored out of other code for presentation purposes, and it is code for which I am preparing write-ups as I go. They won't be perfect; I am doing my best to farm as much of this out to some sort of AI where possible but am keen to explain what exactly is happening and why in each of these repositories. The part that is written in plain English is for the attention of the natural person reading this. The balance is intended primarily for the benefit of your AI. 

There is some finance/math-looking code here. I suppose I am including that code here because I believe that it is important and because I believe that it will in fact someday be the case that the ordinary commerce of the lawyer will be transacted through documents of this type. 

## Corporate, Securities & Tax Repositories
| Repository | Summary |
| :--- | :--- |
| **[SECDatasetBuilder](https://github.com/javaad101/SECDatasetBuilder)** | Here, I demonstrate an approach to the problem of how to create a database essentially on demand for purposes that may include business development, getting a sense for what is market or, as here, for other reasons. |
| **[EDGARExhibits](https://github.com/javaad101/EDGARExhibits)** | Here, I demonstrate a method for downloading and sorting all of the documents that have been incorporated by reference in a particular filing. Note that these are not necessarily the same as the documents listed in the header file to a particular filing. Header files are, or so I suspect, the extent of what data providers scrape from EDGAR. As a result, these exhibits can be difficult to access at scale. Here, I download and classify exhibits from every registration statement filed at any point since January 1, 2020. This worked out to 116,968 documents. ([macOS/iOS client](https://github.com/javaad101/EDGARExhibitsConsole)). |
| **[TaxData](https://github.com/javaad101/TaxData)** | Here, I provide a relatively straightforward way to obtain access to the entirety of the Internal Revenue Code of 1986, as amended and current as of the instant at which the user taps a `refresh` button, together with the entirety of the Treasury Regulations. These are also current as of the instant at which the user taps a `refresh` button. The documents are **fully searchable** and always current. To my knowledge, the only competing product is a semiannual release by Wolters Kluwer. |
| **[SECFormStore](https://github.com/javaad101/SECFormStore)** | Here, I provide a taxonomy for 106 SEC EDGAR form & exhibit codes across 20 regulatory categories. |
| **[ISO20275](https://github.com/javaad101/ISO20275)** | Here, I provide access to a list of all of the entity forms that exist in a particular country. This is for purposes of classifying foreign entities under Treas. Reg. § 301.7701. |

## Quantitative & Quantum Repositories
| Repository | Summary |
| :--- | :--- |
| **[Quantum-Arbitrage](https://github.com/javaad101/Quantum-Arbitrage)** | [Working paper](https://github.com/javaad101/Quantum-Arbitrage/blob/HEAD/paper/Why_Common_Stock_Prevents_State_Space_Pricing.pdf), Bell/CHSH bounds ($2\sqrt{2}$), Eisenberg–Noe phantom-equity arbitrage ($\Delta_{\mathrm{phantom}} > 0$), and Arrow–Debreu state-price inversion. |
| **[Unitary-Equivalence](https://github.com/javaad101/Unitary-Equivalence)** | Lossless contextual equivalence via post-selected Bell states and the Ricochet / Hilbert–Schmidt identity $\frac{1}{d}\,\mathrm{Tr}(U_1 U_2^\dagger)$. |
| **[Quantum-Clock](https://github.com/javaad101/Quantum-Clock)** | Bare-metal Apple Silicon GPU compute shader (`QuantumClock.metal`) for unitary two-level state evolution over shared `MTLBuffer` memory. |
