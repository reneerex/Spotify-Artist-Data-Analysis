<h1>🎵 Spotify Artist Dataset Analysis</h1>

<p>
  This project analyzes metadata about music artists on Spotify, focusing on their <b>popularity</b>, <b>followers</b>, and <b>genre diversity</b>. The dataset is sourced from Kaggle and includes artist-level information like genre tags and engagement metrics.
</p>

<hr>

<h2>1. 📊 Methodology</h2>
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/free-whiteboard-online/Free-Erasorio-Alternative-for-Collaborative-Design@734c33d36ba395523760f940cabaf09cc525a03b/uploads/2025-06-20T01-52-08-142Z-fltiityuj.png" />
</p>


<hr>

<h2>2. 📋 Description</h2>
<ul>
  <li>📁 <b>Dataset:</b> <a href="https://www.kaggle.com/datasets/nimishasen27/spotify-dataset?select=artists.csv" target="_blank">Spotify Artist Dataset (Kaggle)</a></li>
  <li>🔢 <b>Total Artists:</b> 110,349</li>
  <li>🧹 <b>Preprocessing:</b> Removed duplicates & nulls, converted genre strings to lists</li>
  <li>📊 <b>Key Columns:</b>
    <ul>
      <li><code>id</code>: Unique artist ID</li>
      <li><code>name</code>: Artist name</li>
      <li><code>followers</code>: Number of Spotify followers</li>
      <li><code>genres</code>: List of associated genres</li>
      <li><code>popularity</code>: Score (0–100)</li>
    </ul>
  </li>
</ul>

<hr>

<h2>3. 🔁 Input / Output Examples</h2>

<table>
  <thead>
    <tr>
      <th>Query</th>
      <th>Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Top Followed Artist</td>
      <td>Ed Sheeran (78M followers)</td>
    </tr>
    <tr>
      <td>Top Popular Artist</td>
      <td>Ed Sheeran (Popularity 100)</td>
    </tr>
    <tr>
      <td>Most Common Genre</td>
      <td>Pop</td>
    </tr>
    <tr>
      <td>Genre with Highest Avg. Popularity</td>
      <td>Trap Metal Italiana (Popularity ~74)</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>4. 📊 Visual Summary</h2>
<ul>
  <li>📉 <b>Popularity Distribution:</b> Majority of artists have a popularity score of 0</li>
  <li>📈 <b>Followers vs Popularity:</b> Positive correlation, but not linear</li>
  <li>🎧 <b>Genre Spread:</b> Highly diverse with long tail of niche genres</li>
</ul>
