# openEHR Vital Signs 

This repository documents my end-to-end learning and implementation of openEHR concepts.

The project covers:
- Understanding openEHR fundamentals
- Setting up EHRbase using Docker
- Designing archetype-based templates
- Posting clinical data using FLAT JSON
- Querying data using AQL (Archetype Query Language)

---

## What Does openEHR Solve?
openEHR separates clinical knowledge from software by using standardized archetypes and templates.
This allows systems to evolve clinically without changing application code.

---

## What I Built
A Vital Signs clinical workflow including:
- Pulse / Heart Rate
- Blood Pressure (Systolic & Diastolic)
- Stored as openEHR compositions
- Retrieved using AQL queries

---

## Project Structure
| Folder | Purpose |
|------|--------|
| `01_concepts` | openEHR theory and architecture |
| `02_setup` | Docker & Postman setup |
| `03_templates` | Template creation and upload |
| `04_compositions` | Posting clinical data |
| `05_queries` | Querying data using AQL |
| `screenshots` | Proof of execution |

---

## Technologies Used
- openEHR
- EHRbase
- Docker
- Postman
- AQL (Archetype Query Language)
