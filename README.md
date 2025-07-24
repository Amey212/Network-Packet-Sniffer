# Network Packet Sniffer

A Python-based network packet sniffer for computer networking projects. Captures and analyzes network traffic in real-time with protocol-specific decoding.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Project Structure](#project-structure)
- [License](#license)

## Features
- 🕵️‍♂️ Real-time packet capturing
- 📊 Supports multiple protocols:
  - HTTP/HTTPS (URLs, headers)
  - TCP/UDP (ports, payloads)
  - ICMP (ping requests)
  - DNS (queries/responses)
- 🔍 BPF filter support
- 📈 Packet statistics (count, size)
- ⌨️ Simple CLI interface

## Prerequisites
- Python 3.6+
- scapy library
- Root/Administrator privileges

```bash
# Verify Python installation
python3 --version

# Install scapy
pip install scapy
