# BattleRoy Foundation

## Core purpose
BattleRoy is a competitive idea-to-monetization operating system.

## What it must do
- store project memory
- run battles between agents
- generate execution plans
- track tasks and dependencies
- log decisions
- track monetization outcomes

## Architecture direction
- GitHub = source of truth
- Supabase/Postgres = memory layer
- API = execution engine
- Agents = decision + build layer
- UI = replaceable (Lovable temporary)

## First milestone
BattleRoy Core must:
- store a project
- store project state
- return project state via API
