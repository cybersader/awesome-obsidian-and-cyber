---
---

> This is an incredibly rough draft of things to put into here as a placeholder

1. [Working Group](#working-group)
	1. [Current Projects, Ideas, Tasks](#current-projects-ideas-tasks)
		1. [Tasks](#tasks)
		2. [Projects](#projects)
2. [General Obsidian & Workflow](#general-obsidian--workflow)
	1. [0) Obsidian Starters & Templates](#0-obsidian-starters--templates)
		1. [Starter Vaults](#starter-vaults)
	2. [1) Core Activities](#1-core-activities)
		1. [1.1) Knowledge Capture](#11-knowledge-capture)
		2. [1.2) Knowledge Work](#12-knowledge-work)
		3. [1.3) Knowledge Sharing & Output](#13-knowledge-sharing--output)
	3. [2) Organizing Cyber-Related Knowledge & Information](#2-organizing-cyber-related-knowledge--information)
	4. [3) Obsidian Plugins](#3-obsidian-plugins)
3. [By Solution - Cybersecurity, GRC, DFIR](#by-solution---cybersecurity-grc-dfir)
	1. [Task management](#task-management)
	2. [GRC](#grc)
	3. [IR](#ir)
	4. [Awareness](#awareness)
	5. [SecOps](#secops)
	6. [Application Security](#application-security)
	7. [Penetration](#penetration)
4. [Obsidian Technicals](#obsidian-technicals)
5. [Using Obsidian for...](#using-obsidian-for)
	1. [for Corporate, Enterprise](#for-corporate-enterprise)
	2. [for Community](#for-community)
	3. [for Personal Branding](#for-personal-branding)
	4. [for Family, Personal, Partners, Friends](#for-family-personal-partners-friends)
	5. [for Education](#for-education)
6. [Opinionated Additional Tools](#opinionated-additional-tools)
	1. [Obsidian Tools](#obsidian-tools)
	2. [Browser](#browser)
	3. [Core Windows](#core-windows)
	4. [Core Mac](#core-mac)
7. [Obsidian Plugin Development](#obsidian-plugin-development)
8. [Other Knowledge Platforms (Wiki, KMS, Notetaking)](#other-knowledge-platforms-wiki-kms-notetaking)


---

# Working Group

- if you would like to join the working group than contact me at https://cal.com/cybersader 

## Current Projects, Ideas, Tasks

### Tasks

Check the `Projects` tab for current tasks.

<ins>Curated tasks from this README:</ins>
<!-- QueryToSerialize: LIST WITHOUT ID t.text FLATTEN file.tasks AS t WHERE file.name = this.file.name -->
<!-- SerializedQuery: LIST WITHOUT ID t.text FLATTEN file.tasks AS t WHERE file.name = this.file.name -->
- start GRC template repo ➕ 2025-05-04

- Add "cyberbase" starter (need to make a repo for this) ➕ 2025-05-04
- Develop a community vault repo ➕ 2025-05-04
- Need to do more testing to build a good mobile vault that is performant, has good buttons, etc. ➕ 2025-05-04
<!-- SerializedQuery END -->

### Projects

<ins>Easy: </ins>

- Starter vaults for for SecOps, couple/family productivity, personal branding, GRC, and more
- Test Obsidian plugins with application firewall to watch traffic
- Curate Obsidian plugins
- Curate workflows, examples, and user stories

<ins>Medium:</ins>

> With time, you can solve some of these with AI.  They just take awhile

- Plugin to map/sync folders and tags (multiple hierarchies so we aren't limited by folders)
- Crosswalker - convert frameworks into Obsidian notes
- Frameworker - obsidian plugins or workflow to define metadata per framework <-> obsidian_note connection. This would be step 1 of turning Obsidian into a full-fledged GRC database

<ins>Hard / Seasoned-Developer / Pentester:</ins>

- Test risks of Obsidian application
- Fix SMB share and other problems by implementing CRDT-based reconciler for file system like OneNote uses.  Conflict handling for multiple user situations like corporate without needing to go to a block-baswd system like Notion
- User management layer on-top of browser-based Obsidian (linuxserver container like what KASM workspaces uses).  This would make Enterprise use with Obsidian possible (collaboration and accessibility with security)

---

# General Obsidian & Workflow

## 0) Obsidian Starters & Templates

### Starter Vaults

#### (Starter Vaults) Corporate, Enterprise

- [github.com > cybersader/obsidian-secops-vault-template](https://github.com/cybersader/obsidian-secops-vault-template) - corporate template in progress
- [ ] start GRC template repo ➕ 2025-05-04
	

#### (Starter Vaults) Personal Branding

- [github.com > cybersader/cyberbase: My public and contributable base/wiki/digital garden for cybersecurity](https://github.com/cybersader/cyberbase) - my live vault that I use as a website

- [ ] Add "cyberbase" starter (need to make a repo for this) ➕ 2025-05-04

#### (Starter Vaults) Community Vault

- [ ] Develop a community vault repo ➕ 2025-05-04

#### (Starter Vaults) Mobile Vaults

- [ ] Need to do more testing to build a good mobile vault that is performant, has good buttons, etc. ➕ 2025-05-04

## 1) Core Activities

### 1.1) Knowledge Capture

- Obsidian web clipper templates
- Useful ancillary tools, platforms, workflows

### 1.2) Knowledge Work

- Cybersecurity-specific Obsidian plugins
- Knowledge platforms and cyber
	- Organizing knowledge related to cyber - unique problems and solutions for this

### 1.3) Knowledge Sharing & Output

- Obsidian Publish templates
- Using GitHub for community wiki and contributions

## 2) Organizing Cyber-Related Knowledge & Information

> These are example taxonomies that can be used or modified to organize knowledge or information around particular subjects.

- SEACOW(r) - a meta framework for organizing knowledge platforms
- PARA - a folder structure oriented towards what is actionable vs non-actionable knowledge
- Zettelkasten - writer and research focused workflow or approach
- LATCH
- ACE
- ARCO
- STIR

## 3) Obsidian Plugins

- [obsidianstats.com > Explore New](https://www.obsidianstats.com/) - Best place to explore and bookmark Obsidian plugins
- 

---

# By Solution - Cybersecurity, GRC, DFIR

## Task management

- do individual task management in obsidian and escalate to longer term tasks and project MGMT tooling when necessary

## GRC

- map frameworks as notes in obsidian and turn Obsidian into your core evidence mapping and risk management platform.  Store your evidence/knowledge right alongside the frameworks you map to
- set up automations alongside your vault
- Use Obsidian to help other understand how to organize files

## IR

- Set up a backup vault using obsidian Publish or sync with a password that the CISO or chief security related officer only has access to
- Give responders access to the vault to help onboard, see playbooks, and quickly become valuable during the event

## Awareness

- set up games via the education section below for awareness or training

## SecOps

- set up your core working, wiki, and knowledge management environment in Obsidian and collaborate in real time.  this part is hard but game changing
- Store tutorials and document 
- replace using OneDrive or file explorer for working with knowledge content and notes and docs

## Application Security

- make program documentation in Obsidian and format to work with GitHub

## Penetration

- streamline test reporting and documentation
- organize pen testing knowledge for easier sharing and collaboration 

--- 

# Obsidian Technicals

> these are relevant to corporate and to threat model the system

- Browser-based Obsidian
- Collaboration in Obsidian
- Plugin risks and security
- Securing Obsidian Application (network)
- Obsidian vendor philosophy
- Using application firewall with Obsidian

---

# Using Obsidian for...

## for Corporate, Enterprise

- https://cybersader.com/corporate-obsidian
- Obsidian risks in corporate and mitigations
- https://cybersader.com/obsidian-in-browser
- Using Obsidian for IR and knowledge sharing for responders
- Limitations of using SMB shares

## for Community

- Using Obsidian for cyber community and knowledge sharing - modern Wikipedia
- Contributable Obsidian wiki

## for Personal Branding

- Examples
	- https://cybersader.com/%F0%9F%93%81+51+-+Cyberbase/Cyberbase+Development/Cyberbase+Development
	- cybersader.com - my personal website that uses it
	    - https://github.com/cybersader/cyberbase

## for Family, Personal, Partners, Friends

- couple vault template

## for Education

- cynario builder using obsidian, obsidian Publish, or link compatible platforms
- education templates

---

# Opinionated Additional Tools

## Obsidian Tools

- .

## Browser

- .

## Core Windows 

- .

## Core Mac 

- .

---

# Obsidian Plugin Development

- workflow and tooling

---

# Other Knowledge Platforms (Wiki, KMS, Notetaking)

- Alternative tools - not Obsidian
- Using Notion and Obsidian
	- https://github.com/cybersader/notion-to-obsidian-github-sync
- Affine, Appflowy, Trillium, etc.
- Comparisons for cyber