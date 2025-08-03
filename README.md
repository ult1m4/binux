# Binux Linux
Binux is a security focused distro project attempting to turn Crux or Gentoo style source-heavy Linux bases into something clean, declarative, fast, and manageable, with a clear core set of user-friendly binaries.

BPKG package manager will allow deep and robust customization, dependency resolution, containerization and auto-cleaning build environments, keeping your system simple and reducing post-build tooling and dependency leftovers. Inspired by Nix and Guix but more FHS compatible. It will provide a minimal set of x64 binaries for common/necessary packages to save the user time (i.e., kernel, browsers)

Binux looks toward using its own init, dinit, sinit, OpenRC, or Shephed. Binux would like to provide flexibility in all choices including init, but will have an officially supported init for polish and documentation.

Binux intends to support Musl primarily, with extensive containerization and documentation as needed for Glibc compatability.

Binux will employ LibreSSL and kernel haedening by default, with Ryzen optimized builds.

Binux will be primarily built with T2 SDE and custom tooling.
