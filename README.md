<div align="center">
<h3>$\textcolor{red}{\textsf{ MALWARE AHEAD! IF YOU  DO NOT  KNOW WHAT THAT IS - LEAVE}}$ </h3>
This repository is dedicated to the theoretical research and analysis of the NLS Rootkit, also known as NLS_933W.DLL. For safety reasons, the actual malware samples are not included here. They can be found in my other repository focused on NLS_933_DLL. Additionally, for related research, you might want to check my Stuxnet repository.
  
Yours sincerely,

*Will*

</div>

---

<sub>Please see the `THANKS_TO.md` file for people I consider helpful in building this repo!</sub>

## Table of Contents

- [Introduction](#introduction)
  - [Purpose](#purpose)
  - [Important Warnings](#important-warnings)
  - [Why This Repository?](#why-this-repository)
- [Malware Samples](#malware-samples)
- [Related Malware](#related-malware)
- [Overview](#overview)
  - [Related Articles](#related-articles)
- [Tree Overview](#tree-overview)
- [Acknowledgments](#acknowledgments)

---

## Introduction

NLS_933W.DLL is a malware that targets storage device firmware, specifically HDD/SSD firmware, making it a boot/rootkit. **In a nutshell, that's NLS_933W.DLL**.

### Purpose

This repository is a collection of NLS_933W.DLL-related files gathered from various sources to make it more accessible for researchers and antivirus developers. The repository includes:
- **Binary/Raw files**
- **Memory and Hardware Dumps (`JTAG`/`UART`)**
- **Sample Firmwares (before and after with diff)**

### Important Warnings

⚠️ This repository is for research and educational purposes only! Even if you run these in a Virtual Machine, USE CAUTION.⚠️ Samples and reports are sourced from various contributors to provide a comprehensive collection.

### Why This Repository?

NLS_933W.DLL is nearly impossible to find on the internet. I discovered it on one of my hard drives as part of a sample collection. This repository aims to consolidate information and resources related to this elusive malware.

---

## Malware Samples

For the actual malware, please visit the [**only_malware**] branch in the other NLS933W.DLL repository.

- If you see `need PK compat. v5.1 (can do v4.6)`, you need to install `engrampa` on Linux. I use Qubes for malware and Engrampa to pack infected archives.

---

## Related Malware

- **EQUATIONGROUP**
  - STUXNET
  - FANNY.BMP
  - BRUTALKANGAROO
  - GAUSS
  - FLAMER

---

##  Overview

NLS_933W.DLL (referred to as NLS) is a rootkit (or bootkit) residing in the firmware of storage devices. This grants it extreme persistence, and its mechanisms will be covered in this repository.

### Related Articles
- [ ] TODO

---

## Tree Overview
- [ ] TODO

<details>
<summary>🌻 Click to Expand Tree</summary>
`todo`
### Files in `<TODO.zip>`

</details>

---

## Acknowledgments
- [ ] TODO

<div align="center" style="color: #ff6341;">

<br>
Yours sincerely,<br>
Will
</div>

---

```
// Notes
If you see a lot of `$\textcolor{red}{\...`, you need to enable JavaScript. It's just red text.
```
