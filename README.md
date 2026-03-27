# LOGOS: Optically Isolated, Current-Controlled Closed-Loop System for m-tTIS

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19247637.svg)](https://doi.org/10.5281/zenodo.19247637)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Hardware-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: GPL v3](https://img.shields.io/badge/Firmware-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Про проєкт (Overview)
**LOGOS** — це апаратне ядро та детермінована прошивка закритого контуру для магнітно-опосередкованої темпоральної інтерференції (m-tTIS). 

Система спроєктована для синтезу когерентних магнітних полів із повним придушенням електромагнітних перешкод (EMI) та апаратних артефактів демодуляції завдяки архітектурі **Absolute Optical Air-Gap**. 

## Інтелектуальна власність та Prior Art (Defensive Publication)
⚠️ **УВАГА:** Цей репозиторій та пов'язана наукова публікація є офіційним **Defensive Publication (Prior Art Disclosure)**.

Мета цього релізу — перевести архітектуру оптично ізольованої гармонічної модуляції струму у суспільне надбання та заблокувати будь-які спроби її корпоративного патентування незалежно від сфери застосування (нейромодуляція, плазмовий синтез, РЕБ тощо).

* **Офіційна публікація:** [Zenodo DOI: 10.5281/zenodo.19247637](https://doi.org/10.5281/zenodo.19247637)
* **Криптографічна фіксація (TSA & Blockchain):** 27 березня 2026 року
* **SHA-256 документа:** `C2E54424432BAA8F855DE9BAD78029813D48BA06D3B0BF3B15CE84A737DEACC2`

## Ключові технологічні переваги (Architecture Highlights)
* **Абсолютна оптична розв'язка:** Домени керування, живлення та сенсорики фізично розділені. Зв'язок відбувається виключно через пластикове оптоволокно (POF).
* **Субпікофарадна бар'єрна ємність:** Виключає утворення струмових петель (ground loops) та гарантує повну гальванічну ізоляцію.
* **Апаратний контроль струму (Current-Controlled):** Підсилювач Class D у поєднанні з LC-фільтром другого порядку формує чистий синусоїдальний струм носія, автоматично компенсуючи дрейф імпедансу котушок.
* **Детерміноване ядро (Firmware):** Апаратний FSM та переривання в IRAM гарантують точну фазову синхронізацію, обмежену лише тактовою частотою процесора, без програмного джиттера.

## Цитування (Citation)
Якщо ви використовуєте цю архітектуру у своїх дослідженнях, будь ласка, посилайтеся на оригінальний документ:
```text
Lozovyi, Oleksandr. (2026). Optically Isolated, Current-Controlled Closed-Loop System for Magnetically-Mediated Temporal Interference Neuromodulation (m-tTIS) (Defensive Publication). Zenodo. [https://doi.org/10.5281/zenodo.19247637](https://doi.org/10.5281/zenodo.19247637)
