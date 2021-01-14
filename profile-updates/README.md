<div style="text-align: left">
 
   <a href = "https://www.linkedin.com/in/ezhilvelme/" > About Me </a> -
   <a href = "https://drive.google.com/file/d/1LAy5Ol2dtCn14x_uI9mE7Lu4mIqhyvba/view?usp=sharing" > Resume </a> - 
   <a href = "https://github.com/Ezhilvel" > GitHub </a> -
   <a href = "https://www.behance.net/ezhilvelme" > Design </a> -
   <a href = "https://airhockey-love2d.herokuapp.com/" > Try Air Hockey! </a> 

</div>

![](./images/user%20profiles.png) 

## Identifying Outdated User Profiles

A causal study on the profile updates (such as job switch) and the network interaction showed that timely updates lead to connecting with 1.5x more users outside the network than a one month delayed update. And 60% of users did not update their profile within one month of a job switch. Built an end-to-end pipeline to identify the outdated user profiles on the platform.

1. Background & Analysis
2. Design
3. Model Performance
4. Results & Recommendation

### Background & Analysis

Jobs Co is a professional networking platform, that helps it's users connect with people, find job and seek talent. On average 2-3% of it's memeber base were foudn to switch job every month. Close to 70% these users do not update their job switch within one month and around 10% upto a year. Until then these profiles are marked as uptdated. This leads to a poor quality data yielding in poor performance of recomendation models and inaccurate metrics.
Also, a user with an updated profile is able to connect with 1.5x collagues from the new company compared to users whose profile is outdated upto a month.

### Framing Problem Statement

Business Problem: Identify the outdates memeber profiles
Machine Learning Problem: Predict when a memeber has switched job, but has not updated on the portal
