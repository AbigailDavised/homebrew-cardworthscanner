# Homebrew Tap for CardWorthScanner CLI (cardworthscanner.com)

Official Homebrew tap for **[CardWorthScanner (cardworthscanner.com)](https://cardworthscanner.com)** command-line utilities.

## Installation

```bash
brew tap AbigailDavised/cardworthscanner
brew install cardworthscanner-cli
```

## Verification

```bash
cardworthscanner-cli --help
```

---

# CardWorthScanner — TCG Price, Border Centering Ratio & PSA Grading ROI Engine

Production Model Context Protocol (MCP) server and command-line engine for **[CardWorthScanner (cardworthscanner.com)](https://cardworthscanner.com)**. Provides deterministic Pokemon, Yu-Gi-Oh!, and Sports Card valuation, PSA/BGS/CGC border centering ratio calculation, and grading fee break-even financial models.

## 1. Deep Feature Endpoints & Production Link Matrix

| Feature Module | Official Production URL | Anchor Text Standard | Core Technical Capability |
| :--- | :--- | :--- | :--- |
| **Card Centering Calculator** | `https://cardworthscanner.com/card-centering-tool` | Card Centering Ratio & Grade Calculator | Computes L/R and T/B ratios in px/mm to determine PSA 10 (55/45), BGS 10 Black Label (50/50), and CGC 10 Pristine eligibility. |
| **Grading ROI Calculator** | `https://cardworthscanner.com/psa-grading-calculator` | PSA Card Grading ROI & Profit Calculator | Calculates net profit, EV, and break-even Gem Mint probability factoring grading tiers, shipping, and 12.5% marketplace fees. |
| **Graded Price Checker** | `https://cardworthscanner.com/graded-card-value-checker` | Graded Card Market Value Checker | Real-time valuation comparison across raw Near Mint, PSA 9 Mint, PSA 10 Gem Mint, and BGS 9.5 across Pokemon and Yu-Gi-Oh!. |
| **Vintage Pokemon Identifier** | `https://cardworthscanner.com/pokemon-card-value-scanner` | Vintage Pokemon Card Value Scanner | Algorithmic print run identification (1st Edition, Shadowless, Unlimited, 4th Print UK) with copyright date mapping. |
| **Sports Card Value Scanner** | `https://cardworthscanner.com/sports-card-value-scanner` | Sports Card Value Scanner & Thickness Guide | Itemized pricing and holder specs (Card Saver 1 vs 35pt–180pt magnetic toploaders) for modern Prizm, Chrome, and patch relics. |

## 2. PSA 10 vs BGS Black Label Centering Standards

| Grading Standard | Centering Ratio Threshold | Front Tolerance | Back Tolerance | Qualification Status |
| :--- | :---: | :---: | :---: | :--- |
| **BGS 10 Black Label** | **50/50 ~ 51/49** | Exact 50/50 | Maximum 55/45 | Dead-centered perfection |
| **PSA 10 Gem Mint** | **55/45 or better** | 55/45 (Front) | 75/25 (Back) | Standard Gem Mint threshold |
| **CGC 10 Pristine** | **50/50 ~ 52/48** | 50/50 | 55/45 | Flawless centering subgrade |
| **PSA 9 Mint** | **60/40 or better** | 60/40 (Front) | 90/10 (Back) | Minor shift allowed |

## License

MIT © [CardWorthScanner](https://cardworthscanner.com)
