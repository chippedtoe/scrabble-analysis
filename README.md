# Analysis of Scrabble scores following each OWL word list update.

## Scope
Analysis of Scrabble games held from 1973 to 2017 to assess whether the addition of words to the official Scrabble Official Word List (OWL) affected final player scores. For this analysis, I created a time-series graph of winning and losing scores by player rating, noting that players with ratings over 500 are more experienced than those with ratings under 500 - as determined by the official rules for calculating player rating and ranking by state.

## Results
### Average Winning Scores per Week by Player Rating
<img width="940" height="608" alt="output" src="https://github.com/user-attachments/assets/9bedef01-8a1d-48a4-b96c-d5ca745721c9" />

### Average Losing Scores per Week by Player Rating
<img width="940" height="548" alt="scrabble losing scores" src="https://github.com/user-attachments/assets/f03c5dc9-a01b-44c3-9de6-22a8bc24d0ce" />


## Conclusion
The results show a general increase in scores across levels following each OWL release. Players with higher ratings had a uniform increase, while less experienced players performed more sporadically, indicating that more experienced players probably benefited more from an expanded word list than those with less experience.

It would be interesting to see an analysis of the impact of word difficulty on player scores, but it appears that there isn't a standardized way to assess this. Since current methods of evaluating word difficulty are beyond the scope of this analysis, I will attempt this at a later time. 

## References
1. Curto, P., Mamede, N., & Baptista, J. (2015). Automatic Text Difficulty Classifier—Assisting the
Selection Of Adequate Reading Materials For European Portuguese Teaching: Proceedings
of the 7th International Conference on Computer Supported Education, 36–44.
https://doi.org/10.5220/0005428300360044
2. Data/scrabble_games.csv at master · fivethirtyeight/data. (2017, April 18). GitHub. Retrieved
February 11, 2022, from https://github.com/fivethirtyeight/data
3. NASPA: Top Ratings by State and Province. (n.d.). Retrieved February 27, 2022, from
http://scrabbleplayers.org/ratings/bystate.html
4. NASPA Zyzzyva Download—NASPAWiki. (n.d.). Retrieved February 11, 2022, from
http://www.scrabbleplayers.org/w/NASPA_Zyzzyva_Download
5. Official Tournament and Club Word List—NASPAWiki. (n.d.). Retrieved February 11, 2022, from
http://scrabbleplayers.org/w/Official_Tournament_and_Club_Word_List
6. Rating system overview—NASPAWiki. (n.d.). Retrieved February 27, 2022, from
http://scrabbleplayers.org/w/Rating_system_overview
7. Roeder, O. (2017, April 19). How ‘Qi’ And ‘Za’ Changed Scrabble. FiveThirtyEight.
https://fivethirtyeight.com/features/how-qi-and-za-changed-scrabble/
8. Zhang, S., Jia, Q., Shen, L., & Zhao, Y. (2020). Automatic Classification and Comparison of
Words by Difficulty. In H. Yang, K. Pasupa, A. C.-S. Leung, J. T. Kwok, J. H. Chan, & I.
King (Eds.), Neural Information Processing (pp. 635–642). Springer International
Publishing. https://doi.org/10.1007/978-3-030-63820-7_72
