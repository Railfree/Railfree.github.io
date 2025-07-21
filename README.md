# AI Model Release Timeline

This is an interactive timeline of significant AI model releases. The data (`timeline-data.js`) is human-curated for accuracy, while the front-end (`index.html`) was created using an LLM.

## Live Demo

**[View the live timeline here](https://railfree.github.io/)**

## Features

- **Interactive Timeline:** Browse AI model releases chronologically from 2016 to 2025.
- **Dynamic Filtering:** Filter the timeline by:
    - Year
    - Provider (e.g., OpenAI, Google, Meta)
    - Category (Open Weights vs. API Only)
- **Source Links:** Each event includes one or more links to the original announcement, paper, or relevant resource.
- **Event Counters:** See a real-time count of visible "Open Weights" and "API Only" models based on your filters.
- **Zero Dependencies:** Built with pure HTML, CSS, and Vanilla JavaScript.

## File Structure

- `index.html`: The main HTML file for the webpage.
- `timeline-data.js`: A JavaScript file containing all the timeline event data as an array of objects. This is the single source of truth for the timeline content.
- `README.md`: This file.

## Sources

This timeline was originally compiled and inspired by data from the following sources:
1. https://nhlocal.github.io/AiTimeline/
2. https://huggingface.co/spaces/reach-vb/2024-ai-timeline
