# women-t20i-cricket-data-analysis
To analyze the performance trends of the Indian Women’s Cricket Team in T20 Internationals and identify key factors that influence match outcomes.

### 📊 Dataset

- Source: Cricsheet (Open-source cricket data repository)
- Format: JSON (converted to structured CSV)
- Total T20I Matches Analyzed: 1802
- Ball-by-ball Records: 4lac+
- Time Span: 2016 – 20125

## 🔎 Key Questions Answered

- What factors influence match outcomes?
- Does toss decision impact win probability?
- Which players perform better in winning matches?
- Who are the most impactful batters and bowlers?
- How does performance vary across match phases?


### 📂 Notebook Overview
#### 🟢 01_json_to_csv.ipynb

- Converts raw JSON match files (from Cricsheet) into structured CSV datasets.
- Extracts match-level and ball-by-ball data for further analysis.

#### 🟢 02_feature_engineering.ipynb

Enhances match-level dataset by creating derived features such as:

- Match result classification (Win/Loss)
- Home/Away indicator
- Opponent extraction

Prepares data for analytical modeling.

#### 🟢 03_eda.ipynb

Performs exploratory data analysis on match-level data to identify:

- Win trends
- Toss impact
- Venue patterns

Opposition performance
Provides high-level performance insights.

#### 🟢 04_ball_by_ball_analysis.ipynb

Conducts delivery-level performance analysis including:

- Batting metrics (Strike Rate, Boundary %, Dot Ball %)
- Bowling metrics (Economy, Strike Rate, Dot Ball %)

Phase-wise performance (Powerplay, Middle, Death)
Builds the foundation for player-level impact analysis.

#### 🟢 05_player_impact_in_wins.ipynb

Identifies high-impact players specifically in winning matches.
Calculates custom impact scores for batters and bowlers to determine match-winners.

## 📈 Key Insights

- Certain batters show significantly higher strike rates in winning matches.
- Lower economy rates in death overs strongly correlate with match victories.
- Toss decisions have limited impact compared to phase-wise performance.
- A small group of players contribute disproportionately in wins.

Author

Bhavika Mandavkar

bhavikamandavkar111@gmail.com
