# Agents for Scientists

AI coding agents such as Claude Code are rapidly entering scientific work, but most researchers adopt them without guidance on security, personal data, or good practice. This organization hosts the material for a two-part workshop series on Git and AI-assisted research, along with a practical proposal for making AI assistance in research transparent and reviewable.

All material is published as Open Educational Resources and is free for any group to reuse.

## The workshop series

Both workshops are capped at 20 participants and are designed to be taken together: the first sets the foundations that the second builds on.

**Sign up:** [Registration form for both workshops](https://forms.gle/Zf5fPsPJqUxEoLgKA)

### Workshop 1: Git and GitHub for collaboration in scientific work

**15 July 2026, 09:30 to 14:30 (lunch catering included)**

ETH Zurich, CLD Building ([how to find us](https://ghe.ethz.ch/about/how-to-find-us.html))

A hands-on introduction to using Git and GitHub for collaboration in research, updated from a course previously taught for PhD students. Participants work both through the RStudio interface and at the terminal. Everything runs on local installations, set up as pre-work before the workshop.

This workshop is a prerequisite for Workshop 2.

### Workshop 2: Agentic coding for collaboration and scientific work

**September 2026, 08:30 to 17:00 (all-day catering included)**

[Villa Hatt, ETH Zurich](https://ethz.ch/en/campus/access/region-zurich/villa-hatt.html)

A critical, hands-on introduction to agentic coding tools for research: what they do well, where the risks lie, and the do's and don'ts of daily use, including security concerns and personal data.

Building on the foundations workshop, participants learn to treat the agent as a collaborator whose work is fully versioned and reviewable:

- Issues document the to-dos the agent works on.
- Every change the agent makes is committed, so it can be reviewed in the diff view and reverted at any time.
- The agent writes comprehensive commit messages, so the history itself documents why decisions were made.

## Transparent AI assistance

Transparency about AI assistance is becoming a core reproducibility question, yet journal policies are still vague or missing. The series closes with a review of existing journal policies and a practical proposal:

1. **Two kinds of commits.** Commits clearly distinguish work done by the human from work done by the agent. In both cases the agent writes the commit message, so the full change is captured, but the contribution is clearly attributed.
2. **A `prompts` folder.** The repository contains a folder that documents the prompts used for AI-assisted work, with timestamps and a clear link from each prompt to its commit.

Together, these make AI-assisted research transparent and reviewable by others, and they offer journals a concrete mechanism: require the prompts folder alongside the manuscript, with an overview of how the human and AI contributions can be reviewed.

## Reuse

All workshop material in this organization is openly licensed. You are welcome to reuse, adapt, and teach from it.

## Funding and support

This workshop series is supported by:

- The [Swiss Reproducibility Network (SwissRN)](https://www.swissrn.org/contents/community/nodes/) local node work at ETH Zurich
- The [Data Stewardship Network at ETH Zurich](https://library.ethz.ch/en/researching-and-publishing/data-management-and-policies/research-data-management/data-stewardship.html), funded by the [swissuniversities Open Science Programme](https://www.swissuniversities.ch/en/topics/open-science/open-science-programme)
- The [Global Health Engineering group at ETH Zurich](https://ghe.ethz.ch/)
