# Magic PNG

A Windows desktop utility that creates specially structured PNG output through a C# WPF interface.

The repository contains both the maintained source project and the history of the earlier binary-oriented `magicpngexe` repository. Keeping the histories together makes the application easier to study, build, and release from one canonical location.

## What this project includes

- Native Windows desktop interface
- PNG processing and export workflow
- Visual Studio solution and project files
- Preserved legacy executable-history merge
- MIT-licensed source

## Technology

- C#
- .NET
- Windows Presentation Foundation (WPF)
- Visual Studio

## Repository structure

- `sihir/MagicPng.sln` — Visual Studio solution.
- `sihir/MagicPng/` — WPF source and project.
- `LICENSE` — MIT license.

## Getting started

Build on Windows with Visual Studio and the required .NET/WPF workload. Open `sihir/MagicPng.sln`, restore dependencies, select Debug or Release, and build.

## Configuration and data

- Select a Windows-compatible .NET toolchain matching the project file.
- Use Release configuration for distributable builds and publish binaries through GitHub Releases rather than committing build output.

## Development and validation

- Keep changes focused on the relevant module or subproject and verify the user-facing path manually before publishing.
- Do not commit generated build output, local environments, caches, logs, or credentials unless an artifact is intentionally retained as source material.

## Security and responsible use

- Open untrusted images cautiously and validate file paths before extending processing.
- Generated `bin/` and `obj/` directories should remain outside source control.

## Project status

A small legacy Windows utility preserved as buildable source. Modern .NET or WPF migration may require project-file updates.

## License

See the license file in this repository for the terms that apply to the source code.
