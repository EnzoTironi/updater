# InSight Updates

This repository contains update manifests and release information for the InSight AI Assistant application.

## Structure

- `latest.json` - Latest version information and download URLs
- `versions/` - Historical version manifests
- `signatures/` - Digital signatures for verification

## Update Endpoint

The primary update endpoint is available at: `https://updates.zoen.space/latest.json`

## Security

All update manifests are signed using Ed25519 cryptographic signatures to ensure authenticity and integrity.

## Repository Setup

This repository is configured with GitHub Pages to serve update manifests via HTTPS at `updates.zoen.space`.