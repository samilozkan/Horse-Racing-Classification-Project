# Horse-Racing-Classification-Project
Explanation of the Columns of Data
'Date': Date of the race
'City': City of the race
'Race_n_time': Time and number of the race on the given date
'ID': ID
'Racer': Racer of current race
'Racer_1': Racer of ID latest race
'LAST_RACER_SAME_AS_CURRENT_RACER': TRUE IF RACER OF THE LAST RACE WAS SAME AS CURRENT RACE FOR THE GIVEN ID, False if not
'LAST_ RACER SAME_AS_CURRENT RACER _BINARY': 1 if above column was TRUE, False if not
'Yas': Age of the given ID
'Speed_in_Secs': Speed of the ID in the given race converted in m/s
'GANYAN_TRANS': Odds of the ID for the given race
'GANYAN_TRANS_int': Odds in the above column converted
'RANK': Rank of the ID in the given race
'AG_Percentage': Percentage (Only available for specific races)
'AG_RANK_AMONG_GROUP': Rank of the percentage number of AG for the given race
'AG_RANKING_Score_Normalized': Min-max normalized score of AG calculated from the rank of the AG
'Ranking_Score_Normalized': Min-max normalized score from the rank of the ID for the given race
'First_Position_Percentage':==1A=Percentage of the 1st Position of the Racer of the ID for current race
'Second_Position_Percentage':==1B=Percentage of the 2nd Position of the Racer of the ID for current race
'Third_Position_Percentage':==1C=Percentage of the 3rd Position of the Racer of the ID for current race
'Forth_Position_Percentage': Percentage of the 4th Position of the Racer of the ID for current race
'TOP_THREE_RACER_PERCENTAGE': 1A+1B+1C
'RANK_LATEST_1ST': RANK OF THE ID IN THE LATEST RACE
'RANK_LATEST_2ND': RANK OF THE ID IN THE 2ND LAST RACE
'RANK_LATEST_3RD': RANK OF THE ID IN THE 3RD LAST RACE
'RANK_LATEST_4TH': RANK OF THE ID IN THE 4TH LAST RACE
'RANK_LATEST_5TH': RANK OF THE ID IN THE 5TH LAST RACE
'TOPLAM_RACES': Total Races played by the ID in whole lifetime
'TOPLAM_1ST': Number of races in which ID got 1st position
'TOPLAM_2ND': Number of races in which ID got 2nd position
'TOPLAM_3RD': Number of races in which ID got 3rd position
'TOPLAM_4TH': Number of races in which ID got 4th position
'BIRINCILIK_PERCENTAGE': Percentage of 1st Positions
'IKINCILIK_PERCENTAGE': Percentage of 2nd Positions
'UCUNCULUK_PERCENTAGE': Percentage of 3rd Positions
'DORDUNCULUK_PERCENTAGE': Percentage of 4th Positions
'SPEED_LATEST_1ST': Speed of the last race of the given ID calculated from the time and distance for that specific race
'SPEED_LATEST_2nd': Speed of the 2nd last race of the given ID calculated from the time and distance for that specific race
'SPEED_LATEST_3rd': Speed of the 3rd last race of the given ID calculated from the time and distance for that specific race
'SPEED_LATEST_4th':Speed of the 4th last race of the given ID calculated from the time and distance for that specific race
'SPEED_LATEST_5th': Speed of the 5th last race of the given ID calculated from the time and distance for that specific race
'RANK': Rank of the ID in the given race, WILL BE OUR LEARNING CRITERIA
'Ranking_Score_Normalized': Min-max normalized score from the rank of the ID for the given race, WILL BE OUR PREDICTION CRITERIA OR SCORE
