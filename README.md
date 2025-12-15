# Campaign Tracker Platform

Reliable campaign tracking infrastructure for data-driven marketing platforms.

## Overview

Campaign Tracker Platform is a scalable and modular system designed to support marketing and advertising platforms.  
It provides a reliable foundation for managing campaigns, processing click and conversion events, and exposing performance metrics through secure REST APIs.

The platform is built with a strong focus on clean architecture, maintainability, and long-term scalability, enabling seamless integrations and continuous evolution of business rules.

---

## Goals

- Centralize campaign management
- Register and process marketing events (clicks and conversions)
- Expose performance data through APIs
- Enable integrations with external systems
- Provide a scalable foundation for analytics and optimization workflows

---

## Architecture

The application follows a modular, responsibility-driven architecture, allowing independent evolution of services and infrastructure.

```text
campaign-tracker-platform/
├── backend-java/        # Core API and business logic
├── backend-python/      # Data processing and automation
├── frontend-angular/    # Web interface
├── docker/              # Containerization and orchestration
└── README.md
```

## License

This repository's source code is available under the MIT License.
