# AI Starter Pack

Document-first AI development workflow starter.

## Philosophy

* Document-first development
* Proposal approval before implementation
* Context-based session continuation
* System-output based verification
* Avoid over-engineering

## Lite Workflow

kickoff -> propose -> approve -> implement -> update-context

Description

kickoff
Create project brief.

propose
Write proposal for changes.

approve
Approve proposal and define tasks.

implement
Implement approved tasks.

update-context
Record context for next session.

## Advanced Mode

Optional automation layer.

Enable

aiupgrade advanced <project_name>

Features

* router (automatic command decision)
* review stage separation
* qa stage separation
* workflow state machine
* meta-agent orchestration

Disable

aiupgrade rollback <project_name>

## Verification Policy

* Never declare success without system output.
* Use FAIL / UNVERIFIED when uncertain.
* Raw output takes priority over explanation.

## CLI Commands

aistart <project_name>
Create Lite starter project.

aiupgrade advanced <project_name>
Enable advanced automation layer.

aiupgrade rollback <project_name>
Return project to Lite mode.

## Quick Start

Create a starter project using the CLI.

Example

aistart myproject

cd myproject

Workflow

kickoff -> propose -> approve -> implement -> update-context

## Example Usage

aistart blog_engine

kickoff
propose
approve
implement
update-context

## License

MIT
