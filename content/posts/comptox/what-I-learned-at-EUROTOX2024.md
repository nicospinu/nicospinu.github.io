---
title: "What I learned at #EUROTOX2024"
date: 2024-09-15T15:00:00
tags: ["comptox"]
params:
    description: "I continue to see how the cosmetic industry struggles with the adoption and validation of New Approach Methodologies. At the start-up I’m currently building, we are working on changing that. Being invited to present my computational-related projects on neurotoxicity, I attended this year’s edition of the Congress of the European Societies of Toxicology (EUROTOX). Here are the slides. I also took the opportunity to listen to others’ opinions and advances that could inform our direction. Here’s a glimpse of what I’ve learned."
---
I continue to see how the cosmetic industry struggles with the adoption and validation of New Approach Methodologies. At the start-up I’m currently building, we are working on changing that. Being invited to present my computational-related projects on neurotoxicity (slides [here](https://pitch.com/v/eurotox2024_nicoleta-spinu-qafdyn)), I attended this year’s edition of the Congress of the European Societies of Toxicology (EUROTOX). I also took the opportunity to listen to others’ opinions and advances that could inform our direction. Here’s a glimpse of what I’ve learned.

### Protection not prediction

The paradigm shift continues to evolve around the hypothesis that if there is no bioactivity observed at consumer-relevant concentrations, no adverse effects are assumed to happen. In other words, if we don’t see a compound being bioactive at the concentration at which a product is used and applied, we assume it doesn’t lead to toxicity. 

The way we assess acute toxicity is well acknowledged and accepted. However, systemic and repeated dose toxicity is the current focus and challenge of the industry. My hope is for the principles from causal science to be leveraged in this regard. I’ve been looking into them since the early days of my PhD and their utility has been demonstrated in other fields already. 

I found it interesting as well to hear again the discussion about how much mechanistic knowledge should be modelled. As I learned first-hand, a prioritisation strategy and Bayesian machine learning can serve as a solution to finding the balance between what we assess and what we aim to prove.

A personal observation, the Bioactivity Exposure Ratio (BER; the ratio of the point of departure derived from concentration-response data and the relevant exposure estimation, the metric used to support the protection not prediction statement) seems to be increasingly adopted by other chemical industries such as food and nutrition.


### Training models on old chemistry and data 

Making a model to learn a problem/task and its chemical space remains to be challenging. Old chemical data aren’t necessarily only those available in public and/or open-source databases. It’s also the historical records, of failed or discontinued projects, that the companies have. Whatever model someone builds today must remember how well the model extrapolates to today’s chemistry.

Pharmaceutical companies are looking at the development of models trained on all sorts of molecular representations (1D to 3D, SMILES strings, chemical and physical descriptors including new ones and new ways). This multimodal approach seems to be the focus of early-stage discovery projects, for example, for derisking a series of chemicals or filtering to find the best series. This implies having the technical capabilities, which might hinder the competition and concentrate the opportunities among existing big players in the long run.    

Another direction these companies are taking is getting more data internally from unstructured sources to structured machine-readable and ready datasets. Thus, the Large Language Models have found their way quite easily to be adopted in this domain.


### Assessing chemical by chemical 

This is not feasible nor plausible in the real world, and risk assessors would agree. We can group chemicals by structural similarity, biological effects, and uses. For example, class-based approaches have been applied to PFAS. However, we don’t have widely accepted assessment approaches, especially when thinking of mixtures and plastic products. Recently, COSTER was proposed as a research standard for toxicology and environmental health systematic reviews while NIEHS showcased the development of systemic evidence maps as a foundation for exploring evidence in a structured and organised manner. They implemented it in Tableau! Such frameworks can minimise bias and lead to transparent and reproducible decision-making workflows. The wish is for AI to replace the manual curation of articles where most efforts go.

To the question of how to reduce the risk itself imposed by exposure to chemicals, it was acknowledged that the regulatory limits do not have to be based on risk assessment. For example, we will never have a complete list of positive compounds such as PFAS. We should rather opt for the most protective limit values when in doubt.
