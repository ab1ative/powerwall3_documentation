# Powerwall 3 Owner's Manual — DITA Source

This repository contains a DITA XML conversion of Tesla's publicly available 
[Powerwall 3 Owner's Manual](https://service.tesla.com/docs/Public/Energy/Powerwall/Powerwall-3-Owners-Manual-NA-EN/index.html).

It is a portfolio project demonstrating structured authoring in DITA 1.3, 
including topic-based architecture, topic type classification, cross-references, 
and ditamap assembly. All content is sourced from Tesla's public documentation.

## Tools Used

- **Oxygen XML Editor** — authoring and validation
- **DITA Open Toolkit (DITA-OT)** — publishing to HTML5
- **Git/GitHub** — version control

## Repository Structure

├── powerwall3.ditamap

├── concepts/

│ ├── safety.dita — Important Safety Instructions

│ ├── warranty.dita — Powerwall 3 Warranty

│ ├── care.dita — Care and Maintenance

│ ├── design.dita — System Design

│ └── operation.dita — System Operation

├── reference/

│ ├── components.dita — System Components

│ ├── overview.dita — Powerwall 3 Overview (annotated diagram)

│ ├── led_reference.dita — LED Indicator States

│ └── info.dita — System Information

└── tasks/

├── monitoring.dita — Monitoring Your System

├── turn_off.dita — Turning the System Off

├── backup.dita — Backup Troubleshooting

├── support.dita — Technical Support

└── emergency.dita — What to Do in Case of an Emergency

## Topic Types

This project demonstrates all three core DITA topic types:

- **Concept** — background information and system overviews
- **Task** — step-by-step procedures for operators and technicians
- **Reference** — lookup tables, component diagrams, and LED state references

## Source

Original documentation © 2024 Tesla, Inc. Converted to DITA for portfolio 
demonstration purposes only. Not affiliated with or endorsed by Tesla.
