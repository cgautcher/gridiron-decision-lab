# Gridiron Decision Lab

A personal sports analytics and research toolkit for fantasy football lineup optimization, waiver wire recommendations, matchup simulations, and pick'em strategy modeling.

## Features
- **Roster & Lineup Analytics**: Analyze historical and projected player scores to suggest optimal weekly starting lineups.
- **Waiver Wire Evaluation**: Identify high-value free agents and waiver priority targets based on target share, snap counts, and upcoming schedules.
- **Pick'em Decision Modeling**: Data-driven win-probability modeling for weekly pick'em leagues.

## Setup
1. Obtain your OAuth2 **Client ID** and **Client Secret**.
2. Create a `.env` file (do not commit this file):
   ```env
   CLIENT_ID=your_client_id_here
   CLIENT_SECRET=your_client_secret_here
   REDIRECT_URI=https://localhost:8080
   ```
