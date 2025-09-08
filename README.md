# Apple Device Services

[![CI/CD](https://github.com/micromdm/apple-device-services/actions/workflows/on-push-pr.yml/badge.svg)](https://github.com/micromdm/apple-device-services/actions/workflows/on-push-pr.yml)

API schema definitions for Apple's various device management web services.

While Apple does provide documentation in the form of HTML (i.e. for humans to read), machine-readable API schema definitions are much preferred. Not lease of which is for code validation. For example we love the documentation Apple provides in the Apple [Device Management](https://github.com/apple/device-management) repository. We hope one day they will choose to manage and provide machine-readable schemas for their web service APIs, too. These schemas were hand-crafted from the HTML documentation.

## Schemas

A general list of schemas managed here:

- [ABM Schemas](abm/schemas)  
[JSON Schema](https://json-schema.org) definitions for the [Apple Business Manager API](https://developer.apple.com/documentation/applebusinessmanagerapi)

## Contributing

These schemas are almost guaranteed to be incomplete due to the fact they are used as-needed and manually generated from Apple's documentation. So: **your help needed!**. Take a look at a given schema and if something you need isn't there: PRs welcome!

Note that we use the [jsonschema](https://github.com/sourcemeta/jsonschema) tool to enforce JSON Schema formatting and linting.