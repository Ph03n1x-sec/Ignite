# Contributing to Ignite

Thanks for your interest in contributing! Ignite is a personal workstation setup script, so contributions are welcome but should be discussed first.

## Reporting Bugs

1. Run `./Ignite --check` and include the output.
2. Open an issue with:
   - Kali version (`cat /etc/os-release`)
   - Architecture (`dpkg --print-architecture`)
   - Ignite version (shown in the banner)
   - Steps to reproduce
   - Expected vs actual behaviour

## Suggesting Features

Open an issue describing what you'd like and why it would be useful. Since this project targets a specific setup (Apple Silicon + VMware Fusion + Kali), not every feature will fit.

## Pull Requests

- Open an issue first to discuss the change before writing code.
- Keep changes focused — one fix or feature per PR.
- Test on Kali arm64 if possible.
- Make sure `bash -n Ignite` passes (no syntax errors).

## Security

If you find a security issue, please open an issue or contact the maintainer directly rather than posting exploit details publicly.

## License

By contributing you agree that your contributions will be licensed under the GPL-3.0 license.
