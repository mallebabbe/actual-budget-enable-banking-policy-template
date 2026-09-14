# Actual Budget + Enable Banking Policy Templates

Privacy Policy and Terms of Use templates for private, non-commercial [Actual Budget](https://actualbudget.org/) installations using [Enable Banking](https://enablebanking.com/) for bank synchronization.

## Why this repository exists

Actual Budget supports bank synchronization through Enable Banking.

When creating a Production application in Enable Banking, you may be asked to provide public URLs for documents such as:

- Privacy Policy
- Terms of Use

For people running Actual Budget privately for themselves or their household, creating these documents from scratch can be unnecessarily complicated.

This repository provides simple templates that can be copied and adapted for that purpose.

## Included Templates

- [`privacy-policy.md`](privacy-policy.md) — Privacy Policy template
- [`terms-of-use.md`](terms-of-use.md) — Terms of Use template

## Who is this for?

These templates are primarily intended for people who:

- Self-host or privately host Actual Budget
- Use Actual Budget for personal or household finances
- Want to connect their own bank accounts
- Use Enable Banking for bank synchronization
- Are not offering Actual Budget as a commercial financial service

If you operate a business, provide financial services to other people, or process financial information belonging to customers or unrelated third parties, these templates may not be appropriate for your situation.

## How to use

### 1. Fork or copy this repository

You can fork this repository or copy the individual policy files.

### 2. Review the templates

Read both documents carefully:

- `privacy-policy.md`
- `terms-of-use.md`

Make sure they accurately describe how your Actual Budget installation works.

### 3. Adapt them to your setup

Depending on your situation, you may want to add or change information such as:

- Your name or organization
- Contact information
- Hosting provider
- Country or jurisdiction
- Data retention practices
- Other services connected to Actual Budget
- Additional users who have access to the installation

Do not publish a policy that does not accurately describe your setup.

### 4. Publish the pages

The documents need to be publicly accessible if you want to use their URLs when registering an Enable Banking application.

One simple option is GitHub Pages.

After enabling GitHub Pages for your repository, you can publish your Privacy Policy and Terms of Use as public HTTPS pages.

You can then provide those URLs when configuring your Enable Banking application.

## Typical Setup

A private Actual Budget setup using Enable Banking may look like this:

    Bank account
         |
         v
    Enable Banking
         |
         v
    Actual Budget
         |
         v
    Personal / household budgeting

Enable Banking handles the connection to the financial institution, while Actual Budget stores and manages the imported financial information.

## Important

These documents are templates.

Every Actual Budget installation can be configured differently. Hosting providers, banking integrations, users, jurisdictions, and data-processing practices may differ.

You are responsible for reviewing and adapting the documents before using them.

## AI-Generated Content

The initial content of this repository, including the Privacy Policy, Terms of Use, documentation, and explanatory text, was generated with the assistance of artificial intelligence (AI).

The content has not been prepared or reviewed by a lawyer and should not be considered legal advice.

Users are responsible for reviewing, verifying, and adapting the content to their own circumstances before using or publishing it.

## Legal Disclaimer

These templates are provided for informational and convenience purposes only.

They do not constitute legal advice and no guarantee is made that they satisfy the legal or regulatory requirements applicable to your particular situation.

If you are unsure about your obligations, consult an appropriate legal or privacy professional.

## License

This repository is released under the Creative Commons Zero v1.0 Universal (CC0 1.0) dedication.

You may copy, modify, distribute, and reuse these templates without requesting permission or providing attribution.
