# appeals_on_gibdd_judgments
Analysis and predicting of result of court resolutions by appeals on administrative offense judgment of russian traffic police
Case: currently in Russia the most of courts dismisses the most of appeals to administrative offense judgment of traffic police, even if there is no any evidence of guilt, but sometimes the courts cancels the administrative offense judgment of traffic police.
Purpose: identify factors affecting the cancelations and build model (using machine learning algorithms) that predicts result of court resolution.
Plan:
1. Check the available database of court resolutions and decide if it's enough for the purpose.
1.1 If point 1 - not: download database and parce it from open public resource like https://bsr.sudrf.ru or https://mos-gorsud.ru
2. Preprocessing (incl. filtration), extraction of features and metadata (incl. using NLP tools) potentially affecting the resolution result
3. Explonatory Data Analisys, check statistics
4. Testing hypotheses about the influence of certain factors on the resolutoin result (like the presence of video recording of the offense / evidence of innocence, the presence of a lawyer in court, etc)
5. Building the classification model that could predict the appeal result and its probability using input case materials
6. Statistical findings, report of the most influential factors of cancelations, trends, tendencies, practical recommendatoins of how to maximize the probability of allowance of appeal.
