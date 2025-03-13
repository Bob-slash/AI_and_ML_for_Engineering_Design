# AI_and_ML_for_Engineering_Design
Machine Learning assignments and projects from MIT 2.155 Artificial Intelligence and Machine Learning for Engineering Design class.

## Challenge Problems
Over the course of the course, we were tasked with different optimization, classification, and generation problems to solve over a course over a week.

## Final Project
For my final project, I worked with 2 other team mates to create a meal-plan optimizer.

The intent of this project was to develop a meal plan tool that incorporates recipe reviews in order to provide a variety of quality meals that meet the nutritional requirements set by the user. The tool combines machine learning techniques with a constrained discrete optimization algorithm to generate a two-week meal plan. 
The inclusion of machine learning comes in the form of recipe analysis. A database of over 240,000 recipes with over 1.2 million reviews was analyzed to ensure quality (in the form of highly rated meals) and variety. 
The methodology combined three key machine learning components: ratings normalization through weighting and sentiment analysis, text embeddings and Hamming distance calculation for recipe similarity, and logistic regression for meal type classification. Optimization was conducted to maximize the normalized ratings average and minimize the similarity across the two-week plan while remaining within the nutritional constraints. 
Findings show that the tool successfully generated a varied meal plan with high average meal rating while maintaining daily nutritional targets. 
This project addresses what we believe to be a heretofore unexplored method of developing nutritious meal plans. The incorporation of constraint-based optimization based on average ratings may currently exist in another meal plan tool, but the inclusion of machine learning to create more sophisticated ratings analysis and ensuring variety across meals provides a feature not present in most (if any) meal plans. 


