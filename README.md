
<div align="center">
<h3>$\textcolor{red}{\textsf{ MALWARE AHEAD! IF YOU  DO NOT  KNOW WHAT THAT IS - LEAVE}}$ </h3>
This repository is dedicated to the theoretical research and analysis of the NLS Rootkit, also known as NLS_933W.DLL. <b>For safety reasons, the actual malware samples are not included here.</b> They can be found in my other repository focused on NLS_933_DLL. Additionally, for related research, you might want to check my Stuxnet repository.
  
Yours sincerely,

*Will*

</div>

---

# ⚠️
## Disclaimer

This repository contains information and resources related to malware analysis, specifically the NLS_933W.DLL rootkit. The content provided here is intended solely for educational and research purposes. By accessing or using any part of this repository, you agree to the following terms:

1. **Educational Use Only**: The materials in this repository are provided for the purpose of studying and understanding malware behavior and should not be used for any malicious or unauthorized activities.

2. **No Responsibility**: The author(s) of this repository do not accept any responsibility or liability for any harm, loss, or damage caused by the use or misuse of the information, code, or tools provided here. This includes, but is not limited to, any direct, indirect, incidental, or consequential damages arising out of or in connection with the use or performance of this repository.

3. **Use at Your Own Risk**: Any use of the information or resources in this repository is done at your own risk. It is your responsibility to ensure that you have adequate knowledge, tools, and precautions in place when working with malware.

4. **Compliance with Laws**: It is your responsibility to ensure that your use of the information and resources in this repository complies with all applicable laws, regulations, and policies. Unauthorized use of this repository's contents may violate local, state, national, or international laws.

5. **No Warranty**: The information, code, and tools in this repository are provided "as is" without any warranties of any kind, either express or implied. The author(s) make no representations or warranties regarding the accuracy, completeness, or suitability of the content provided.

6. **Third-Party Links**: This repository may contain links to third-party websites or resources. These links are provided for convenience only, and the author(s) do not endorse or assume any responsibility for the content, products, or services provided by third parties.

By continuing (scrolling, accessing, and/or using this repository), you acknowledge that you have read, understood, and agree to this disclaimer. If you do not agree to these terms, you should not use this repository or its contents and are advised not to continue. Please have a good day.

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

 files will be listed here.

</details>


---

## Acknowledgments

<div align="center" style="color: #ff6341;">
  
  I  want to thank the **reverse engineers/Devs** of the **tools** that have been essential for my analysis, including:
  <br><br>
  <a href="https://github.com/hasherezade" style="color: #ff6341;"><b>Hasherezade</b></a> for their repositories, <a href="https://github.com/hasherezade/crypto_utils" style="color: #ff6341;"><b>crypto_utils</a>.
  <br><br>
  Your contributions have been instrumental in my research.
  <br><br>
  Yours sincerely,<br>
  Will
</div>

---

```
// Notes
If you see a lot of `$\textcolor{red}{\...`, you need to enable JavaScript. It's just red text.
```
