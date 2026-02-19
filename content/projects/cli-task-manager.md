---
title: 'CLI Task Manager'
date: 2025-10-18T10:00:00-00:00
lastmod: 2025-10-18T10:00:00-00:00
description: 'A command-line task manager built with Python. Features priority sorting, due dates, project grouping, and a clean terminal interface.'
tags: ['python', 'cli', 'productivity']
tech: ['Python', 'Click', 'SQLite']
github: 'https://github.com/pallets/click'
type: 'projects'
---

A lightweight task manager designed for developers who prefer the command line over GUI applications.

## Motivation

Most task management tools are web-based and require context switching away from the terminal. This tool keeps task management within the development workflow.

## Features

The CLI supports creating, listing, completing, and archiving tasks. Tasks can be assigned priorities, due dates, and project labels.

### Priority System

Tasks are sorted by priority and due date. Overdue tasks are highlighted automatically. The priority system uses a simple high, medium, low scale.

### Project Grouping

Tasks can be grouped by project. List views can be filtered by project, showing only relevant tasks. This keeps separate concerns organized.

### Data Storage

Tasks are stored in a local SQLite database. This provides reliable storage without requiring a server or external service. The database file can be synced between machines using any file sync tool.

## Technical Details

Built with Python and the Click library for CLI argument parsing. Click provides automatic help text generation and input validation.
