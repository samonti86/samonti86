# Saul Montiel

**Enterprise support engineer.** Twelve years keeping infrastructure software working —
Microsoft, Commvault, Cohesity, Hyperscience. Linux, Kubernetes, Docker, AWS, Azure, MS SQL,
backup and recovery.

For twelve years the job has been the same: something's broken in a customer's environment,
the logs are enormous, people are stressed, and someone has to work out what actually happened.

A couple of years ago I got tired of doing that by hand, so I started building tools instead.

## How I build

**I'm not a software engineer and I won't pretend to be one.** I read code and debug it; I don't
write it from a blank file. What I'm good at is knowing exactly which tool needs to exist — and
then driving an AI coding assistant until it does, then testing it, breaking it, and fixing it
until it's trustworthy.

At Hyperscience I built three internal tools that way (Copilot CLI + LLM APIs): one that collects
and triages customer diagnostic logs and surfaces probable root causes, one that sizes
infrastructure from a customer's real document volume, and one that catches fixes needing backport
before they bite. Nobody asked me to build any of them. That code belongs to Hyperscience, so it
isn't here — but the instinct behind it is what's in this profile.

**On using LLMs, since that's the thing everyone claims now:** I don't treat them as magic. An LLM
is very good at reading 40,000 lines of log noise and telling you where to look. It is *not* good
at being trusted without checking. The tools I build put the model where it's strong —
summarizing, pattern-matching, ranking what looks suspicious — and leave the actual call to a
human who verifies it. That distinction is most of the difference between a tool people use and a
tool people quietly stop trusting.

## What's here

| Project | What it is |
|---|---|
| **[jarvis](https://github.com/samonti86/jarvis)** | Always-on Windows voice assistant with a 36-tool agentic layer built on Claude. Local wake word + speech-to-text, streamed TTS, sandboxed code execution, vision and security modes, phone and Discord clients. This is the one that shows how I actually work: 186 commits of specifying, testing, breaking, and fixing until the thing could be trusted. |
| **[pc-tuneup](https://github.com/samonti86/pc-tuneup)** | Self-elevating Windows 10/11 maintenance script. Safe monthly routine, integrity repair, and an Event Viewer health analysis that surfaces real incidents. One `.ps1`, no dependencies, in-box PowerShell 5.1. Careful about the things that quietly break unattended maintenance — missing `winget`, third-party AV displacing Defender, native tools that report failure only via exit code. |
| **[terminal-setup](https://github.com/samonti86/terminal-setup)** | My Windows terminal environment captured as code — Windows Terminal + PowerShell 7 + oh-my-posh. One script rebuilds it on a fresh PC. |

## What I'm looking for

My role was eliminated in Hyperscience's July 2026 layoff. I'm looking for **enterprise support or
IT operations** work where deep infrastructure experience is the baseline and building the internal
tooling that makes the whole team faster is the point.

Fort Lauderdale, FL — or remote.

📫 **saul.a.montiel@live.com** · [LinkedIn](https://www.linkedin.com/in/saulamontiel/)
