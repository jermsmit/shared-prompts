# Shared Prompts

A small collection of prompts I've built and used for my own job search. I'm sharing them here as a reference, not as a definitive toolkit. Take what's useful, ignore what isn't, and adapt freely.

## Why this exists

These aren't polished products or a cohesive "system." They're prompts I wrote to solve specific problems I ran into while job hunting: figuring out if a resume would survive an ATS, deciding whether a job posting was worth my time, and telling the difference between a real recruiter and a scam. I'm putting them up in case they save someone else the trouble of starting from scratch.

Feel free to fork, remix, strip out the parts you don't need, or use them as a starting point for something better.

## What's here

This repo is a running collection, so the list below will grow over time. Each prompt lives in its own file, named for what it does.

| File | What it does |
|---|---|
| `ats-resume-audit-prompt.md` | Audits a resume against a job description (or general benchmarks) and returns a scored ATS report covering keyword match, formatting, quantified impact, and conciseness. |
| `job-fit-scoring-prompt.md` | Scores a job posting against a candidate profile you provide separately, checks for hard blockers, and returns a 1 to 10 fit score with a clear recommendation. |
| `linkedin-profile-prompt.md` | Rewrites a LinkedIn profile from a resume, with constraints against filler language and AI-sounding phrasing. |
| `recruiter-fraud-risk-analyzer-v3.md` | Analyzes recruiter or job outreach for fraud risk, ideally from a raw `.eml` or `.msg` file so it can check headers and authentication. |
| `resume-modeling-prompt.md` | Tailors a resume to a specific job description, flagging gaps between the role's requirements and the candidate's actual background. |

New prompts will follow the same pattern: one file, one job, added to this table as they land.

## How to use these

Each file is a full prompt meant to be pasted into a chat with an AI assistant (Claude, ChatGPT, or similar) at the start of a conversation. Most expect you to fill in a placeholder (a job description, a resume, an email file) after pasting the prompt itself. Read through a prompt before using it. These were written for my own workflow and assumptions, so you may want to adjust tone, scope, or scoring thresholds to fit yours.

## A note on scope

None of these are meant to be authoritative. An ATS score from a prompt is not a guarantee of anything, and a fraud risk score is a starting point for your own verification, not a substitute for it. Treat the outputs as a second opinion, not a final word.

## Feedback

If you use one of these and find a gap, a bad assumption, or a better way to phrase something, open an issue or a pull request. I'll likely keep iterating on these as I use them more.
