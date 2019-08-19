# Changelog
All notable changes to this project will be documented in this file.

# v3.1.1

### Fixed

- An issue when reading `config_help.json` for Windows users due to an encoding problem.

# v3.1.0

### Breaking

- `disable_recipient_thread_close` is removed, a new configuration variable `recipient_thread_close` replaces it which defaults to False.
- Truthy and falsy values for binary configuration variables are now interpreted respectfully.
- `LOG_URL_PREFIX` cannot be set to "NONE" to specify no additional path in the future, "/" is the new method.