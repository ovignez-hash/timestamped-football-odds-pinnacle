# FREE SAMPLE - 20 matches

This sample is an exact copy of the full product: same files, same columns, same formats. Only the number of matches differs.

| Match_ID | Code | Season | Stage | Date | Match | 90' |
|---|---|---|---|---|---|---|
| 11025052 | ENG_CH | 2025/26 | Regular Season | 2026-05-02 | Preston - Southampton | 1-3 |
| 11833944 | ENG_CH | 2025/26 | Play-Offs | 2026-05-12 | Southampton - Middlesbrough | 1-1 |
| 12101722 | ENG_CH | 2026/27 | Regular Season | 2026-09-15 | Middlesbrough - Millwall | 2-2 |
| 12101724 | ENG_CH | 2026/27 | Regular Season | 2026-09-15 | Bristol City - Lincoln City | 0-1 |
| 10856112 | ENG_PL | 2025/26 | Regular Season | 2026-05-24 | West Ham - Leeds | 3-0 |
| 11889805 | ESP_LL | 2025/26 | Regular Season | 2026-05-24 | Villarreal - Atletico Madrid | 5-1 |
| 13087014 | ESP_LL | 2026/27 | Regular Season | 2026-09-15 | Rayo Vallecano - Espanyol | 2-1 |
| 13086836 | ESP_LL | 2026/27 | Regular Season | 2026-09-15 | CD Alaves - Valencia | 0-1 |
| 13086922 | ESP_LL | 2026/27 | Regular Season | 2026-09-15 | Elche - Real Madrid | 2-3 |
| 10926111 | ESP_SEG | 2025/26 | Regular Season | 2026-05-31 | Leganes - Mirandes | 1-0 |
| 11883122 | FRA_L1 | 2025/26 | Play-Offs | 2026-05-15 | St Etienne - Rodez Aveyron | 0-0 |
| 10176815 | FRA_L1 | 2025/26 | Regular Season | 2026-05-17 | Marseille - Rennes | 3-1 |
| 10578703 | FRA_L2 | 2025/26 | Regular Season | 2026-05-09 | Red Star FC 93 - Montpellier | 1-1 |
| 10702928 | GER_BL | 2025/26 | Regular Season | 2026-05-16 | Werder Bremen - Borussia Dortmund | 0-2 |
| 11906693 | GER_BL | 2025/26 | Play-Offs | 2026-05-25 | Paderborn - Wolfsburg | 1-1 |
| 10576530 | GER_BL2 | 2025/26 | Regular Season | 2026-05-17 | Darmstadt - Paderborn | 0-2 |
| 10909720 | ITA_SA | 2025/26 | Regular Season | 2026-05-24 | Torino - Juventus | 2-2 |
| 10850718 | ITA_SB | 2025/26 | Regular Season | 2026-05-08 | AC Reggiana - Sampdoria | 1-0 |
| 11879281 | POR_PL | 2025/26 | Regular Season | 2026-05-16 | Estoril - Benfica | 1-3 |
| 11884383 | POR_SL | 2025/26 | Regular Season | 2026-05-17 | Portimonense - SC Farense | 1-0 |

Full product (all 45,554 matches) and contact: contact@oliviersportsdata.com

---

# Big 6 Europe Premium - Football Odds, In-Play Ticks & Full Match Layer (2016-2026)

45,554 finished matches from the top two divisions of England, Spain, Italy, Germany, France and Portugal,
2016-08-28 to 2026-09-28. Every recorded price update from 5 named bookmakers (Bet365 on all 8 markets),
pre-match and in-play, with the score and the match clock given by the bookmaker on in-play quotes. Opening and
closing prices with the exact time of each, per bookmaker and market. Match sheet, team statistics, lineups,
events and minute-by-minute statistics. All tables join on `Match_ID`.

## At a glance

