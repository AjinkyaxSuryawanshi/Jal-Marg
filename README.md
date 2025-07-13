# Jal-Marg
Final year project 
SIH 2024 problem statement 1658 
Title - Development of a versatile and fast algorithm for the optimal ship routing.
Description - Background: Most of the goods are transported around the world by shipping which relies heavily on fossil fuels for powering. Given the expenditure of the shipping industry on the fuel, a main objective of a shipping company is to optimize the ship route for the least fuel consumption. Depending on the type and purpose of the voyage, it is also desirable to optimize several other parameters such as, the travel time, passenger comfort and route safety, to avoid any damage to the ship, cargo, crew and passengers. Optimization of each of these parameters serves a purpose. For instance, an energy efficient route may not be safe in terms of weather. Therefore, to avoid loss of life and property, route weather safety needs to be considered. An application suggesting the optimal route based on the chosen set of optimal parameters for any voyage between two ports in the Indian Ocean, will immensely benefit the Indian shipping industry. Description: At the heart of any optimal ship routing application lies the optimization algorithm. Although scientific literature is available on various methods of optimizing the ship routes, given the commercial potential, there are no applications available publicly which can be customized for the Indian Ocean region. The optimization methods reported in literature range in complexity, computation time, versatility, etc. Various factors, such as, the forcings (surface winds, currents and waves), design of the ship and ship drift characteristics, impact the ship├ö├ç├ûs motion at sea. The optimal route must be continually evolving because the weather conditions keep changing as a ship proceeds on its voyage. Therefore, it is crucial to choose a suitable optimization method that can optimize several parameters for a range of ships (with varying type, dimensions, drift characteristics of a ship) and develop an algorithm to return an optimal route within a reasonable computational time. The algorithm can optimize for the voyage time and safety to begin with but with a scope for addition of more optimization parameters. To get an idea of the problem, please visit: https://www.youtube.com/watch?v=ct9v-mQgYqE ii) https://www.youtube.com/watch?v=wCTdHRTWtNI Expected Solution: Identification of a versatile optimization method and development of a reasonably fast algorithm, preferably written in an open-source programming language such as Python


#Abstract

What was done?
This research developed machine learning (ML) models to monitor the hydrodynamic performance of ships using operational data. The study implemented three approaches: non-linear
Principal Component Regression (NL-PCR), non-linear Partial Least Squares Regression
(NL-PLSR), and probabilistic Artificial Neural Networks (ANN), enhanced with a novel
fouling growth factor to quantify biofouling effects.
Why was it done?
Accurate performance monitoring is essential for optimizing hull and propeller maintenance,
which directly impacts fuel efficiency and emissions. Current scheduled maintenance practices are often inefficient, while existing performance monitoring methods lack precision.
This work addresses the maritime industry’s need for data-driven solutions to support the
International Maritime Organization’s greenhouse gas reduction targets.
How was it done?
The models were trained on 2.5-3 years of in-service data from two sister ships, incorporating
weather hindcast data and multiple cleaning events. A fouling growth factor was formulated
using ship static time and admiralty coefficient trends. Model performance was validated
against traditional fouling friction coefficient methods.
What was found?
All three ML models effectively tracked hydrodynamic performance changes, with probabilistic ANN showing superior accuracy (R²=0.98 for shaft power prediction). Surprisingly,
the simpler NL-PCR and NL-PLSR models achieved comparable results (R²=0.94-0.95),
suggesting interpretable models may suffice for this application. The fouling growth factor
successfully captured performance degradation trends between cleaning events.
Significance
This work demonstrates that ML can transform ship performance monitoring from schedulebased to condition-based maintenance. The comparable performance of simpler models
makes the solution more accessible for industry implementation. By enabling optimal cleaning schedules, this approach can reduce fuel consumption by 5-15% and significantly lower
emissions, contributing to sustainable shipping practices.
