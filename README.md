# LOGOS: Optically Isolated, Current-Controlled Closed-Loop System for m-tTIS

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19247637.svg)](https://doi.org/10.5281/zenodo.19247637)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Hardware-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: GPL v3](https://img.shields.io/badge/Firmware-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

---

## 🇬🇧 English

### Overview
**LOGOS** is a hardware core and deterministic closed-loop firmware for magnetically-mediated temporal interference stimulation (m-tTIS). 

The system is engineered for coherent magnetic field synthesis with complete suppression of electromagnetic interference (EMI) and hardware-induced demodulation artifacts via the **Absolute Optical Air-Gap** architecture.

### Intellectual Property & Prior Art (Defensive Publication)
⚠️ **NOTICE:** This repository and the associated scientific publication constitute an official **Defensive Publication (Prior Art Disclosure)**.

The purpose of this release is to place the architecture of optically isolated harmonic current modulation into the public domain, effectively blocking any attempts at corporate patenting across all domains of application (neuromodulation, plasma synthesis, EW, etc.).

* **Official Publication:** [Zenodo DOI: 10.5281/zenodo.19247637](https://doi.org/10.5281/zenodo.19247637)
* **Cryptographic Timestamp (TSA & Blockchain):** March 27, 2026
* **Document SHA-256:** `C2E54424432BAA8F855DE9BAD78029813D48BA06D3B0BF3B15CE84A737DEACC2`

### Architecture Highlights
* **Absolute Optical Isolation:** Control, power, and sensing domains are physically partitioned with zero shared electrical reference. Communication is executed exclusively via plastic optical fiber (POF).
* **Sub-picofarad Barrier Capacitance:** Eliminates conductive coupling paths and prevents the formation of ground loops.
* **Current-Controlled Mode:** A Class D amplification stage paired with a passive 2nd-order LC filter converts the digital PWM into a pure sinusoidal current carrier, automatically compensating for coil impedance drift.
* **Deterministic Firmware Core:** Hardware FSM and IRAM-loaded interrupts provide deterministic execution latency, guaranteeing strict phase synchronization bounded by hardware timing primitives.

### Citation
If you use this architecture in your research, please cite the original defensive publication:
```text
Lozovyi, Oleksandr. (2026). Optically Isolated, Current-Controlled Closed-Loop System for Magnetically-Mediated Temporal Interference Neuromodulation (m-tTIS) (Defensive Publication). Zenodo. [https://doi.org/10.5281/zenodo.19247637](https://doi.org/10.5281/zenodo.19247637)



🇺🇦 Українська
Про проєкт
LOGOS — це апаратне ядро та детермінована прошивка закритого контуру для магнітно-опосередкованої темпоральної інтерференції (m-tTIS).

Система спроєктована для синтезу когерентних магнітних полів із повним придушенням електромагнітних перешкод (EMI) та апаратних артефактів демодуляції завдяки архітектурі Absolute Optical Air-Gap.

Інтелектуальна власність та Prior Art (Defensive Publication)
⚠️ УВАГА: Цей репозиторій та пов'язана наукова публікація є офіційним Defensive Publication (Prior Art Disclosure).

Мета цього релізу — перевести архітектуру оптично ізольованої гармонічної модуляції струму у суспільне надбання та заблокувати будь-які спроби її корпоративного патентування незалежно від сфери застосування (нейромодуляція, плазмовий синтез, РЕБ тощо).

Офіційна публікація: Zenodo DOI: 10.5281/zenodo.19247637

Криптографічна фіксація (TSA & Blockchain): 27 березня 2026 року

SHA-256 документа: C2E54424432BAA8F855DE9BAD78029813D48BA06D3B0BF3B15CE84A737DEACC2

Ключові технологічні переваги
Абсолютна оптична розв'язка: Домени керування, живлення та сенсорики фізично розділені. Зв'язок відбувається виключно через пластикове оптоволокно (POF).

Субпікофарадна бар'єрна ємність: Виключає утворення струмових петель (ground loops) та гарантує повну гальванічну ізоляцію.

Апаратний контроль струму (Current-Controlled): Підсилювач Class D у поєднанні з LC-фільтром другого порядку формує чистий синусоїдальний струм носія, автоматично компенсуючи дрейф імпедансу котушок.

Детерміноване ядро (Firmware): Апаратний FSM та переривання в IRAM гарантують точну фазову синхронізацію, обмежену лише тактовою частотою процесора, без програмного джиттера.

Цитування
Якщо ви використовуєте цю архітектуру у своїх дослідженнях, будь ласка, посилайтеся на оригінальний документ:

Plaintext
Lozovyi, Oleksandr. (2026). Optically Isolated, Current-Controlled Closed-Loop System for Magnetically-Mediated Temporal Interference Neuromodulation (m-tTIS) (Defensive Publication). Zenodo. [https://doi.org/10.5281/zenodo.19247637](https://doi.org/10.5281/zenodo.19247637)
Ліцензія
Апаратна частина, схеми та документація: CC BY-NC-SA 4.0

Вихідний код (Firmware): GNU GPLv3

Розроблено в Україні.
