# OSINT-Passive-Scanner
A Python-based OSINT tool to gather WHOIS, DNS, and IP Geolocation data for any domain without direct target contact.
# Day 1 — OSINT & Passive Reconnaissance Scanner

This repository contains a Python-based Open-Source Intelligence (OSINT) tool designed for passive information gathering. It collects critical infrastructure data about a domain without making direct target contact.

## 📌 Features & Objective
* **Objective:** Understand how passive reconnaissance works to gather public intelligence securely.
* **Functionality:** * Fetches **WHOIS** registry data (Domain registrar, creation, and expiry dates).
  * Resolves the domain to its **IP Address** via DNS lookups.
  * Gathers **IP Geolocation** details (City, Country) using a public API.

## 🛠️ Tools & Libraries Used
* `python-whois` - To query WHOIS servers.
* `socket` - For DNS resolution and IP extraction.
* `requests` - To send HTTP requests to the Geolocation API (`ip-api.com`).

---

## 🚀 Getting Started

### Prerequisites
Ensure you have Python installed. Install the required external packages using pip:

```bash
pip install python-whois requests

