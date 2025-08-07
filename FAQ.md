# Frequently Asked Questions (FAQs)

Welcome to Vendano’s open-source FAQ. This document explains our philosophy, approach, and how you can participate in building a better Cardano wallet for everyone.

## What is Vendano?

Vendano is a Cardano-based mobile wallet designed to be beginner-friendly, private by default, and open to community contributions. Our goal is to reduce the friction barrier to using ADA and to provide a hands-on way for people to learn how crypto works in a safe, low-risk context.

## Why adopt an open-source approach?

Open source accelerates learning, trust, and adoption. By sharing designs, flows, and code, we invite testers, educators, developers, and potential users to shape the product. This collaboration helps us build a wallet that reflects real user needs rather than a narrow internal perspective.

## Who should contribute?

- Crypto beginners who want a practical example of self-custody and transfers
- UX designers and researchers focused on onboarding and accessibility
- Cardano developers and security researchers who want to review seed handling and privacy-preserving features
- Educators and advocates who want to demonstrate safe, private crypto usage

## How can I contribute?

- Review and discuss design decisions in issues
- Propose UI/UX improvements and accessibility tweaks
- Submit code changes for iOS and Android where you have expertise
- Help with documentation, tutorials, or community testing
- Participate in security reviews and responsible disclosure

## How does the contact-based sending flow work?

Vendano uses a privacy-preserving approach to map a phone number or email to a recipient address. The identifiers are hashed to avoid exposing personal data, and lookups only succeed if the recipient also uses the app. This design keeps personal data private while enabling convenient, real-world transfers.

## How do you handle privacy and security?

- Seed words are shown at onboarding to emphasize self-custody
- Minimal data collection and off-chain handling where possible
- Hashed-contact identifiers prevent publicly searchable directories
- We publish security and privacy guidelines and welcome external reviews

## How is onboarding designed for beginners?

- Clear, plain-language explanations of terms and fees
- Immediate seed words display to establish self-custody
- Straightforward funding paths and guided first transfers
- Gentle progression from install to first outbound transaction

## What is the plan for platform parity and parity milestones?

We start with a polished iOS experience, followed by a native Android implementation that mirrors the workflows and data collection. Ongoing parity checks ensure features and analytics stay aligned across platforms.

## How can a user get started today?

- Install Vendano from the appropriate app store when available
- Follow the onboarding flow to create/import a wallet
- Use the Send flow to transfer ADA to a phone number or email contact

## How do I report issues or request features?

- Open an issue in the repository with a clear title and description
- Include steps to reproduce, expected vs. actual results, and any relevant logs or screenshots (as safe)
- If you discover a security vulnerability, use the Security policy and email support@vendano.net

## Where can I find documentation or governance details?

- The main project repository contains the philosophy, onboarding flows, and design decisions
- Security and privacy guidelines are in SECURITY.md
- Community updates and governance discussions are published periodically in the project notes and discussions channels
- Links to user-facing pages (website, support, privacy, terms) live at:
  - Website: https://vendano.net
  - Support: https://vendano.net/support.html
  - Privacy: https://vendano.net/privacy.html
  - Terms: https://vendano.net/terms.html
