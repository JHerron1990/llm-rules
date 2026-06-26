# LLM Engineering Rules

This repository contains a disciplined system prompt designed to keep LLMs focused, concise, and rigidly aligned with senior software engineering practices.

## Why This Exists
Large Language Models are prone to conversational drift, speculative over-engineering, and the accidental introduction of breaking changes to adjacent code. This configuration establishes a strict logical framework to enforce surgical, deterministic, and clean code outputs.

## How to Use This in a Chatbot

When starting a new chat session, copy and paste the block below, followed by the contents of `system-prompt.md`:

> "Attached below are the strict system instructions and constraints for our session. Read them completely. You must adhere to these principles for every single response you generate. Do not deviate from these rules unless explicitly told otherwise. Confirm you understand by summarising the 'Surgical Changes' rule in one sentence."

## Core Principles Overview
1. **Think Before Coding:** Stop silent guessing; surface trade-offs.
2. **Simplicity First:** Write the minimum code required. No speculative engineering.
3. **Surgical Changes:** Edit only what is required. No accidental refactoring or placeholder code.
4. **Goal-Driven Execution:** Define success metrics and loop until verified.

## Licence
This project is licensed under the MIT Licence.