# Recommendation System with Fuzzy Logic

## Overview
This project aims to develop a hybrid recommendation framework that combines fuzzy logic with content-based and collaborative filtering techniques. The primary objective is to enhance traditional recommendation engines by applying fuzzy rules derived from data analysis. These fuzzy rules augment the capabilities of both content-based and collaborative filtering methods, improving the quality of recommendations.

## Introduction
Contemporary recommender systems primarily leverage data mining and relational analysis to discern patterns or similarities in user preferences. However, a noticeable gap exists in the realm of algorithms that facilitate the incorporation of recommendation rules derived from exploratory data analysis and business insights. The conventional approach often involves deploying algorithms that generate recommendations based on pre-established rules or outputs from mining processes. Yet, not every organization or industry finds this one-size-fits-all methodology suitable. There arises a need for recommender systems that allow users to input rules derived from a nuanced understanding of data, business requirements, and unique rules that go beyond standard mining algorithms.

Enter fuzzy logic—a paradigm that introduces a degree of flexibility and imprecision into the recommendation process, combining elements of both content and collaborative logic. The integration of fuzzy logic provides a more adaptable framework, allowing for recommendations that may not necessarily have the highest scores based solely on algorithmic calculations. Take, for instance, the scenario of recommending new products to users. While traditional algorithms might not prioritize these recommendations based on mining rules, organizations often desire the ability to familiarize users with new items by aligning them with past purchase history.

This research delves into the synergy between fuzzy logic and traditional recommendation algorithms, exploring how the incorporation of fuzzy logic, rooted in exploratory data analysis, enhances the precision and applicability of recommendations. By leveraging the strengths of both traditional algorithms and fuzzy logic, we aim to develop a more versatile recommendation system that aligns with the diverse needs of organizations, incorporating business logic and nuanced exploratory data analysis to refine the recommendation process.

## Project Structure
The project is organized into two main parts:

### Datasets
This directory contains the datasets used in the recommendation system. Proper data preprocessing and exploratory data analysis (EDA) are carried out to create the fuzzy logic rules. 

### Python Books
This section encompasses the Python codebase and logic for building the recommendation system. The primary steps involved are:

1. **Data Preprocessing:** The data is cleaned and structured to be used for generating fuzzy logic rules.(Pre_processing_for_fuzzy_logic)

2. **EDA (Exploratory Data Analysis):** Analyzing the data to identify patterns and correlations, which will inform the creation of fuzzy logic rules.(EDA_KPMG_2)

3. **Fuzzy Logic Integration:** Implementing fuzzy logic to create rules based on the insights from EDA. These fuzzy rules will enhance the recommendation process. Membership functions creation (membership_functions_ver2)

4. **Combining Fuzzy Logic with Apriori and Clustering:** Integrating fuzzy logic with other techniques like Apriori and clustering to further enhance recommendation accuracy.(mem_5_apriori)

5. **Upcoming: Collaborative Logic:** A collaborative filtering approach will be added to the project to complement the existing techniques

