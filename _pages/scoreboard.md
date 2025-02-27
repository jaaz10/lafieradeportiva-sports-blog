---
title: "Scoreboard"
layout: single
permalink: /scoreboard/
---

<div class="scoreboard-container">
  <div class="results-section">
    <h2>Recent Results</h2>
    <div class="results-grid">
      {% for match in site.data.scoreboard.recent_results %}
        <div class="match-card">
          <div class="match-date">
            {{ match.date | date: "%b %d, %Y" }} | {{ match.competition }}
          </div>
          <div class="match-result">
            <span class="team home-team">{{ match.home_team }}</span>
            <span class="score">{{ match.home_score }} - {{ match.away_score }}</span>
            <span class="team away-team">{{ match.away_team }}</span>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
  
  <div class="fixtures-section">
    <h2>Upcoming Matches</h2>
    <div class="fixtures-grid">
      {% for match in site.data.scoreboard.upcoming_matches %}
        <div class="match-card">
          <div class="match-date">
            {{ match.date | date: "%b %d, %Y" }} | {{ match.time }} | {{ match.competition }}
          </div>
          <div class="match-fixture">
            <span class="team home-team">{{ match.home_team }}</span>
            <span class="vs">vs</span>
            <span class="team away-team">{{ match.away_team }}</span>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</div>

<style>
  .scoreboard-container {
    margin-bottom: 2em;
  }
  
  .results-section, .fixtures-section {
    margin-bottom: 2em;
  }
  
  .results-grid, .fixtures-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1em;
    margin-top: 1em;
  }
  
  .match-card {
    border: 1px solid #e0e0e0;
    border-radius: 5px;
    padding: 1em;
    background-color: #f9f9f9;
  }
  
  .match-date {
    font-size: 0.9em;
    color: #666;
    margin-bottom: 0.5em;
  }
  
  .match-result, .match-fixture {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 1.1em;
  }
  
  .score {
    font-weight: bold;
    padding: 0 0.5em;
  }
  
  .vs {
    font-weight: bold;
    color: #666;
  }
  
  .team {
    max-width: 40%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
</style>
