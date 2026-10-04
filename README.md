R-Team OC (currently in beta) - Click Releases to the right ------->

Portable Radeon tuning, live telemetry, and a personalized desktop experience.

R-Team OC uses AMD’s ADLX interface to request GPU settings and check fresh driver readback. It runs without administrator privileges, an installer, or automatic internet access.

Features

GPU clock, VRAM, power-limit, and fan controls where supported.

Apply results that distinguish verified settings from unconfirmed requests.

Restore Driver Defaults.

Ten profile slots for saving and loading settings.

Live telemetry, graphs, and thermal monitoring.

Nano-OC and Nano-Thermo windows that can stay open together.

Driver features and automatic tuning options where exposed by AMD.

Appearance customization and screenshot capture.

Support exports with diagnostics and optional user feedback.

Requirements

Windows x64.

A compatible AMD Radeon GPU and installed AMD graphics driver.

Feature availability depends on the GPU, driver, and driver installation.

Primary tested hardware: Radeon RX 9070 GRE. Compatibility with every AMD card has not been established. Legacy Radeon HD cards are outside the current target.

Some features, including AFMF and Radeon Super Resolution, may require the full AMD Software installation.

Getting Started

Download the published portable release.

Extract it if supplied as a ZIP.

Run RTeamOC.exe.

Review the first-run information before tuning.

The portable EXE includes the required .NET runtime and ADLX bridge. Preferences, profiles, and extracted components are stored in your Windows user account.

Experimental Power Requests

An optional experimental range allows power-limit requests above the driver-reported maximum.

A higher slider position is a request—not proof that additional power was applied. The driver may reject, clamp, or ignore it. R-Team OC reports whether fresh readback matches the requested value.

This feature does not modify AMD’s driver or guarantee additional performance.

Support and Feedback

Use Support Export in the app to create a diagnostic ZIP. Include a short description of the issue, what you expected, and how to reproduce it.

Exports are saved locally. Nothing is uploaded automatically. Review the contents before sharing, and share diagnostic bundles privately where possible.

Release Integrity

Public builds use Azure code signing. R-Team OC checks its bundled bridge against an embedded SHA-256 hash before running driver commands.

Tuning Responsibility

Choose settings carefully and monitor temperature and stability. Driver acceptance or matching readback does not establish that an overclock is stable.

License

R-Team OC is proprietary software. See the included EULA and third-party notices for applicable terms.

R-Team OC is an independent project and is not affiliated with or endorsed by AMD.
