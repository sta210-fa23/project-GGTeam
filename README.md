# Predicting Tik-Tok User Data Based on Video Data
by GG-Team (Will Chen, Katelyn Cai, Hannah Choi, Weston Slayton)

# Presentation
https://docs.google.com/presentation/d/18ZayU1tHrilcA2Z3Z3cIBiqDSe69scSLH7CQ7ZyPimA/edit?usp=sharing

# Data Dictionary
user_name: Tiktok username which data is drawn from

likes: Average number of video likes on a user's account

shares: Average number of video shares on a user's account

comments: Average number of video comments on a user's account

plays: Average number of video plays on a user's account

followers: Average number of followers for a user's account

video_length: Average video length time on a user's account

total_videos: Total videos on a user's account

video_length_bin: Average video length time for a user in comparison to other users (1 = bottom 1/3 of average video length times, 2 = middle 1/3 of average video length times, 3 = highest 1/3 of average video length times)

## Summary
To better understand Tiktok's algorithm, which drives massive social change, GGTeam chose to analyze the relationship between a user's follower counts and a user's other account statistics (including but not limited to plays, shares, and total videos). We transformed the dataset to deal with lack of constant variance and linearity, and dropped likes to account for multicollinearity with plays. We used AIC, BIC, and adjusted r-squared applied to several rounds of cross-validation to create our final model. Although we captured around a third of the variability in the data using the model, we then reflected on what underlying relationships we may have missed and what variables/data we might use in a second try for this model. 
