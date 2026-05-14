# Genrun

A browser-based runner game with on-chain high score tracking powered by GenLayer Intelligent Contracts on the Bradbury Testnet.

## Live Demo
🎮 [Play Genrun](https://genrun-iota.vercel.app)

## What it does
- Players run and dodge obstacles in a browser game
- High scores are submitted and stored on-chain via a GenLayer Intelligent Contract
- Each wallet has its own verified high score and total games played
- Scores are publicly viewable by wallet address

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Smart Contract: GenLayer Intelligent Contract (Python)
- Deployed on: GenLayer Bradbury Testnet
- Hosted on: Vercel

## Smart Contract
Handles score submission and leaderboard storage on-chain using GenLayer's `TreeMap` storage.
