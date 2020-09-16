# nrf52-project-template

Template to start a new nrf52 project with the AWS IoT SDK.

This template uses submodules! You'll need a recursive clone.

## Folders

- `/build `: Intended for build output
- `/secrets`: To store passwords and certificates (git will ignore it)

## Compiler config

### Env vars

You need to set this env vars:

- `GNU_GCC_ARM`
- `GNU_GCC_ARM_LIBS`
- `nRF_SDK`

I'm using the .vscode/settings.json file for that. If you want to set it in a different way you need to delete them from there.
