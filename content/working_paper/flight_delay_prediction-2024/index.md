---
title: "Flight Delay Dynamics: Unraveling the Impact of Airport-Network-Spilled Propagation on Airline On-Time Performance"
abstract: Flight delay prediction has attracted increasing attention in airline operations. Early identification of potential flight delays is crucial for improving airport scheduling and airline operations while mitigating associated costs. This study investigates the influence of the potential propagation of flight delays throughout the airport network via interconnected flights, a mechanism we term Airport-Network-Spilled Propagation (ANSP). To model the ANSP mechanism, we develop a novel time-dependent, network-based approach that decays the importance of past delays. From this network, we extract a real-time ANSP score for each airport to measure the influence of propagated delays. To evaluate our proposed approach, we employ four state-of-the-art machine learning models using domestic airline on-time performance data from the 30 large hub airports in the United States. The results demonstrate that integrating the ANSP score with established features from airline operations literature significantly enhances flight departure delay prediction performance, achieving an increase in AUC of up to 5.49%. Furthermore, we conduct an explainable AI analysis using Shapley additive explanations (SHAP), which reveals that our ANSP score ranks as the most important predictor among all features tested. 
author_notes:

authors:
- admin
- Yi Tan
- Lu Wang
date: "2024-12-20T00:00:00Z"
#doi: https://doi.org/10.1093/jamia/ocae140
featured: false

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Major revision at *Decision Support Systems*, December 2024"



#links: "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4756710"
# - name: ""
#   url: ""
#url_pdf: /publication/2021-2025/risk-score-2024/Risk_score_2024.pdf
#url_pdf: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4756710'  
#url_code: 'https://github.com/yajun668/RiskScoring'
url_poster: ''
url_project: ''
url_source: ''
url_video: ''


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---