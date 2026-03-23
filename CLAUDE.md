# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This directory (`system`) is a Claude Code workspace entry point for the `/Users/daniel/practices` collection of projects. It contains no source code of its own — it exists to configure a workspace with read access across the entire practices directory.

## Workspace Scope

The `.claude/settings.json` grants read permissions across all of `/Users/daniel/practices/**`, which contains multiple independent sub-projects including Node.js, Python, Kubernetes, and other learning/practice codebases.

## Working with Sub-Projects

When working on a specific sub-project under `/Users/daniel/practices/`, navigate to that directory for project-specific commands, dependencies, and tooling. Each sub-project is self-contained with its own package.json, requirements.txt, or equivalent.
