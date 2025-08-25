---
title: "Solutionstatement"
status: "open"
created: "23.8.2025, 14:00:24"
url: "https://github.com/Luis85/Obsidian-Plugin-Development-Starter-Kit/issues/15"
opened_by: "Luis85"
assignees: ["Luis85"]
updateMode: "update"
allowDelete: false
---

# Solutionstatement
The Obsidian Plugin Development Starter-Kit. 
An opinionated framework for well documented prototypes and products with a problem first approach.

- Automate the Project Setup for new Obsidian Plugin Ideas
- Have sensible defaults for rapid idea validation
- Bring transparency and traceability to the whole Delivery Process
- Be prepared for success

## How does the solution work?

The solution will rely heavily on Git, GitHub, and Obsidian, and will be build around the provided features of these tools.

Using Issues to describe the Problemspace and Pull Request defining the Solutionspace.

Leveraging the following features:

- Documentation in Markdown
- Designing and Data Enrichment with Obsidian
- Issue Management
- Pull Requests and Change Management
- Versioning and Distribution


## Solutionidea

**Targetgroup:** Solo Developer

- The solution provides for every point in the lifecycle of a Plugin Idea the right tools to enable consistent documentation and traceability
- The solution guides trough the necessary steps from Idea to published Solution depending in the needed quality
- Provide a complete and versioned Development Environment as downloadable Obsidian Vault Folder with the necessary Plugins and Settings in place
- Integrate with Git for versioning
- Provide Plugin Boilerplate for Development in TypeScript
- Provide Documentation Structure for Plugin plublishing
- Integrate with GitHub for Issue Tracking and Feedback for Improvements
- Problemspace is well separated within GitHub
- Solutionspace evolves around Git, Pull-Requests, and Obsidian

## Workflow

- Fork the Starter-Kit
- git clone the forked repo
- Open the new folder as workspace in VS Code
- Edit manifest.json, package.json, LICENSE, and README.md
- npm install
- npm dev-server
- Open the configured dist folder as Obsidian Vault to test your plugin
- Happy Coding!

## Mentalmodel

Documentation is a living Artifact and gets created automatically while working. It is up to us to surface our knowledge and align on the same language and goals.

The Repo is the Status Quo of the actual Solution, by creating a Pull Request you propose a Change to the current Solution, constraint and guided by the Issues defining the current Problemspace.

By using the Issues Feature from GitHub we can connect Issues, Pull Request via Commit References and make the path from Issue to Idea to Solution visible with Obsidian.

Following a Dual-Track approach as base for the product development process we see Issues as defining domains and boundaries of our Problemspace, guiding and documenting Product Discovery. 

Pull Requests define and describe an agreed on Solution giving context and scope for our upcoming work. Connecting Issues and Solutions via Commit Messages. Making changes to the System traceable and visible.

During Pull Request Refinement emerge Solutions described as User Story.

- The solution must help and support fostering a Problem first mentality.
- The solution must help and support fostering an agile and lean Organisation.
- The solution must provide a template first approach
- The Git Repo represents the implemented Solution
- The GitHub Issue Tracker represents and defines the Problemspace
- The GitHub Pull Requests represent a Product Increments Lifecycle
- The GitHub Pull Requests define the Scope of a Product Increment following the Problem -> Insight -> Solution Format
- Obsidian is the User Interface for the Documentation
- The Git Repo is the source of truth
- Hierachies: Jobs to be done -> Features -> User Stories

## Repo Structure

- .obsidian
- dist
    - Project Name
- docs
    - 01 Features
    - 02 Areas
    - 03 Resources
    - 04 Archives
- src
LICENSE
TODO.md
README.md
Manifest.json
Package.json
.gitignore


## Recommended Plugins

- Advanced Canvas
- Excalidraw
- BPMN 
- Folder Notes


## Required Plugins

- Git Plugin
- Hotreload


## Out of Scope

- Custom User Interface
- Plugin Development
- Integrations


## Basic Deliverables

- README.md
- Todos.md
- Product Vision
- Solution Concept
- Proof of Concept
- Teststrategy
- Developmentstrategy
- Releasestrategy
- Change Management
- Risk Management
- IT Security Concept
- Delivery Plan
- System Landscape
- Backlog
    - Jobs to be done
    - Features
    - User Stories
    - Requirements
    - Issues
    - Risks
    - Bugs
    - Deliverables
- Documentation
    - Reviews
    - Audits
    - Checklists
    - Templates
    - Glossary


## Assumptions 

- GitHub can be used for proper Change Management 
- GitHub can be used for proper Issue Management 
- GitHub can be used for basic Feedback Management 
- GitHub can be used for basic Quality Management
- GitHub can be used for Release Management
- GitHub can be used for Distribution
- Constraining the Documentation to Markdown Input helps getting a well enough content- and knowledge base for further data enrichment and information processing supporting faster delivery of valuable insights for further improvements and cheap change during the whole product lifecycle


