### Javaad Ali

The repositories collected and shared hereunder are provided in support of applications I have submitted to a law firm and to a hedge fund. The code that has been shared in support of the law firm application is code that is actually used in production. The code the to the extent that they provide instruction as to how to encode concepts into a form suitable for representation in code and for use in computation. I am willing to share this code because I do not believe that lawyers from other firms are likely to make their way to this site on their own. 

The code being shared in support of the hedge fund application is hand-waving and demonstrative. The extent of what is presented for discussion below is either very high-level or else directly implied by one of two papers in which reference is made to JPMorgan Research. 

I have not seen the arbitrage argument made anywhere. This could be because people have figured out how to make it work in practice or because everyone is still trying to figure out how to make it work; in either case, the value is in making getting the trade to work in practice somehow. I am not prepared to believe that the idea itself is not widely known, even if papers have not been published to the related effect.  

## Hedge Fund Repositories
| Repository | Summary |
| :--- | :--- |
| **[Quantum-Arbitrage](https://github.com/javaad101/Quantum-Arbitrage)** | [Working paper](https://github.com/javaad101/Quantum-Arbitrage/blob/HEAD/paper/Why_Common_Stock_Prevents_State_Space_Pricing.pdf), Bell/CHSH bounds ($2\sqrt{2}$), Eisenberg–Noe phantom-equity arbitrage ($\Delta_{\mathrm{phantom}} > 0$), and Arrow–Debreu state-price inversion. |
| **[Unitary-Equivalence](https://github.com/javaad101/Unitary-Equivalence)** | Lossless contextual equivalence via post-selected Bell states and the Ricochet / Hilbert–Schmidt identity $\frac{1}{d}\,\mathrm{Tr}(U_1 U_2^\dagger)$. |
| **[Quantum-Clock](https://github.com/javaad101/Quantum-Clock)** | Bare-metal Apple Silicon GPU compute shader (`QuantumClock.metal`) for unitary two-level state evolution over shared `MTLBuffer` memory. |

## Law Firm Repositories
| Repository | Summary |
| :--- | :--- |
| **[SECDatasetBuilder](https://github.com/javaad101/SECDatasetBuilder)** | Here, I demonstrate an approach to problem of how to create a database essentially on demand for purposes that may include business development, getting a sense for what is market or, as here, for other reasons. 
| **[EDGARExhibits](https://github.com/javaad101/EDGARExhibits)** | Here, I demonstrate a method for downloading and sorting all of the documents that have been incorporated by reference in a particular filing. Note that these are not necessarily the same as the documents listed in the header file to a particular filing. Header files are, or so I suspect, the extent of what data providers scrape from EDGAR. As a result, these exhibits can be difficult to access at scale. Here, I download and classify exhibits from every registration statement filed at any point since January 1, 2020. This worked out to 116,968 documents. I will list this on the App Store at some point. ([macOS/iOS client](https://github.com/javaad101/EDGARExhibitsConsole)). |
| **[TaxData](https://github.com/javaad101/TaxData)** | Here, I provide a relatively straightforward way to obtain access to the entirety of the Internal Revenue Code of 1986, as amended and current as of the instant at which the user taps a `refresh` button, together with the entirety of the Treasury Regulations. These are also current as of the instant at which the user taps a `refresh` button. The documents are **fully searchable** and always current. To my knowledge, the only competing product is semiannual release by Wolters Kluwer. |
**[SECFormStore](https://github.com/javaad101/SECFormStore)** | Here, I provide a taxonomy for 106 SEC EDGAR form & exhibit codes across 20 regulatory categories) |
**[ISO20275](https://github.com/javaad101/ISO20275)** | Here, I provide access to a list of all of the entity forms that exist in a particular country. This is for purposes of classifying foreign entities under Treas. Reg. § 301.7701.|
