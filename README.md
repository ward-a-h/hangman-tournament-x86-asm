# Hangman Tournament in x86 Assembly

> 🚧 Work in progress. Computer Organization and Assembly Language (EL-2003) lab project at FAST NUCES Karachi, Fall 2026.

A console word-guessing game written in 32-bit x86 Assembly with MASM and the Irvine32 library. Beyond basic Hangman, it adds categories, difficulty levels, console themes, timing, scoring and a leaderboard saved to a file.

## Planned features

- Player name entry and main menu
- Word categories, difficulty levels and colour themes
- Random word selection with `RandomRange`
- Guess validation that rejects repeated or invalid letters and reveals every matching position
- ASCII Hangman display, lives and win/loss handling
- Completion timer with `GetMseconds` and an integer score based on difficulty, lives left, mistakes and speed
- Attempt log and ranking, with ties broken by fewer wrong guesses and then faster time
- Persistent leaderboard stored with file I/O

## Assembly concepts used

Registers and indexed addressing, arrays and string processing, loops and conditional jumps, procedures and the stack, integer arithmetic, and Irvine32 console, timer and file procedures.

## Tools

MASM, Irvine32, Visual Studio 2022, Windows (x86, 32-bit)

## Status

- [x] Proposal
- [ ] Core game loop
- [ ] Categories, difficulty and themes
- [ ] Timer and scoring
- [ ] Attempt log and leaderboard
- [ ] Final testing

## Author

Wardah Ahmed, BS Computer Science, FAST NUCES Karachi
