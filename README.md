# Predicting the Single Game Win Probability


As a big-time basketball fan who happens to love data science, I am always quite interested if some of the historical game data could be useful for predicting the outcome of the next game. In fact, I did find strong predicted powers from the adavanced statistics provided by basketball-reference.com. For a better viewing experience please visit my []()

Here are something you could find out in this project,

The 4 factors of winning the basketball game,

1. Home Court Advantage
2. Star Player Contribution (Injuries are considered)
3. Player/Team Hotstreaks
4. Team Match-ups

How well does this model predict? Well You can find out yourself.

Here are the actual results of the 11 games played on 2018-02-14. Winning teams are in bold fonts.

| Date       | Home Team             | Home Score | Away Team              | Away Score |
|------------|-----------------------|------------|------------------------|------------|
| 2018-02-14 | **Los Angeles Clippers**  | **129.0**      | Boston Celtics         | 119.0      |
| 2018-02-14 | **Indiana Pacers**        | **108.0**      | Brooklyn Nets          | 103.0      |
| 2018-02-14 | **Toronto Raptors**       | **122.0**      | Chicago Bulls          | 98.0       |
| 2018-02-14 | Atlanta Hawks         | 98.0       | **Detroit Pistons**        | **104.0**      |
| 2018-02-14 | Sacramento Kings      | 91.0       | **Houston Rockets**        | **100.0**      |
| 2018-02-14 | **Oklahoma City Thunder** | **121.0**      | Memphis Grizzlies      | 114.0      |
| 2018-02-14 | Los Angeles Lakers    | 117.0      | **New Orleans Pelicans**   | **139.0**      |
| 2018-02-14 | **Washington Wizards**    | **118.0**      | New York Knicks        | 113.0      |
| 2018-02-14 | **Charlotte Hornets**     | **104.0**      | Orlando Magic          | 102.0      |
| 2018-02-14 | Miami Heat            | 102.0      | **Philadelphia 76ers**     | **104.0**      |
| 2018-02-14 | Golden State Warriors | 117.0      | **Portland Trail Blazers** | **123.0**      |
| 2018-02-14 | Phoenix Suns          | 97.0       | **Utah Jazz**              | **107.0**      |

Here are the predictions

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **LAC**  | **0.521**              |
| Away | BOS  | 0.479              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **IND**  | **0.667**              |
| Away | BRK  | 0.333              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **TOR** | **0.742**              |
| Away | CHI  | 0.258              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | ATL  | 0.436              |
| Away | **DET**  | **0.564**              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | SAC  | 0.248              |
| Away | **HOU**  | **0.752**              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **OKC**  | **0.683**              |
| Away | MEM  | 0.317              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | LAL  | 0.445              |
| Away | **NOP**  | **0.555**              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **WAS**  | **0.733**              |
| Away | NYK  | 0.267              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **CHO**  | **0.537**              |
| Away | ORL  | 0.463              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | MIA  | 0.398              |
| Away | **PHI**  | **0.602**              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | **GSW**  | **0.594**              |
| Away | POR  | 0.406              |

|      | Team | Wining Probability |
|------|------|--------------------|
| Home | PHO  | 0.229              |
| Away | **UTA**  | **0.771**              |

This model successfully predicted correctly the results of 10 games out of 11 games, which is the **Golden State Warriors** losing to the **Portland Trail Blazers** at home
