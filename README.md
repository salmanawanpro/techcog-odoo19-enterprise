# TechCog Odoo 19 Enterprise

This repository contains a customized Odoo 19 Enterprise environment developed for TechCog's ERP requirements.

The project is organized to keep custom business logic separate from the Odoo core, making maintenance, upgrades, and future development more manageable.

It includes custom modules, workflow customizations, localization requirements, deployment configurations, and other enhancements tailored to business needs.

## What's Included

- Odoo 19 Enterprise environment
- Custom addons workspace
- Business-specific customizations
- Deployment and configuration setup
- Development environment resources
- Module packaging structure

## Project Structure

```text
custom_addons/   Custom business modules
odoo/            Odoo framework source
setup/           Environment configuration
debian/          Packaging and deployment files
```

## Technology Stack

- Odoo 19 Enterprise
- Python
- PostgreSQL
- JavaScript
- XML
- CSS

## Development Approach

The primary focus of this project is maintainable and upgrade-friendly development.

Rather than modifying Odoo core files directly, custom requirements are implemented through dedicated modules whenever possible. This approach helps simplify future upgrades, improves maintainability, and keeps the codebase organized.

## About

Developed by Salman Awan

**Odoo Developer | ERP Consultant**

Areas of expertise:

- Odoo Customization
- ERP Implementation
- Business Process Automation
- API Integrations
- Custom Module Development