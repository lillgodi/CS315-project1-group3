#CS 315, Project 1, S1-Group 3 
CS315 project analyzing the effect of liking a video on Tiktok on the testing recommendation algorithm.

By: Adelle, Amy, Brooke, Lillie, Rachel, Soo

## file: PageTikTok.py
Main code?
##file: test_active.py
Function that was called for all active experiments (liked videos based on hashtags defined in main code)
##file: test_control.py
Function that was called for all control experiments
##file: proj1_analysis.ipynb
Common file that contains all the code used for data analysis—parsing and graphing data.
## folder: Data
Contains all the data that was collected over the course of this experiment
Some naming conventions taken:
```
{scenario_num}_{username}_{current_time}_{filename}
```
  - Scenario Num
    - "-1" - control experiment
    - Between 1-6 - active experiment, each number corresponds to a persona
      - 1 = Amy (Gaming)
      - 2 = Rachel (K-Pop)
      - 3 = Lillie (Cooking)
      - 4 = Soo (Makeup)
      - 5 = Adelle (Sports)
      - 6 = Brooke (Art)
  - Username
      - Amy = AH, Rachel = RX, Lillie = LG, Soo = SL, Adelle = AW, Brooke = BB
  - Filename
    - liked videos (videos that were liked)
    - all videos (data that was scrolled through)
    
##folder: data_individual
Contains the data for each individual in subfolders.
