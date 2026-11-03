# LAB17 - HTTP Rate Limiting & Abuse Detection

Labtainers exercise demonstrating HTTP rate limiting.

## Topology
- ext-client: 172.31.67.50
- rate-server: 172.31.67.40:8080

## Objectives
- HTTP 200 for normal requests
- HTTP 429 after exceeding 5 requests in 10 seconds
- Retry-After header verification
- Recovery after rate-limit window
- Server-side abuse evidence

## Installation
Download imodule.tar from GitHub Releases.
Docker Hub namespace: trongbua
