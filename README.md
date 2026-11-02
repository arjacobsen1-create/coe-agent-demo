# Knowledge Maintenance Agent — Concept Demo

## ▶ Live page — start here

**[Open the demo](https://arjacobsen1-create.github.io/coe-agent-demo/)**

GitHub shows this project's files as code. The link above opens the
finished page in your browser: press "Run the morning check" and decide
the findings yourself.

## What this is

A working model of an idea: an agent that watches an organisation's
official source documents, notices when one changes, works out which
knowledge-hub pages are affected, explains the change in plain words,
drafts the update, and then waits. It never publishes anything. A human
approves, rejects, defers or escalates every item, and every decision is
written to a log.

The demo walks through four findings: a material change (a support
contact changed), an editorial reissue (words only, no action), a
conflict between two official sources (escalated, never guessed at),
and a superseded standard (a page still pointing at the old version).

## Fictional data

Northfield Manufacturing does not exist. Neither do its people, its
documents or its phone numbers. This demo is not connected to any real
system, and it is not built from any real company's documents or data.
It exists so the idea can be seen and clicked before anything is built
for real.

In a real organisation, this flow would run inside that organisation's
own systems and security boundary, with named owners for every watched
source and every page.

## How it is built

One self-contained page, `index.html` in this repo, served by GitHub
Pages. No data is sent anywhere; the demo resets when the page is
refreshed.

Built by Anahita Jacobsen.
