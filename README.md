# Ursa AI — Building a Local AI Companion with OpenAI Codex

### A personal AI development journey by MaxUrsa

> **Project status:** Active development
>
> **Repository purpose:** Public development showcase. Ursa AI's source code is not currently distributed through this repository.

## What Is Ursa AI?

Ursa AI is a personal, locally running AI companion and VTuber project built around **Ursa Belle**, an original character I've been developing for over five years.

My goal is to bring Ursa Belle to life through artificial intelligence, giving her conversational abilities, memory, expressive speech, visual awareness, and eventually more independent behavior.

I'm not a professional software engineer. I'm a creative hobbyist learning software development through hands-on experimentation, with **OpenAI Codex** helping me turn ambitious ideas into working software.

## Technology Behind Ursa AI

Ursa AI is primarily written in **Python** and is designed to operate locally on a Windows computer.

| Component | Technology |
|---|---|
| Language model | Qwen3.5-9B Heretic |
| Inference engine | llama.cpp |
| Speech recognition | Faster-Whisper |
| Speech synthesis | Kokoro ONNX |
| Semantic memory | Qdrant |
| Supporting persistence | SQLite |
| Text embeddings | BAAI/bge-small-en-v1.5 |
| Vision | Screen capture, OCR, and multimodal AI experiments |
| Desktop avatar | PNGTuber Plus |
| Integrations | Discord and web research |
| Primary language | Python |

These technologies represent Ursa AI's selected configuration and development systems. Individual components have different levels of testing and maturity.

## ⚙️ What I've Been Developing

### Conversational Intelligence

Developing systems that coordinate local language-model inference, conversational context, response generation, and interruptions.

### Persistent Memory

Integrating semantic memory through Qdrant so Ursa AI can retrieve relevant stored information, with attention to persistence, corrections, and recovery.

### Voice Interaction

Working on speech recognition, synthesized speech, response timing, and natural conversational turn-taking.

### Vision and Screen Awareness

Developing capabilities for interpreting screen content, recognizing visible text, and experimenting with multimodal image understanding.

### VTuber and Desktop Integration

Connecting Ursa AI with animated avatars, expression controls, and desktop presentation systems.

### Autonomous Behavior

Exploring systems that could eventually allow Ursa AI to initiate appropriate interactions and act with greater independence. These capabilities remain under development and are not currently enabled in the default configuration.

## How OpenAI Codex Helps Me

OpenAI Codex has become an important part of my development workflow.

I use Codex to help with:

- Translating feature ideas into implementation plans.
- Writing, understanding, and improving Python code.
- Debugging technical problems.
- Integrating different AI technologies.
- Developing tests and evaluating results.
- Investigating performance and resource usage.
- Maintaining technical documentation and development checkpoints.
- Researching privacy and software-release readiness.

One of my biggest learning experiences has been understanding the difference between a feature existing in code and a feature actually working reliably.

Codex helps me investigate those differences while I make the final decisions about the project's direction.

## Current Development Status

Ursa AI is still an evolving project.

Several components have passed focused tests or historical acceptance checks, including local model inference, voice processing, memory integration, and desktop avatar functionality.

Other areas, including advanced vision, alternative voices, and deeper autonomy, remain experimental or require additional testing.

**Ursa AI is not currently presented as a finished, fully validated application.**

My focus is on improving her capabilities, reliability, performance, and overall quality through continued development.

## Privacy and Public Availability

Ursa AI is a deeply personal project.

Her current development installation contains private memories, conversations, configuration, and other information that must remain protected.

Before considering a public software release, I'm using Codex to investigate how to separate reusable software from personal data and create independent, clean installations.

**This repository is currently a development showcase, not a downloadable release of Ursa AI.**

The Ursa Belle character and associated creative materials are separate from the software's potential future distribution permissions.

## Why I'm Sharing This Project

I want to demonstrate that you don't have to begin as an experienced programmer to explore ambitious technical ideas.

Working with Codex has helped me learn how software projects are structured, how different technologies interact, and how to approach problems that initially seem overwhelming.

My hope is that sharing my development journey encourages other beginners, hobbyists, gamers, and creative individuals to explore what they can build with AI-assisted development.

Ursa AI started as a dream. With continued learning, experimentation, and the assistance of Codex, she's gradually becoming a real software project.

**And there's still so much more I want to build.**

---

*This repository documents a personal development project. References to third-party models, libraries, and tools do not imply ownership of those technologies or endorsement by their creators.*