|  |  |
|---|---|
| Matches | 45,554 (45,243 regular season, 311 play-offs) |
| Competitions | 12 (6 countries x 2 divisions) |
| Seasons | 2016/17 to 2026/27 (the last one up to 2026-09-30) |
| Bookmakers | Bet365, Pinnacle, Unibet, Betfair (Sportsbook), Betsson - always named, never aggregated |
| Markets | FT 1X2, FT Asian handicap, FT total goals, FT total corners, HT 1X2, HT Asian handicap, HT total goals, HT total corners |
| Timestamped price updates | 87,379,474 |
| Events | 1,547,381 |
| Lineup rows | 1,775,335 |
| Minute-by-minute statistics | 11,533,683 |

## Files

| File | Rows | One row per | Format |
|---|---|---|---|
| Big6_Matches.csv / .xlsx | 45,554 | match | CSV + XLSX |
| Big6_Opening_Closing_Odds.csv / .xlsx | 45,554 | match (opening and closing price + time, per bookmaker and market) | CSV + XLSX |
| Big6_Team_Stats.csv / .xlsx | 91,108 | match x team | CSV + XLSX |
| odds_timestamped/Big6_Odds_Timestamped_<CODE>.csv.gz | 87,379,474 | price update (bookmaker x market x time) | 12 gzip CSV |
| events/Big6_Events_<CODE>.csv.gz | 1,547,381 | match event | 12 gzip CSV |
| lineups/Big6_Lineups_<CODE>.csv.gz | 1,775,335 | player in a match squad | 12 gzip CSV |
| minute_stats/Big6_Minute_Stats_<CODE>.csv.gz | 11,533,683 | statistic x team x minute | 12 gzip CSV |

Load in pandas: `pd.read_csv("Big6_Matches.csv")` and `pd.read_csv("events/Big6_Events_ENG_PL.csv.gz")`
(gzip is read directly). Comma-separated, UTF-8 with BOM, "." decimals. The XLSX workbooks are typed:
text stays text, numbers are numbers, header frozen, filters on.

## Competitions and coverage

| Code | Competition | Country | Div. | Matches | Seasons | Lineups | Minute stats | Events |
|---|---|---|---|---|---|---|---|---|
| ENG_PL | Premier League | England | 1 | 3,822 | 2016/17 to 2026/27 | 99.9 % | 75.1 % | 99.4 % |
| ENG_CH | Championship | England | 2 | 5,605 | 2016/17 to 2026/27 | 98.6 % | 75.1 % | 99.4 % |
| ESP_LL | La Liga | Spain | 1 | 3,853 | 2016/17 to 2026/27 | 99.9 % | 74.3 % | 99.3 % |
| ESP_SEG | Segunda Division | Spain | 2 | 4,728 | 2016/17 to 2026/27 | 99.7 % | 74.5 % | 99.3 % |
| ITA_SA | Serie A | Italy | 1 | 3,837 | 2016/17 to 2026/27 | 99.9 % | 74.6 % | 99.5 % |
| ITA_SB | Serie B | Italy | 2 | 4,062 | 2016/17 to 2026/27 | 100.0 % | 72.9 % | 99.0 % |
| GER_BL | Bundesliga | Germany | 1 | 3,108 | 2016/17 to 2026/27 | 100.0 % | 74.1 % | 99.5 % |
| GER_BL2 | 2. Bundesliga | Germany | 2 | 3,107 | 2016/17 to 2026/27 | 100.0 % | 74.4 % | 99.5 % |
| FRA_L1 | Ligue 1 | France | 1 | 3,512 | 2016/17 to 2026/27 | 99.9 % | 71.8 % | 99.4 % |
| FRA_L2 | Ligue 2 | France | 2 | 3,585 | 2016/17 to 2026/27 | 75.7 % | 72.0 % | 99.8 % |
| POR_PL | Primeira Liga | Portugal | 1 | 3,112 | 2016/17 to 2026/27 | 99.9 % | 74.5 % | 99.1 % |
| POR_SL | Liga Portugal 2 | Portugal | 2 | 3,223 | 2016/17 to 2026/27 | 99.0 % | 69.9 % | 99.4 % |
| **Total** |  |  |  | **45,554** | 2016/17 to 2026/27 | 97.8 % | 73.7 % | 99.4 % |

Lineups = both starting elevens present. Minute stats = at least one minute-by-minute statistic.
Events = at least one event in the source timeline.

### Coverage by bookmaker (FT 1X2 closing price present)

