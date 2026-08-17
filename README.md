# daric-doc
This repository centralizes documentation for DARIC chip development, including chip information, EVB usage, RISC-V development workflows, and download tool guides, enabling efficient collaboration across R&D, testing, and support teams.

---

## Overview

This repository is organized around the full DARIC development lifecycle, including:

- **DARIC chip documentation**    
  Chip introduction, architecture, features, and interface references.

- **EVB documentation**  
  Board setup, power-on, debugging, and validation guides.

- **RISC-V development guides**    
  Environment setup, toolchain configuration, build/debug workflows.

- **Download tool manuals**   
  Firmware/image download tool installation, configuration, and troubleshooting.

---

## Directory Structure & Descriptions

### `01 Daric/`
 Core DARIC chip documentation, including chip basics, architecture, key capabilities, interfaces, and usage notes.

### `02 EVB/`
 EVB (Evaluation Board) documentation, covering hardware connections, boot procedures, peripheral validation, and bring-up troubleshooting.

### `03 RISCV Development/`  
 RISC-V development documentation, including environment setup, toolchain usage, build/flash flow, and debugging examples.

### `04 Download Tool/`
 Download tool documentation, including installation/configuration, flashing steps, and common download failure handling.

---

## Recommended Reading Order
1. `01 Daric` (understand chip capabilities and constraints first)
2. `02 EVB` (get familiar with the hardware platform)
3. `03 RISCV Development` (start software development)
4. `04 Download Tool` (complete flashing and bring-up loop)

---
## Hardware Resources
For Daric hardware-related resources, please refer to the hardware repository:

https://github.com/crossbar-inc/daric-hardware

## SDK Resources
For Daric ARM SDK-related resources, please refer to the SDK repository:

https://github.com/crossbar-inc/daric-sdk

---

## Intended Audience
- Embedded/system software engineers
- Hardware and bring-up engineers
- Test and validation engineers
- Technical support and FAE teams

---

## Maintenance Guidelines
- Recommended naming format: `topic-version-date.md`
- When updating docs, indicate applicable versions and change context
- For new procedures, include prerequisites, steps, expected results, and FAQs
