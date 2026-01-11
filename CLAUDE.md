# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal birthday greeting project for Marjolijn. It contains a single-page React application (`birthday-marjolijn.html`) with accompanying media files.

## Structure

- `birthday-marjolijn.html` - Self-contained React birthday card with:
  - Photo slideshow (auto-advances every 4 seconds)
  - Audio player for birthday music
  - Animated confetti and balloons
  - File upload functionality for photos and audio
- `*.jpg`, `*.jpeg` - Photo collection
- `stevie.mp3` - Birthday song audio

## Running the Project

Open `birthday-marjolijn.html` directly in a web browser. No build step or server required - all dependencies (React, ReactDOM, Babel, Tailwind CSS) are loaded via CDN.

## Tech Stack

- React 18 (via CDN)
- Babel standalone (for JSX transformation in browser)
- Tailwind CSS (via CDN)
- Vanilla CSS animations
