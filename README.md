# Script_documentcreation
 PlanetGreen Directory Structure Automation
PlanetGreen Directory Structure Automation
------------------------------------------

Overview:
This project is a Bash automation script that creates a structured, multi-level directory hierarchy for a fictional organization named PlanetGreen. It simulates realistic departmental folder structures under 'Earth' and replicates the same into four elemental folders: Wind, Fire, Water, and Heart.

Features:
- Automates folder creation for departments: IT, HR, Finance, Operations
- Includes realistic subfolders such as Payroll, Budgets, Security, etc.
- Creates monthly folders under Expense Reports
- Replicates the entire Earth structure to Wind, Fire, Water, and Heart
- Displays directory structure using 'tree'

Requirements:
- Bash-compatible terminal
- tree utility (auto-installed)
- sudo privileges for installation (Linux systems)

How to Run:
1. Save this script as 'planetgreen.sh'
2. Run in terminal with:
   bash planetgreen.sh

Directory Layout Summary:
PlanetGreen/
├── Earth/
│   ├── IT/
│   │   ├── Management, Engineering, etc.
│   ├── HR/
│   │   ├── Policies/2023, Payroll, etc.
│   ├── Finance/
│   │   ├── Expense Reports/January–December, Budgets/
│   └── Operations/
│       ├── Management, Sales, etc.
├── Wind/
├── Fire/
├── Water/
└── Heart/

Learning Objectives:
- Practice Bash scripting
- Automate directory structures
- Understand logical folder grouping in enterprise setups
