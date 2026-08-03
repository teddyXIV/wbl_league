# WPBL Fantasy League

A static fantasy league dashboard built in a single HTML file for the inaugural WPBL season.

## Overview

`fantasy_page.html` is a self-contained interactive page that lets 8 managers:

- draft players in a snake-style draft
- build and view team rosters
- browse the real season schedule
- track weekly head-to-head matchup outcomes and standings

The page uses plain HTML, CSS, and JavaScript, with no external build step.

## Features

- Draft board with player search, position filter, and real-team filter
- Team name editing for each manager
- Persistent draft state using browser storage
- Roster display for all 8 fantasy managers
- Real WPBL schedule table for the inaugural season
- Weekly matchup tracker with clickable winner selection
- Standings leaderboard built from match results

## How to Use

1. Open `fantasy_page.html` in a web browser.
2. Use the `Draft` tab to choose players for each team in order.
3. Rename managers by editing the team name fields.
4. Visit the `Rosters` tab to review each fantasy roster.
5. View the real `Schedule` tab for game dates and opponents.
6. Use `Matchups` to record weekly winners and see standings.

## Notes

- The draft is a snake draft for 8 managers with 12 roster spots each.
- Player data and schedule data are stored directly in the HTML file.
- State is saved locally in browser storage so progress persists on reload.

## File

- `fantasy_page.html` — single-file fantasy league interface

## License

Use freely for demonstration, practice, or local league planning.