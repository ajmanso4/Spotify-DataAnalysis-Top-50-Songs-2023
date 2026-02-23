# Exploratory Data Analysis: Spotify Most Streamed Songs of 2023
Data analysis of Spotify Top-50 streaming dataset using Python (pandas, matplotlib) via Jupyter notebook.
  * Completed Spring 2024.
  * Revamped February 2026.


## Table of Contents:
* Dataset and Source
* Research Questions
* Presentation
  1. Of the top 50 songs streamed in 2023 on spotify, how many songs does each artist have and what percentage of the top 50 do they make up?
       * Top 25 and Top 10
       * Basic Statistics of the Dataset
  3. Which artists have the highest streams per song? One-Hit-Wonder metric!
  4. Within the top 50, do artists with more entries account for more listening volume?
* Evaluation of Visualization
   


## Dataset and Source:
Dataset: Spotify Most Streamed Songs
Source: https://www.kaggle.com/datasets/meeratif/spotify-most-streamed-songs-of-all-time
* Data obtained from Kaggle (from link above).
* Dataset not included in this repository.


## Research Questions:
1. Of the top 50 songs streamed in 2023 on spotify, how many songs does each artist have and what percentage of the top 50 do they make up?
2. Which artists have the highest streams per song? One-Hit-Wonder metric!
3. Within the top 50, do artists with more entries account for more listening volume?

## Presentation:

### 1. Of the top 50 songs streamed in 2023 on spotify, how many songs does each artist have and what percentage of the top 50 do they make up?
<img width="1073" height="786" alt="Screenshot 2026-02-16 at 17 15 10" src="https://github.com/user-attachments/assets/8ccaf74e-8576-4b88-afcd-cad0d76f8d3c" />
^^ As we can see here, Ed Sheeran is the artist with the most songs in the top 50 of Spotify 2023, with 4 songs. In second place lies Post Malone and The Weeknd, with 3 songs each. 

<br>
<br>

#### We can see the top 25 and the top 10 as we zoom in closer:
<img width="886" height="800" alt="Screenshot 2026-02-16 at 18 03 58" src="https://github.com/user-attachments/assets/a6d73539-b50b-48d8-b252-bac546a56c9e" />
<img width="893" height="477" alt="Screenshot 2026-02-16 at 18 04 05" src="https://github.com/user-attachments/assets/390f78b4-8ddd-418b-a0f7-ac8e300fa108" />

<br>
<br>

#### Some basic statistics of the dataset:
* Mean: 2,357,434,145
* Standard deviation: 404,438,639
* Minimum: 1,930,339,344
* Maximum: 3,783,983,806
<img width="526" height="635" alt="Screenshot 2026-02-16 at 21 57 45" src="https://github.com/user-attachments/assets/0bee6182-4ec1-4bb0-b695-be256e2a2915" />

^^ As we can see here, the songs "Shape of You" by Ed Sheeran and B"linding Lights" by The Weeknd are clear outliers when it comes to total streams.

<br>
<br>

### 2. Which artists have the highest streams per song? One-Hit-Wonder metric!
<img width="1090" height="596" alt="Screenshot 2026-02-16 at 22 16 36" src="https://github.com/user-attachments/assets/586e2e73-4611-475b-bea1-649a3c9b8106" />

^^ As we can see, this is a pretty good metric for one hit wonders as we see "Someone You Loved" by Lewis Capaldi, "Dance Monkey" by Tones And I, "STAY" by The Kid Laroi, and "Heat Waves" by Glass Animals on the top of this list. The majority of people on Earth would be able to recognize those songs but the chance the average person could name other songs by them is lower than artists like Dua Lipa or The Weeknd. These are prime examples of "One hit wonder" artists.

Naturally, we see artists on this "One hit wonder" list who are most definitley not one hit wonders such as The Weeknd and Post Malone. Both of them are extreme outliers, as not many artists are able to get billions of streams on more than two songs.

<br>
<br>

### 3. Within the top 50, do artists with more entries account for more listening volume?
<img width="811" height="601" alt="Screenshot 2026-02-16 at 22 06 47" src="https://github.com/user-attachments/assets/de04cf3e-a86d-46b7-96a4-0b5db428f8bb" />

^^ This visualization confirms the relationship between the number of songs an artist has in Spotify's top 50 and their total amount of streams. This is another way to visualize the significant gap between Ed Sheeran, The Weeknd and Post Malone compared to the other artists.


