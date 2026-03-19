# EPOS MASTER RULES

## SYSTEM TYPE
EPOS is a WordPress internal system built ONLY with WPCode snippets.

## NON-NEGOTIABLE RULES
- No plugins for system architecture
- No traditional app structure
- No frontend folders
- No HTML files
- No standalone UI files
- No external frameworks
- No Node
- No React
- No Vue
- No separate backend

## IMPLEMENTATION MODEL
Every functional module must exist as an independent WPCode snippet file.

## MANDATORY SNIPPET ORDER
Each snippet must follow this exact internal order:

1. Migration
2. REST API Routes
3. CRUD functions

## SOURCE OF TRUTH
This repository is the only source of truth for EPOS.
Nothing should be invented outside this repository.

## GOAL
The goal is to produce code that can be copied into WPCode and work inside WordPress with minimal or no modification.
