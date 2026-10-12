# Burp Repeater Tab Namer

Burp Suite extension that replaces numeric Repeater tab names with readable names such as `GET /users` or `query GetUser`.

## Features

- REST names use the HTTP method and cleaned path.
- GraphQL names use the operation name when available.
- Long names are limited to 80 characters.
- Duplicate names are resolved case-insensitively.
- Optional JSON-response-only mode.
- Includes a modern Montoya build and a legacy API build.

## Installation

Load the appropriate JAR from `dist/` in Burp Suite under **Extensions**.

- `burp-repeater-tab-namer-1.1.0.jar`: Burp versions using the Montoya API.
- `burp-repeater-tab-namer-legacy-1.1.0.jar`: older Burp versions using the legacy API.

The extension changes tab labels only; it does not send data to an external service.
