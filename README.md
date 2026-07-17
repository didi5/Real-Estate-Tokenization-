# TokenImmo — Web3 Real Estate Investment Prototype

A responsive multi-page frontend prototype exploring how real estate owners and investors could interact with a Web3-based property investment platform.

The concept focuses on making real estate investment more accessible through Security Token Offerings (STOs), a simplified owner journey, an investor community, and an interactive payout calculator.

> **Project status:** Academic frontend prototype. The repository does not currently include a production backend, authentication, blockchain integration, token issuance, payment processing, or validated financial calculations.

## Project Overview

TokenImmo explores a digital platform with two primary user groups:

* **Property owners**, who want to unlock liquidity without directly selling their assets.
* **Investors**, who want easier access to tokenized real estate opportunities and community benefits.

The prototype translates this concept into a visual user journey across a landing page, owner calculator, onboarding explanation, community page, and contact page.

## Key Features

* Multi-page website with consistent navigation
* Separate entry points for property owners and investors
* Owner-focused STO calculator prototype
* Explanatory two-step onboarding journey
* Community concept with loyalty points and exclusive rights
* Responsive navigation and mobile layout
* Custom visual design using HTML and CSS
* Lightweight implementation without frameworks

## User Journeys

### Property Owners

1. Enter the estimated market value and debt associated with a property.
2. Review a preliminary STO payout calculation.
3. Continue toward the proposed community and dashboard experience.

### Investors

1. Register through a simplified access point.
2. Discover tokenized real estate opportunities.
3. Join the community and explore potential rewards.

## Technology Stack

* **HTML5** — page structure and content
* **CSS3** — custom styling, layouts, and responsive behavior
* **Vanilla JavaScript** — calculator prototype and navigation interactions
* **Google Fonts** — typography
* **Font Awesome** — interface icons

## Project Structure

```text
.
├── images/              # Logos and visual assets
├── index.html           # Main landing page
├── seller.html          # Property-owner journey and STO calculator
├── community.html       # Investor community concept
├── howto.html           # Owner and buyer onboarding steps
├── contact.html         # Contact page
├── sto-calculator.js    # Preliminary calculator logic
├── style.css            # Shared styles and responsive layout
└── README.md            # Project documentation
```

## Run Locally

No package installation or build process is required.

1. Clone the repository:

```bash
git clone https://github.com/didi5/Dilem-Kaya---BA.git
```

2. Open the project folder:

```bash
cd Dilem-Kaya---BA
```

3. Open `index.html` directly in your browser.

For a local development server, you can also use the VS Code **Live Server** extension.

## Current Limitations

This repository represents an early-stage concept and interface prototype.

* The STO calculator is not financially or legally validated.
* The calculator logic requires further implementation and testing.
* The selected payout rate and STO duration are not yet fully integrated into the calculation.
* No user accounts or authentication are available.
* No database or backend API is connected.
* No smart contracts, blockchain network, wallet, or token infrastructure are implemented.
* Community actions and contact functions are currently visual placeholders.
* The project is not intended to provide financial, investment, or legal advice.

## Potential Next Steps

* Refactor and validate the STO calculation model
* Add input validation and automated tests
* Implement investor and property-owner dashboards
* Introduce secure authentication and role management
* Connect the interface to a backend and database
* Evaluate compliant tokenization and smart-contract architecture
* Add property listings and investment portfolios
* Improve accessibility and semantic HTML
* Deploy the prototype through GitHub Pages or Vercel
* Conduct usability testing with owners and investors

## What This Project Demonstrates

* Translating a business concept into a digital product prototype
* Designing separate journeys for different stakeholder groups
* Building a responsive website without a frontend framework
* Implementing basic interactive logic with JavaScript
* Structuring a multi-page web project
* Exploring the intersection of real estate, financial technology, and Web3

## Author

**Dilem Kaya**

* Website: [dilemkaya.com](https://www.dilemkaya.com)
* LinkedIn: [Dilem Kaya](https://www.linkedin.com/in/dilemkaya/)

## Disclaimer

This project is an educational prototype. Its calculations, assumptions, and interface elements must not be used as the basis for real financial, investment, legal, or real-estate decisions.
