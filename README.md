# SprintBoard

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

SprintBoard is a multi-tenant Django SaaS application inspired by Jira, designed for agile teams to manage projects, tasks, and blogs. Built with Django and leveraging PostgreSQL schemas for tenant isolation, it provides secure, scalable workspaces for organizations with collaborative boards and streamlined planning workflows.

## Features

- **Multi-Tenancy**: Isolated workspaces for each tenant using PostgreSQL schemas.
- **Project Management**: Create and manage projects with task assignments and tracking.
- **Collaborative Boards**: Visualize workflows with intuitive, team-friendly boards.
- **User Management**: Tenant-specific user roles and permissions.
- **Public Blog**: Shared blog for cross-tenant marketing content.
- **RESTful API**: Built with Django REST Framework for seamless integrations.
- **Scalable Architecture**: Semi-isolated approach for performance and data privacy.

## Prerequisites

- Python 3.8+
- PostgreSQL 13+
- pip and virtualenv
- Git

## Acknowledgements

- Built following the TestDriven.io Django Multi-Tenant Tutorial.
- Powered by `django-tenants` and `django-tenant-users`.
