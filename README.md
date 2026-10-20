# Yahoo Fantasy Football Research & Decision Support

A personal sports analytics and research toolkit leveraging the Yahoo Fantasy Sports API for lineup optimization, waiver wire recommendations, matchup simulations, and pick'em strategy modeling.

## Features
- **Roster & Lineup Analytics**: Analyze historical and projected player scores to suggest optimal weekly starting lineups.
- **Waiver Wire Evaluation**: Identify high-value free agents and waiver priority targets based on target share, snap counts, and upcoming schedules.
- **Pick'em Decision Modeling**: Data-driven win-probability modeling for weekly pick'em leagues.

## Setup
1. Apply for API access on the [Yahoo Developer Network](https://developer.yahoo.com/apps/create/).
2. Obtain your **Client ID** and **Client Secret**.
3. Create a `.env` file (do not commit this file):
   ```env
   YAHOO_CLIENT_ID=your_client_id_here
   YAHOO_CLIENT_SECRET=your_client_secret_here
   YAHOO_REDIRECT_URI=https://localhost:8080
   ```