| Bookmaker | Matches with a FT 1X2 close | Coverage | From season | Markets (closing prices present) |
|---|---|---|---|---|
| Bet365 | 45,497 | 99.9 % | 2016/17 | FT_1X2, FT_Asian_Handicap, FT_Total_Goals, HT_Total_Goals, HT_Total_Corners, HT_1X2, FT_Total_Corners, HT_Asian_Handicap |
| Pinnacle | 34,004 | 74.6 % | 2018/19 | FT_Total_Goals, FT_1X2, FT_Asian_Handicap |
| Unibet | 41,556 | 91.2 % | 2017/18 | FT_1X2, FT_Total_Goals |
| Betfair (Sportsbook) | 8,699 | 19.1 % | 2023/24 | FT_1X2 |
| Betsson | 17,226 | 37.8 % | 2022/23 | FT_1X2, FT_Total_Goals |

### Coverage by season (share of matches with a FT 1X2 closing price)

| Season | Matches | Bet365 | Pinnacle | Unibet | Betfair | Betsson |
|---|---|---|---|---|---|---|
| 2016/17 | 4,469 | 100 % | 0 % | 17 % | 0 % | 0 % |
| 2017/18 | 4,705 | 100 % | 0 % | 100 % | 0 % | 0 % |
| 2018/19 | 4,499 | 99 % | 83 % | 100 % | 0 % | 0 % |
| 2019/20 | 4,252 | 100 % | 100 % | 100 % | 0 % | 0 % |
| 2020/21 | 4,546 | 100 % | 100 % | 100 % | 0 % | 0 % |
| 2021/22 | 4,553 | 100 % | 100 % | 100 % | 0 % | 0 % |
| 2022/23 | 4,546 | 100 % | 100 % | 100 % | 0 % | 99 % |
| 2023/24 | 4,476 | 100 % | 69 % | 100 % | 72 % | 98 % |
| 2024/25 | 4,403 | 100 % | 100 % | 99 % | 24 % | 90 % |
| 2025/26 | 4,402 | 100 % | 100 % | 100 % | 89 % | 91 % |
| 2026/27 | 703 | 100 % | 73 % | 73 % | 74 % | 49 % |

## Column dictionary

