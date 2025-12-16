# Real-Time Speech Stream Processor

## Overview

This project is a real-time speech processing system built with **Python 3** that:

- Continuously records audio from a microphone
- Converts speech to text in near real time
- Broadcasts the transcribed text over a WebSocket server
- Allows multiple clients (JavaScript or Python) to receive live text
- Saves raw audio to disk without interruption

The system is modular, concurrent, and production-oriented.

---

## Architecture

The application is composed of four main components running in parallel:

