---
layout: single
title: "Welcome to La Fiera Deportiva"
permalink: /welcome/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/welcome-banner.jpg
  actions:
    - label: "Latest News"
      url: "/posts/"
excerpt: "Your ultimate destination for passionate sports coverage"
toc: true
toc_sticky: true
---

<style>
  /* Custom CSS for Welcome Page */
  .welcome-section {
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 30px;
    background: linear-gradient(to right, rgba(0,0,0,0.8), rgba(25,25,40,0.9));
    box-shadow: 0 5px 15px rgba(0,0,0,0.5);
    border-left: 4px solid #ff4d94;
  }
  
  .welcome-title {
    color: #ff4d94;
    font-size: 2.2em;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: 1px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
  }
  
  .welcome-intro {
    font-size: 1.2em;
    line-height: 1.6;
    color: #f8f8f8;
    margin-bottom: 25px;
    border-bottom: 1px solid rgba(255,255,255,0.1);
    padding-bottom: 15px;
  }
  
  .feature-list {
    list-style-type: none;
    padding-left: 0;
  }
  
  .feature-list li {
    padding: 12px 0;
    margin-bottom: 8px;
    padding-left: 35px;
    position: relative;
    font-size: 1.1em;
    color: #e6e6e6;
    transition: transform 0.2s ease;
  }
  
  .feature-list li:before {
    content: "▶";
    color: #00ccff;
    position: absolute;
    left: 5px;
    top: 12px;
    font-size: 0.8em;
  }
  
  .feature-list li:hover {
    transform: translateX(5px);
    color: #ffffff;
  }
  
  .quote-box {
    background: rgba(0, 204, 255, 0.1);
    border-radius: 6px;
    padding: 20px;
    font-style: italic;
    margin: 30px 0;
    box-shadow: inset 0 0 10px rgba(0, 204, 255, 0.2);
  }
  
  .cta-button {
    display: inline-block;
    background: linear-gradient(45deg, #ff4d94, #ff1a75);
    color: white;
    padding: 12px 28px;
    border-radius: 30px;
    font-weight: bold;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 1px;
    margin-top: 20px;
    transition: all 0.3s ease;
    box-shadow: 0 4px 8px rgba(255, 77, 148, 0.3);
  }
  
  .cta-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 7px 15px rgba(255, 77, 148, 0.4);
    background: linear-gradient(45deg, #ff1a75, #ff4d94);
    color: white;
  }
  
  .sports-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    margin: 30px 0;
  }
  
  .sport-card {
    background: rgba(10,10,20,0.7);
    border-radius: 8px;
    overflow: hidden;
    transition: all 0.3s ease;
    border: 1px solid rgba(0, 204, 255, 0.2);
  }
  
  .sport-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
    border-color: rgba(0, 204, 255, 0.5);
  }
  
  .sport-image {
    height: 150px;
    background-size: cover;
    background-position: center;
  }
  
  .sport-content {
    padding: 15px;
  }
  
  .sport-title {
    color: #00ccff;
    margin-top: 0;
    font-size: 1.3em;
  }
</style>

<div class="welcome-section">
  <h1 class="welcome-title">Welcome to La Fiera Deportiva!</h1>
  
  <p class="welcome-intro">Your premier destination for passionate sports coverage, insightful analysis, and engaging commentary. Stay ahead of the game with our expert coverage of major leagues and tournaments around the world.</p>
  
  <div class="quote-box">
    "Sports have the power to change the world. It has the power to inspire, the power to unite people in a way that little else does." - Nelson Mandela
  </div>
  
  <h2 style="color: #00ccff;">What to Expect</h2>
  
  <ul class="feature-list">
    <li>Match previews and post-game analysis with expert insights</li>
    <li>In-depth player profiles and exclusive interviews</li>
    <li>Tactical breakdowns from seasoned analysts</li>
    <li>Statistical analysis and emerging trends in sports</li>
    <li>Transfer news and rumors from reliable sources</li>
    <li>Coverage of major tournaments and special events</li>
  </ul>
  
  <a href="/posts/" class="cta-button">Explore Latest Articles</a>
</div>

<h2 style="color: #ff4d94; margin-top: 40px;">Sports Coverage</h2>

<div class="sports-grid">
  <div class="sport-card">
    <div class="sport-image" style="background-image: url('/assets/images/soccer.jpg');"></div>
    <div class="sport-content">
      <h3 class="sport-title">Soccer</h3>
      <p>Premier League, La Liga, Serie A, Bundesliga, Champions League and more.</p>
    </div>
  </div>
  
  <div class="sport-card">
    <div class="sport-image" style="background-image: url('/assets/images/basketball.jpg');"></div>
    <div class="sport-content">
      <h3 class="sport-title">Basketball</h3>
      <p>NBA, EuroLeague, FIBA tournaments and college basketball.</p>
    </div>
  </div>
  
  <div class="sport-card">
    <div class="sport-image" style="background-image: url('/assets/images/baseball.jpg');"></div>
    <div class="sport-content">
      <h3 class="sport-title">Baseball</h3>
      <p>MLB, international competitions and more.</p>
    </div>
  </div>
</div>

<div class="welcome-section" style="margin-top: 40px;">
  <h2 style="color: #00ccff;">Meet Our Team</h2>
  <p>La Fiera Deportiva brings together a team of passionate sports journalists, former athletes, and analytical experts to deliver the highest quality content to our readers.</p>
  
  <p>Our contributors have experience covering major sporting events including the World Cup, Olympics, Super Bowl, and Champions League finals.</p>
  
  <p>With backgrounds in professional sports, data analysis, and media, our diverse team brings unique perspectives to every story.</p>
  
  <a href="/about/" class="cta-button">About Us</a>
</div>
