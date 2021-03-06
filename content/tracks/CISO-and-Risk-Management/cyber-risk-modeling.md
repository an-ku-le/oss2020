---
title        : Cyber Risk Modeling
type         : working-session
track        : "CISO and Risk Management"
topics       : ["CISO", "RISK"]
featured     : yes                # if  "yes" review with summit team
when_day     : Wed
when_time    : WS-3
hey_summit   :
room_layout  :                
room_id      : 
session_slack: 
status       : review-content 
organizers   : Phil Huggins
description  : Session on Risk Modeling
---

Phil brings his extensive experience to a discussion on modelling (general) risk and comparing security risk modelling maturity to other markets (finance, insurance, medical..). This also involves attribution of $ value to risk and how security teams can talk the language of the business


### Current Security Risk Management is Broken

There is a lot of complexity and uncertainty in cyber risk.
Current practice tends to hide uncertainty and present certainty.

We use Ordinal Scales (Red, Amber, Green / High, Medium, Low / 1,2,3,4,5 etc) rather than Cardinal measures (£ or %).
Is a red x red risk a really red risk? Twice as bad? Three times as bad?
We then assign numerical values to support ‘risk arithmetic’ (5 x 5 = 25 /2.5 = risk score)
OWASP Risk Rating Methodology (Risk Factors / Ordinal Scales)

We then use risk matrices that arbitrarily identify an ordinal boundary as the ‘risk appetite’. (Amber =Good, red = Bad).

By assigning a single value to probability and impact we are communicating a level of certainty about the outcome we don’t really have.

People are individually poor at prediction
Hedgehogs / Foxes / Superpredictors

We are awash with data about cyber events but few documented robust statistical methods deployed. 

The solutions are well known by other risk professions

#### Quantitative Risk Approaches

 - Probability of event
 - Range of outcomes (lognormal distribution)
 - Monte Carlo Simulation
 - Loss Exceedance Curves <- Business understands these
 - FAIR / OpenFAIR

#### Prediction Approaches:
 - Risk Panels
 - Averaged predictions
 - Feedback !!!!!!!!!
 - Brier Scores 
 - Base Rate Data
 - Calibration

#### References:
 - Dan Geer
 - Doug Hubbard
 - Philip Tetlock
 - Jack Jones
 - Ryan Huber