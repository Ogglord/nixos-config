### NixOS config 2025

## Overview

This repository contains my NixOS configuration, which is managed using Nix flakes.

## Directory Structure

      .
      ├── home-manager/          # Home-manager configurations
      │   └── home.nix           # Default home-manager configuration      
      ├── modules/               # NixOS and home-manager modules      
      ├── nixos/                 # Host-specific configurations
      │   └── configuration.nix  # Default host configuration
      ├── secrets/               # Encrypted secrets
      └── flake.nix              # Main system configuration

