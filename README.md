# Self-Hosted Linux Server Infrastructure

## Overview
This repository documents a personal Linux-based server setup designed to
support secure service deployment, data management, and experimentation with
AI-enabled applications.

## System Overview
- Hardware: Dell OptiPlex 7040 SFF
- OS: Linux
- Network: Reverse proxy + VPN-based remote access

## Core Components
- NGINX reverse proxy with HTTPS (Let’s Encrypt)
- Docker-based service deployment
- Secure remote access using VPN
- Centralized storage and file sharing

## Deployed Services
- Media streaming service (Jellyfin)
- Photo management system (Immich)
- Planned personal cloud services (Nextcloud)
- Internal tooling and experimental services

## Key Engineering Challenges
- Hardware-accelerated transcoding (Intel Quick Sync)
- Permission and device access management on Linux
- Secure public vs private service exposure
- Reliability and maintainability on limited hardware

## Relevance to AI Systems
This infrastructure enables practical experimentation with deploying,
monitoring, and maintaining AI-driven applications in a real-world environment,
bridging the gap between model development and production systems.

## Key Takeaways
- Strong understanding of Linux systems and networking
- Experience deploying long-running services
- Emphasis on security, stability, and maintainability
