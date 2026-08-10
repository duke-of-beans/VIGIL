# VIGIL

A video intelligence pipeline: download, transcribe via Whisper, detect scene boundaries, capture keyframes, and analyze individual frames.

## The problem

Video is one of the least accessible formats for research and analysis at scale — no ctrl-F, no way to jump to the part that matters without watching the whole thing, and transcripts alone lose everything that happens visually.

## What it does

VIGIL runs a full pipeline against video sources: downloads the source, transcribes audio with Whisper, detects scene changes, captures a keyframe per scene, and runs frame-level analysis — turning an unsearchable video into a structured, queryable record of what was said and shown, and when.

## Part of a system

VIGIL is the video-intelligence layer supporting a larger cognitive-infrastructure stack. See [davidkirsch.me/builds](https://davidkirsch.me/builds) for the rest.