### Big6_Matches

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). The key shared by every table. |
| `Competition_Code` | ENG_PL, ENG_CH, ESP_LL, ESP_SEG, ITA_SA, ITA_SB, GER_BL, GER_BL2, FRA_L1, FRA_L2, POR_PL, POR_SL. |
| `Country / Competition / Division` | Country, competition name, division (1 or 2). |
| `Season` | 2016/17 form (stays text in Excel). Seasons are cut on the first matchday, not on a calendar date. |
| `Stage` | Regular Season or Play-Offs (promotion, relegation and play-out ties). |
| `Round` | Matchday number as given by the source (play-off rounds use the source's own numbering). |
| `Kickoff_UTC / Kickoff_Epoch` | Scheduled kickoff, ISO 8601 UTC and Unix seconds. |
| `Home_Team_ID / Home_Team / Away_Team_ID / Away_Team` | Source team id (text) and team name. |
| `Home_Goals_HT / Away_Goals_HT` | Half-time score. |
| `Home_Goals_90 / Away_Goals_90` | Score after 90 minutes plus added time: the score 1X2, handicap and total markets settle on. |
| `Result_90` | H, D or A after 90 minutes. |
| `Extra_Time` | 1 when extra time was played, else 0. |
| `Home_Goals_AET / Away_Goals_AET` | Score after extra time (cumulative), only when Extra_Time = 1. |
| `Home_Penalties / Away_Penalties` | Penalty shoot-out score. |
| `Home_Aggregate / Away_Aggregate` | Aggregate score of a two-legged tie, when the source gives it. |
| `Home_League_Position / Away_League_Position` | League positions given by the source for the match. |
| `Home_Formation / Away_Formation` | Formation as digits: 4231 = 4-2-3-1, 442 = 4-4-2. |
| `Home_Manager / Away_Manager / Referee / Referee_Country` | Names as given; country as a 2-letter code. |
| `Stadium / Stadium_City / Stadium_Country / Stadium_Capacity` | Venue as given by the source. |
| `Stadium_Latitude / Stadium_Longitude` | Venue coordinates (decimal degrees). |
| `Has_Lineups / Has_Minute_Stats / Has_Match_Stats` | 1 when the table holds both starting elevens / minute-by-minute statistics / team statistics for the match. |

### Big6_Opening_Closing_Odds

| Column | Meaning |
|---|---|
| `Match_ID ... Away_Penalties` | Identity and result of the match, copied from Big6_Matches so the file stands alone. |
| `{Book}_{Market}_Open_*` | Opening: first valid pre-match quote of that bookmaker and market (no suspended, empty, out-of-range or unreadable price; valid line for handicaps and totals). |
| `{Book}_{Market}_Close_*` | Closing: last valid pre-match quote. Never an in-play quote (see Pre-match, in-play and closing). |
| `*_Home / *_Draw / *_Away` | 1X2: home win, draw, away win. Asian handicap: home side and away side. |
| `*_Line` | Handicap line of the HOME team, or total line, as a decimal; split lines averaged (0.0,-0.5 -> -0.25). |
| `*_Over / *_Under` | Over and Under the line. |
| `*_Open_Time / *_Close_Time` | Time of the opening / closing quote, ISO 8601 UTC. |
| `Empty cells` | No valid pre-match quote for that bookmaker and market on that match. |

### Big6_Team_Stats

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Two rows per match: Home and Away. |
| `Goals ... Action_Areas` | Full-match totals as given by the source (29 statistics, including Possession_Pct, Shots_On_Target, Dangerous_Attacks, Corners, Corners_HT, Yellow_Cards, Red_Cards, xG). Empty when the source does not give that statistic for the match. |

### Big6_Odds_Timestamped_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). |
| `Book` | Bet365, Pinnacle, Unibet, Betfair (Sportsbook), Betsson. |
| `Market` | FT_1X2, FT_Asian_Handicap, FT_Total_Goals, FT_Total_Corners, HT_1X2, HT_Asian_Handicap, HT_Total_Goals, HT_Total_Corners (HT = first half). |
| `Phase` | Pre-match or In-play (rule below). |
| `Timestamp_UTC / Epoch` | Time the price was recorded, ISO 8601 UTC and Unix seconds. |
| `Minute / Second` | Match clock given by the bookmaker at that quote (integers). Unibet and Betsson give mm:ss; empty pre-match and when the bookmaker gives a non-numeric clock (Pinnacle '1H47'', 'HT'). |
| `Score_Home / Score_Away` | Score at that quote (integers); empty pre-match and when the bookmaker sends a partial score. |
| `Corners_Home / Corners_Away` | Corner count at that quote, corner markets only. |
| `Line` | Handicap line of the HOME team, or total line (decimal). Empty for 1X2. |
| `Price_Home / Price_Draw / Price_Away / Price_Over / Price_Under` | Decimal prices. Empty when suspended, absent, out of range or unreadable. |
| `Suspended` | 1 when the bookmaker showed the market suspended at that quote, else 0. |

### Big6_Events_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Event_Order` | Source event id; position of the event in the source timeline (gaps = summary lines not delivered). |
| `Minute / Added_Time` | Match minute and added time (90+3 -> 90 and 3), integers. |
| `Event_Type` | Goal, Assist, Yellow Card, Red Card, Substitution, Corner, Shot On Target, Shot Off Target, Offside, Race To Corners, Missed Penalty, Penalty Shootout Scored, Penalty Shootout Missed. |
| `Type_Ordinal` | The source's match-wide count for that event type (1st, 2nd...); a team's kick number in a shoot-out. |
| `Team_Side / Team` | Home or Away, and the team name as written in the event. |
| `Player / Player_2` | Substitution: player on / player off. Goal: scorer / assist provider. |
| `Race_Target` | N in 'Race to N corners'. |
| `Detail` | Goal type: Shot, Header, Penalty, Own Goal, Free Kick. |
| `Extra_Time` | 1 for events the source marks as extra time. |

### Big6_Lineups_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Match and team. |
| `Starter` | 1 = starting eleven, 0 = substitute. |
| `Lineup_Order` | Order in the source's team sheet. |
| `Player_ID / Player / Player_Country` | Source player id (text), name, 2-letter country code. |
| `Shirt_Number` | Shirt number. |
| `Position / Position_Group` | Position as given (Goalkeeper, Defender, Midfielder, Forward and detailed roles) and its group. |

### Big6_Minute_Stats_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Stat` | Match, team side and statistic (Attacks, Dangerous_Attacks, Possession_Pct, Shots_On_Target, Corners, Goals...). |
| `Minute / Value` | Match minute and the running value at that minute: cumulative count, or running percentage for Possession_Pct, Passing_Accuracy and Crossing_Accuracy. |
| `Timestamp_UTC / Epoch` | Time the value was recorded. |

## Rules applied to every cell

- **Times** are ISO 8601 UTC with the T and the Z (`2026-09-20T15:30:00Z`), plus a Unix epoch column.
  Excel and LibreOffice keep this form as text: it is never converted into a local date.
- **No cell that a spreadsheet can rewrite.** Scores, minutes and shoot-outs are separate integer columns
  (never "1-0", "90+2" or "73:02"). Formations are digits: `4231` means 4-2-3-1, `442` means 4-4-2
  ("4-4-2" in a cell becomes 04/04/2002 in French Excel). Handicap lines are decimals (`-0.25`, never "0.0,-0.5").
  Leading "-", "+", "=" or "@" are removed from names.
- Every cell of every file was audited against these Excel conversion patterns at write time: **0 risky cells**.
  A sample of every table was also opened in LibreOffice (English and French locales) and read back: 0 conversions.
- **Empty cell = absent from the source.** Nothing is imputed, interpolated or averaged across bookmakers.
- A suspended price ("-") is an empty cell with `Suspended = 1`: kept, not deleted.

## Pre-match, in-play and closing

- A quote is **Pre-match** when it carries no score AND was recorded before the kickoff anchor K. Everything
  else is **In-play**.
- **K** is the scheduled kickoff. When Bet365's live clock (tick time minus its minute, minutes 1 to 15) shows
  that the match started before the scheduled time (the source sometimes schedules a match too late), K is that
  start minus 2 minutes. Without a Bet365 live clock, K is also bounded by the first quote
  that carries a score, minus 2 minutes. K is never later than the scheduled kickoff, so a delayed kickoff
  closes the market at the scheduled time.
- **Opening** = first valid pre-match quote, **Closing** = last valid pre-match quote, per bookmaker and market,
  each with its own time. A closing price is never an in-play price.
- The source records a quote when the price changes. A `_Close_Time` hours before kickoff therefore means the
  price did not move after that time, or that the bookmaker stopped quoting the market: the data cannot tell the
  two apart. Closing times differ widely between bookmakers and markets: compare the `_Close_Time` columns before
  comparing closing prices across books.

## Data integrity: what was corrected, and why

Each decision below is written in the build code with its evidence; the build stops if a new unresolved case appears.

**17 source events removed** (the source keeps some postponed, abandoned or duplicated fixtures as
"finished"):

| Source event | Competition | Reason | Evidence |
|---|---|---|---|
| 115280 | ENG_CH | abandoned, then replayed in full | Reading - Fulham, 2016-12-30: stopped at half-time (0-0); replayed 2017-01-24 (129171, 1-0) |
| 457451 | ESP_SEG | postponed - no match data under this id | Gimnastic - Barcelona B, 2017-10-01: no match data; played 2017-11-01 (502458) |
| 11047325 | ESP_SEG | continuation of an interrupted match | second half of AD Ceuta - Almeria played 2025-11-26; match kept as 10209353 |
| 2442635 | ESP_SEG | continuation of an interrupted match | second half of Rayo Vallecano - Albacete played 2020-06-10; match kept as 1703299 |
| 126326 | FRA_L2 | postponed - no match data under this id | Strasbourg - Tours, 2017-01-20: no match data; played 2017-02-21 (160029) |
| 326159 | GER_BL2 | abandoned, then replayed in full | Heidenheim - Erzgebirge Aue, 2017-07-30: stopped around 12' (0-0); replayed 2017-08-09 (370566, 2-1) |
| 1613721 | ITA_SA | home/away reversed by the source | Atalanta - Sassuolo, 2019-05-26, stored the wrong way round (Sassuolo at home) while Pinnacle prices Atalanta at home; Sassuolo - Atalanta already exists (849732) |
| 8122701 | ITA_SA | continuation of an interrupted match | last minutes of Udinese - Roma played 2024-04-25; match kept as 7129975 |
| 890276 | ITA_SB | abandoned, then replayed in full | Lecce - Ascoli, 2019-02-01: stopped before half-time (0-0 at 43'); replayed 2019-03-23 (1520963) |
| 258727 | ITA_SB | postponed - no match data under this id | Ascoli - Carpi dated 2017-03-01: no events, no stats; played 2017-04-01 (236292) |
| 7173 | ITA_SB | postponed - no match data under this id | Ascoli - Cesena, 2016-09-04: no match data; played 2016-09-27 (30248) |
| 2900000 | ITA_SB | continuation of an interrupted match | end of Venezia - Empoli played 2020-11-01; match kept as 2730854 |
| 467799 | ITA_SB | continuation of an interrupted match | end of Ternana - Brescia played 2017-10-03; match kept as 386939 |
| 60722 | ITA_SB | continuation of an interrupted match | second id created during Ascoli - Salernitana, 2016-10-25; match kept as 58677 |
| 570613 | POR_PL | continuation of an interrupted match | second half of Feirense - Vitoria Setubal played 2017-12-17; match kept as 337634 |
| 637525 | POR_PL | continuation of an interrupted match | second half of Estoril - FC Porto played 2018-02-21; match kept as 341815 |
| 298463 | POR_SL | not a match of this competition | Merelinense - Academico Viseu, 2017-06-03: Merelinense is not a LigaPro 2016/17 club |

**Interrupted matches completed on a later date** are kept once, under their original id, with the pre-match
market of the original kickoff and the final score. Their in-play quotes, events and minute statistics stop at
the interruption:

| Match kept | Match | Interrupted on | Completed on | Note |
|---|---|---|---|---|
| 1703299 | Rayo Vallecano - Albacete | 2019-12-15 | 2020-06-10 | stopped at half-time, second half played six months later |
| 7129975 | Udinese - Roma | 2024-04-14 | 2024-04-25 | stopped in the second half, last minutes played eleven days later |
| 341815 | Estoril - FC Porto | 2018-01-15 | 2018-02-21 | stopped at half-time, second half played five weeks later |
| 10209353 | AD Ceuta FC - Almeria | 2025-11-09 | 2025-11-26 | stopped at half-time; final score read on the continuation |
| 337634 | Feirense - Vitoria Setubal | 2017-12-16 | 2017-12-17 | stopped at half-time, second half played the next day |
| 2730854 | Venezia - Empoli | 2020-10-31 | 2020-11-01 | stopped in the second half, finished the next day |
| 386939 | Ternana - Brescia | 2017-09-19 | 2017-10-03 | stopped in the first half; the source dates this match 2017-10-03 |
| 58677 | Ascoli - Salernitana | 2016-10-25 | 2016-10-25 | not interrupted: the source split its live feed into two ids |

**Play-offs.** 311 play-off matches (promotion, relegation and play-out ties).
164 of them were filed by the source under the regular season and are reclassified: a regular
season meets each home/away pairing once, so a repeat of the pairing after the last full matchday is a play-off.
The French Ligue 1 file also holds the Ligue 2 promotion play-off path, as filed by the source.
Extra time is recorded for 21 matches and penalty shoot-outs for 15 (some Ligue 2 play-offs go straight
to penalties after 90 minutes).

**Team identity.** In 4 Ligue 2 2016/17 matches the source names RC Lens "Wasquehal" (wrong team id). Corrected
to Lens (id 9899): coach, stadium (Bollaert-Delelis) and event texts all say Lens.

**Half-time scores.** 3 half-time scores were higher than the final score (the source counted a goal it
later cancelled): left empty rather than wrong.

**Home / away orientation.** A bookmaker sometimes lists a fixture with the two teams the other way round. Every price series is aligned on the match's home and away teams: 1X2 and Asian handicap, full time and half time, with the handicap line and the live score turned with it (4 match-bookmaker series turned: Unibet 2, Pinnacle 2).

**37 fixtures are not in the tables** because the source never marked them as finished (18 result never confirmed by the source; 10 result decided by the federation; 6 abandoned; 2 removed by the source; 1 interrupted). They are listed so that a gap in a season is never silent:

| Source event | League | Date | Home | Away | Score shown | Status |
|---|---|---|---|---|---|---|
| 2456255 | ESP_SEG | 2019-06-09 | Rayo Majadahonda | Reus Deportiu | 1-0 | result decided by the federation |
| 2696802 | ESP_SEG | 2020-10-03 | Alcorcon | Real Zaragoza | 0-3 | result decided by the federation |
| 96905 | FRA_L1 | 2016-12-03 | Metz | Lyon | 1-0 | abandoned |
| 189809 | FRA_L1 | 2017-04-16 | SC Bastia | Lyon | 0-0 | result decided by the federation |
| 336655 | FRA_L1 | 2017-09-30 | Amiens | Lille | 0-1 | abandoned |
| 1685748 | FRA_L1 | 2019-07-10 | Dijon | St Etienne |  | result never confirmed by the source |
| 1685749 | FRA_L1 | 2019-07-10 | Marseille | Reims |  | result never confirmed by the source |
| 1685750 | FRA_L1 | 2019-07-10 | Nice | Amiens |  | result never confirmed by the source |
| 1685751 | FRA_L1 | 2019-07-10 | Strasbourg | Metz |  | result never confirmed by the source |
| 1685752 | FRA_L1 | 2019-07-10 | Montpellier | Rennes |  | result never confirmed by the source |
| 1685753 | FRA_L1 | 2019-07-10 | Angers | Bordeaux |  | result never confirmed by the source |
| 1685754 | FRA_L1 | 2019-07-10 | Lille | Nantes |  | result never confirmed by the source |
| 1685755 | FRA_L1 | 2019-07-10 | Brest | Toulouse |  | result never confirmed by the source |
| 1685756 | FRA_L1 | 2019-07-10 | Monaco | Lyon |  | result never confirmed by the source |
| 10176991 | FRA_L1 | 2026-05-17 | Nantes | Toulouse | 0-0 | abandoned |
| 1584743 | FRA_L2 | 2019-05-02 | Niort | Lorient |  | result never confirmed by the source |
| 2528042 | FRA_L2 | 2020-12-22 | Niort | Valenciennes | 0-3 | result decided by the federation |
| 5608149 | FRA_L2 | 2023-06-02 | Bordeaux | Rodez Aveyron | 0-1 | result decided by the federation |
| 8384536 | FRA_L2 | 2024-10-26 | AC Ajaccio | SC Bastia | 0-0 | abandoned |
| 10189127 | FRA_L2 | 2025-08-09 | AC Ajaccio | SC Bastia |  | removed by the source |
| 11841481 | FRA_L2 | 2026-05-09 | SC Bastia | Le Mans | - | result decided by the federation |
| 2244816 | GER_BL | 2020-03-14 | Union Berlin | Bayern Munich |  | result never confirmed by the source |
| 8451644 | GER_BL | 2024-12-14 | Union Berlin | Bochum | 0-2 | result decided by the federation |
| 487433 | GER_BL2 | 2018-01-24 | Darmstadt | Kaiserslautern | 0-0 | abandoned |
| 2743490 | GER_BL2 | 2020-09-19 | Heidenheim | Eintracht Braunschweig |  | result never confirmed by the source |
| 2743491 | GER_BL2 | 2020-09-19 | Greuther Furth | VfL Osnabruck |  | result never confirmed by the source |
| 2743492 | GER_BL2 | 2020-09-19 | Holstein Kiel | Paderborn |  | result never confirmed by the source |
| 2743560 | GER_BL2 | 2020-09-19 | Bochum | St Pauli |  | result never confirmed by the source |
| 2704533 | ITA_SA | 2020-09-19 | Verona | Roma | 3-0 | result decided by the federation |
| 6678858 | ITA_SB | 2023-06-01 | Brescia | Cosenza | 0-3 | result decided by the federation |
| 9953789 | ITA_SB | 2025-05-19 | Salernitana | Frosinone |  | removed by the source |
| 10092286 | ITA_SB | 2025-06-22 | Salernitana | Sampdoria | 0-3 | result decided by the federation |
| 8468696 | POR_PL | 2025-01-03 | Nacional | FC Porto | 2-0 | abandoned |
| 11806975 | POR_PL | 2026-05-02 | Famalicao | Benfica | 2-2 | interrupted |
| 12450160 | POR_PL | 2026-08-23 | Estrela | Braga |  | result never confirmed by the source |
| 12450208 | POR_PL | 2026-08-23 | Moreirense | Benfica |  | result never confirmed by the source |
| 1367170 | POR_SL | 2018-12-22 | Arouca | Guimaraes |  | result never confirmed by the source |

## Said plainly - known limitations

- **Pinnacle**: closing prices regular from 2018/19 on FT_1X2, FT_Asian_Handicap, FT_Total_Goals. Its Asian handicap is regular from 2023/24. Lower coverage in 2023/24 (see the season table).
- **Betfair (Sportsbook)**: closing prices regular from 2023/24 on FT_1X2.
- **Betsson**: closing prices regular from 2022/23 on FT_1X2, FT_Total_Goals.
- **Unibet**: closing prices regular from 2017/18 on FT_1X2, FT_Total_Goals.
- **Bet365 markets**: FT 1X2, Asian handicap and total goals regular from 2016/17; HT_1X2 regular from 2018/19, FT_Total_Corners regular from 2019/20, HT_Asian_Handicap regular from 2020/21.
- **Bet365 corner markets** often carry a single pre-match quote: opening = closing on 49 % (FT) and 40 % (HT) of the matches priced.
- **Pinnacle in-play quotes** are numerous only in 2026/27 (227,673); earlier seasons hold at most 17,087 per season. Pinnacle's live clock is mostly not a whole minute ('3 - 46', '1H47''), so `Minute` stays empty on those rows.
- **Implausible source prices are kept as given**: 6 opening/closing 1X2 quotes with an overround outside -0.5 % to 25 %, 5 extreme handicap or total lines, and one Bet365 opening with home and away apparently swapped (Osasuna - Mallorca, 2022-05-22).
- **Closing times differ by bookmaker** (median gap between the last recorded FT 1X2 pre-match quote and kickoff: Pinnacle 3 min, Betfair 6 min, Betsson 8 min, Bet365 24 min, Unibet 53 min).
- **Kickoff times**: for 4 matches the source's scheduled kickoff is more than 3 hours later than the real start read from Bet365's live clock (for example Sporting Gijon - Leganes (2026-03-02), Ternana - Brescia (2017-10-03), Santa Clara - Benfica (2021-01-04)). `Kickoff_UTC` keeps the source's value; their pre-match markets are cut at the real start.
- **Data starts on 2016-08-28** (Championship 2016-09-09, 2. Bundesliga 2016-09-09, Ligue 2 2016-09-09): the first matchdays of 2016/17 are missing. **2026/27** stops at 2026-09-30.
- **Lineups**: formations are present from 2019/20. Lowest lineup coverage: Ligue 2 (75.7 %).
- **Minute-by-minute statistics** start in 2017/18 and cover most matches from 2020/21.
- **Events** are the source's text timeline: it keeps some events it later cancelled (goals disallowed by VAR,
  rescinded cards; a repeated ordinal marks them). Goals in events match the 90-minute score on
  98.434 % of matches; the match tables carry the official score.
- **Team statistics**: goals equal the 90-minute score on 99.98 % of rows.
- Odds are UTC and come from one data provider. No cross-provider reconciliation is claimed.

## Format, licence, delivery

- CSV: comma-separated, UTF-8 with BOM, "." decimals. Large tables are gzip CSV, one file per competition.
- Single-user commercial licence: use the data, analyse it, build and sell models on it.
  Do not resell or redistribute the files themselves.
- A question, an invoice or a custom extract: contact@oliviersportsdata.com

Olivier Vignez - Sports Betting Data Engineer - Olivier Sports Data
