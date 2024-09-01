# Spectral API Linter Demo

This repository serves as a demonstration of how to use a spectral API linter with an external configuration source.

## Overview

The spectral API linter is a powerful tool for validating and linting API specifications. By using an external configuration source, you can customize the linter's rules and settings to suit your specific requirements.

## Usage

To use the spectral API linter with an external configuration source, follow these steps:

1. Clone this repository to your local machine.
2. Install the spectral API linter (if not already installed).
3. Configure the linter to use the external configuration file provided in this repository.
4. Run the linter against your API specifications to ensure they adhere to the defined rules.

```bash
npx spectral lint src/unique-tech-events.v1.yaml
```

## External Configuration

The external configuration file included in this repository contains the custom rules and settings for the spectral API linter. You can modify this configuration file to adjust the linter's behavior according to your project's needs.

## Resources

- [Spectral API Linter Documentation](https://stoplight.io/p/docs/gh/stoplightio/spectral)
- [Spectral API Linter GitHub Repository](https://github.com/stoplightio/spectral)
