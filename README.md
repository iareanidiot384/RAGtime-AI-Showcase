# RAGtime AI

RAGtime AI is a real-time accompaniment system that listens to live piano input and responds with musically aligned orchestral context.

Instead of time-stretching audio to force synchronization, it retrieves structurally compatible accompaniment fragments based on performance timing behavior.

## What It Delivers

- Live MIDI capture from performance input
- Phrase-aware rhythm profiling in real time
- Similarity-based retrieval from a prepared accompaniment corpus
- Fast loop from performance to playback response
- Browser-based monitoring and interaction

## Why This Project Matters

This project demonstrates practical real-time AI system design for music:

- Low-latency event processing
- Robust feature extraction from noisy expressive input
- Retrieval-first decision logic for predictable behavior
- Deployable architecture that runs on standard developer hardware

## Engineering Highlights

- Implemented a streaming pipeline from MIDI events to retrieval queries
- Built fixed-dimension rhythmic embeddings to compare variable-length phrases
- Designed an indexed corpus pipeline for batch preparation and fast runtime lookup
- Added phrase boundary detection to make retrieval musically coherent
- Exposed operational diagnostics for latency and reliability tracking

## System Design (High Level)

1. Capture note-on timing events from live input
2. Convert timing deltas into a rhythmic descriptor
3. Normalize and embed into a fixed query representation
4. Retrieve top matching accompaniment segments from the indexed corpus
5. Return and render the selected response for immediate playback

## Current Focus

- Higher-fidelity orchestral rendering
- Stronger context continuity across successive phrases
- Improved retrieval precision under expressive tempo variation

## Public Showcase Scope
- This repository is a product showcase and overview only. Implementation details and source code are maintained separately.

## Contact
Interested in a walkthrough, collaboration, or technical deep dive:

- Open an issue in this repository or reach out via GitHub profile


## License

MIT
