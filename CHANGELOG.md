# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.11.0] - 2026-01-18

### Added
- 8 new crypto plugin skills with full PRD/ARD documentation and Python implementations:
  - **Blockchain & On-Chain**: blockchain-explorer-cli, on-chain-analytics, mempool-analyzer, whale-alert-monitor, gas-fee-optimizer
  - **NFT & Tokens**: nft-rarity-analyzer, token-launch-tracker
  - **Infrastructure**: cross-chain-bridge-monitor, wallet-security-auditor
- Firebase Hosting deployment workflow for claudecodeplugins.io
- Firebase Analytics integration with measurement ID tracking
- Google Secret Manager integration for secure Firebase config

### Fixed
- Gemini code review feedback for all new crypto skills:
  - Timezone-naive datetime operations (now UTC)
  - Empty except clauses with explanatory comments
  - Unused import cleanup
  - Config loading from settings.yaml
  - Mock data fallback with explicit --demo flag

### Infrastructure
- GitHub Actions workflow for Firebase Hosting deployment
- Workload Identity Federation for keyless GCP authentication
- All crypto skills follow nixtla enterprise PRD/ARD standard

### Metrics
- New crypto skills: 8 (completing Batch 5 & 6)
- Commits since v4.10.0: 29
- PRs merged: 10
- Total files changed: 221
- Lines changed: +23,839 / -19,891

## [4.10.0] - 2026-01-15

### Added
- 13 new crypto plugin skills with full PRD/ARD documentation and Python implementations:
  - **Market Data & Pricing**: market-price-tracker, market-movers-scanner, crypto-news-aggregator, market-sentiment-analyzer
  - **Portfolio & Tax**: crypto-portfolio-tracker, crypto-tax-calculator
  - **DeFi**: defi-yield-optimizer, liquidity-pool-analyzer, staking-rewards-optimizer, dex-aggregator-router, flash-loan-simulator
  - **Trading & Derivatives**: arbitrage-opportunity-finder, crypto-derivatives-tracker
- Firebase Hosting integration for marketplace website
- Firebase Analytics for download tracking

### Changed
- Updated skill validator compliance for backtester and signal generator skills
- Unified theme colors across all marketplace pages (CSS consolidation)
- Updated .gitignore for firebase cache and skill data files

### Infrastructure
- All crypto skills follow nixtla enterprise PRD/ARD standard
- Each skill includes: SKILL.md, PRD.md, ARD.md, Python scripts, references, config
- Skills use DeFiLlama, CoinGecko, CryptoCompare APIs (free tiers)

### Metrics
- New crypto skills: 13 (with full documentation)
- Commits since v4.9.0: 50
- PRs merged: 8 (crypto skill branches)
- Total files changed: ~200
- Lines added: ~25,000

## [4.9.0] - 2026-01-08

### Added
- 10 new SaaS vendor skill packs (Batch 3): Apollo, Deepgram, Juicebox, Customer.io, LangChain, Lindy, Granola, Gamma, Clerk, Linear
- 240 new skills across Batch 3 vendors (24 skills per pack)
- npm packages for all 30 SaaS packs with download tracking
- Learn pages for all Batch 3 vendors on claudecodeplugins.io

### Changed
- Updated marketplace.extended.json with 10 new pack entries
- Updated vendor-packs.json with Batch 3 vendor metadata
- Updated TRACKER.csv with Batch 3 completion status

### Infrastructure
- All 30 SaaS packs now published to npm (@intentsolutionsio/{vendor}-pack)
- Consistent naming across marketplace and npm registries
- Website deployed with 642 pages including all vendor learn pages

### Metrics
- Total SaaS skill packs: 30 (720 skills)
- Batch 3 packs: 10 (240 skills)
- npm packages published: 30
- Files changed: 305
- Lines added: +72,405

## [4.8.0] - 2026-01-06

### Added
- Marketplace redirects for deleted learning pages
- 14 new vendor skill packs with website pages

### Changed
- Updated learn hub with all vendor icons
- Synced marketplace catalogs

## [4.7.0] - 2026-01-06

### Added
- Progressive Disclosure Architecture (PDA) pattern for all skills
- Intent Solutions 100-point grading system integrated into validator
- 348 reference files for detailed skill content extraction
- `scripts/refactor-skills-pda.py` automation script for skill restructuring

### Changed
- Refactored 98 skills to PDA pattern (SKILL.md files now <150 lines)
- Merged `validate-frontmatter.py` into unified `validate-skills-schema.py` (v3.0)
- Improved average skill score from 88.0/100 (B) to 92.5/100 (A)
- All 957 skills now 100% production ready

### Fixed
- Excel skills quality issues (GitHub Issues #250, #251, #252, #253)
- OpenRouter pack skills grading (8 skills improved from 80 to 95+ points)
- All C/D grade skills elevated to A/B grade
- Kling AI common-errors skill malformed code fences

### Metrics
- Skills validated: 957
- A grade: 897 (93.7%)
- B grade: 60 (6.3%)
- C/D/F grade: 0 (0%)
- Files changed: 2,173
- Lines added: +77,698
- Lines removed: -70,011

## [4.6.0] - 2026-01-05

### Added
- Batch 2 vendor skill databases (217 files)
- Skill databases for 6 published SaaS packs
- Kling AI flagship+ skill pack (30 skills)

### Fixed
- OpenRouter pack skill quality improvements

## [4.5.0] - 2026-01-04

### Added
- External plugin sync infrastructure
- ZCF integration
- 50-vendor SaaS skill packs initiative

### Changed
- Skill quality improvements to 99.9% compliance
