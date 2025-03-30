# Vibe Rules Collection by copyleftdev

<p align="center">
  <img src="assets/logo.png" alt="Vibe Rules Collection Logo" width="200"/>
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.1-ff69b4.svg)](CODE_OF_CONDUCT.md)

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](language/pythonic.windsurfrules)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)](language/cpp_modern_best_practices.windsurfrules)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](language/typescript_modular.windsurfrules) <!-- Assuming TS rules cover JS well -->
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](language/typescript_modular.windsurfrules)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)](language/golang_best_practices.windsurfrules)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)](language/rust_clean_architecture.windsurfrules)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)](language/php_modern_best_practices.windsurfrules)
[![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)](language/ruby_idiomatic_best_practices.windsurfrules)
[![SQL](https://img.shields.io/badge/SQL-Various-blue?style=flat&logo=postgresql&logoColor=white)](database/generic_sql_best_practices.windsurfrules)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](devops/dockerfile_best_practices.windsurfrules)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)](devops/kubernetes_manifests.windsurfrules)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)](devops/terraform_best_practices.windsurfrules)

A curated collection of `.windsurfrules` files designed to guide AI coding assistants (like Codeium's Cascade) in generating code that adheres to various best practices, architectural patterns, language idioms, and framework conventions.

The goal is to provide a centralized repository of "vibes" or guidelines that can be easily referenced or incorporated into AI-assisted development workflows, ensuring generated code aligns with specific project standards or desired styles.

## Table of Contents

- [Purpose](#purpose)
- [Usage](#usage)
- [Rule Categories](#rule-categories)
  - [API Design](#api-design)
  - [Architecture](#architecture)
  - [Database](#database)
  - [Design Systems](#design-systems)
  - [DevOps](#devops)
  - [Frameworks](#frameworks)
  - [Language Specific](#language-specific)
  - [Paradigms](#paradigms)
  - [Performance](#performance)
  - [Quality](#quality)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)
- [License](#license)

## Purpose

Modern AI coding assistants can significantly accelerate development, but guiding them to produce code that matches specific project requirements, team conventions, or nuanced best practices can be challenging. This collection aims to bridge that gap by providing explicit rule sets (`.windsurfrules`) that define these expectations.

These rules are designed primarily for **Windsurf**, the agentic IDE by [Codeium](https://codeium.com/), to guide its AI assistant, **Cascade**. By defining a "vibe" or set of instructions within a `.windsurfrules` file, developers can influence how Cascade generates and suggests code.

By using these rules, developers can:
- Improve the consistency and quality of AI-generated code within Windsurf.
- Enforce specific architectural patterns or design choices.
- Ensure adherence to language idioms and framework conventions.
- Reduce the time spent refactoring or correcting AI suggestions.
- Codify team standards for AI collaboration.

## Usage

These `.windsurfrules` files are intended for use with AI coding tools that support such configuration (e.g., Codeium in specific IDEs). The exact mechanism for applying these rules may vary depending on the tool.

Generally, you might reference a specific rule file when interacting with the AI, or configure the tool to use certain rules by default for a project.

## Rule Categories

The collection is organized into the following categories:

### API Design
- `graphql_api_design.windsurfrules`
- `rest_api_design.windsurfrules`

### Architecture
- `actor_model_architecture.windsurfrules`
- `clean_architecture.windsurfrules`
- `hexagonal_architecture.windsurfrules`
- `layered_architecture.windsurfrules`
- `microservices_architecture.windsurfrules`
- `mvc_architecture.windsurfrules`
- `pipe_filter_architecture.windsurfrules`
- `serverless_architecture.windsurfrules`
- `soa_architecture.windsurfrules`
- `space_based_architecture.windsurfrules`

### Database
- `generic_sql_best_practices.windsurfrules`
- `mysql_best_practices.windsurfrules`
- `oracle_plsql_best_practices.windsurfrules`
- `postgresql_best_practices.windsurfrules`
- `sqlite_best_practices.windsurfrules`
- `sqlserver_tsql_best_practices.windsurfrules`

### Design Systems
- `ant_design.windsurfrules`
- `apple_hig_principles.windsurfrules`
- `atlassian_design_system.windsurfrules`
- `fluent_ui.windsurfrules`
- `material_design.windsurfrules`

### DevOps
- `git_best_practices.windsurfrules`
- `github_flow_workflow.windsurfrules`
- `gitflow_workflow.windsurfrules`
- `macos_sysadmin_scripting.windsurfrules`
- `powershell_scripting_best_practices.windsurfrules`
- `shell_scripting_best_practices.windsurfrules`
- `terraform_best_practices.windsurfrules`
- `trunk_based_development.windsurfrules`

### Frameworks
- `aspnet_core_mvc_api.windsurfrules`
- `express_js_middleware.windsurfrules`
- `flask_minimalist_python.windsurfrules`
- `ruby_on_rails_convention.windsurfrules`
- `svelte_reactive_ui.windsurfrules`
- `unity_csharp_scripting.windsurfrules`

### Language Specific
- `cpp_game_development.windsurfrules`
- `cpp_google_style.windsurfrules`
- `cpp_high_integrity.windsurfrules`
- `cpp_modern_best_practices.windsurfrules`
- `golang_best_practices.windsurfrules`
- `php_modern_best_practices.windsurfrules`
- `pythonic.windsurfrules`
- `ruby_idiomatic_best_practices.windsurfrules`
- `rust_clean_architecture.windsurfrules`
- `typescript_modular.windsurfrules`

### Paradigms
- `data_oriented_design.windsurfrules`
- `event_driven_design.windsurfrules`
- `functional_programming.windsurfrules`
- `object_oriented_design.windsurfrules`

### Performance
- `performance_tuning_principles.windsurfrules`
- `sql_performance_tuning.windsurfrules`

### Quality
- `code_linting_principles.windsurfrules`

## Contributing

Contributions are welcome! If you have ideas for new rules, improvements to existing ones, or suggestions for better organization, please feel free to open an issue or submit a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## Code of Conduct

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2025 copyleftdev
