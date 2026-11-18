<div align="center">

# 📐 Ingeniería del Software · UAH

**Software Engineering (Ingeniería del Software, 780015) · B.S. Computer Engineering · Universidad de Alcalá · 2025–2026**

![UML](https://img.shields.io/badge/UML-5C2D91?style=flat-square)
![IEEE 830](https://img.shields.io/badge/IEEE_830-SRS-161B22?style=flat-square)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Team](https://img.shields.io/badge/team-3_people-00C853?style=flat-square)

</div>

Two coursework reports covering the software lifecycle end to end: **requirements and UML design** for a new system, then **testing** an existing one with unit, white-box and black-box techniques.

> Done in a **team of 3** (group GII 2B). My teammates' names and everyone's ID numbers have been removed from the reports for privacy. This repository holds the reports (PDF); the code and test classes are included inside them.

---

## 📁 Contents

| Folder | Project | Report |
|---|---|---|
| [`PECL1-requisitos-uml-taller`](PECL1-requisitos-uml-taller) | Requirements specification and UML design for a car-repair workshop chain | [Memoria_PECL1.pdf](PECL1-requisitos-uml-taller/Memoria_PECL1.pdf) · 89 pp. |
| [`PECL2-pruebas-junit-agenda`](PECL2-pruebas-junit-agenda) | Unit tests, cyclomatic complexity, white-box and black-box testing of a digital diary | [Memoria_PECL2.pdf](PECL2-pruebas-junit-agenda/Memoria_PECL2.pdf) · 20 pp. |

---

## PECL1 · Workshop management system: requirements & design

The *Sistema de Gestión de Talleres Mecánicos* serves a central office in Madrid and 11 workshops, linked by LAN locally and VPN to head office. Four roles: **workshop manager, sales desk, mechanic and cashier**.

- **Software Requirements Specification following IEEE 830:** purpose, scope, stakeholders, product perspective, constraints and expected evolution.
- **7 functional requirements** (quotes, repair notifications, billing, staff productivity…).
- **Non-functional requirements:** data, performance, **security** (role-based access control, user validation), reliability, availability and maintainability.
- **Use-case documents and diagrams** for every actor.
- **UML class diagram**, **sequence diagrams** per role and a **deployment diagram** of the LAN/VPN architecture.

## PECL2 · Digital diary: software testing

- **Exercise 1 · JUnit:** unit tests for the model classes `Cita`, `CitaTrabajo`, `Contacto`, `ContactoProfesional`, `Tarea` and `TareaSeguimiento`.
- **Exercise 2 · Cyclomatic complexity:** computed three ways (edges and nodes, decisions, regions) and cross-checked.
- **Exercise 3 · Testing a given method:**
  - reverse engineering to a high-level design;
  - **white-box:** control-flow graph, cyclomatic complexity, basis paths and their test cases;
  - **black-box:** equivalence classes, test cases and **boundary-value analysis**.

---

<div align="center">

Miguel Hernández López · [GitHub](https://github.com/MiguelHernandezz) · [LinkedIn](https://www.linkedin.com/in/miguel-hernandez-lopez/)

</div>
