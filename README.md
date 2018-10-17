# nix-bundle-macos

Inspired by [`nix-bundle`](https://github.com/matthewbauer/nix-bundle), this is an early attempt at creating self-contained bundles for Nix packages for macOS.

First, [install Nix](https://nixos.org/nix/download.html) on your Mac. Then install the Nix package you'd like to bundle. Then you can bundle that package as either a self-contained `.app` or `bin` executable.

# Create a self-contained `.app`

```
nix-bundle-macos PathVisio
```

# Create a self-contained `bin` executable

```
nix-bundle-macos ripgrep-0.9.0
```
