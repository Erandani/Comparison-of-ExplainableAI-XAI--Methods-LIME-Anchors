# Comparison-of-ExplainableAI-XAI--Methods-LIME-Anchors


One of key focus areas of modern AI is, understanding the risk associated with black-box AI models. Before accessing the risk, the model and its local/global behaviors need to be understood first by the team and end users. It is not much simple for end-users, to understand the other widely used model agnostic approaches for interpretability like LIME, SHARP; where Anchors come in handy as set of IF THEN conditions. Neurocat may serve SLA (service-level agreement) customers where model is already in production and original developers are not around to explain the model. In this scenario, Anchor would be an ideal method for understanding the model predictions at a glance with no detailed explanations, with minimum time and effort. Other than simplicity, in terms of comprehensibility Anchors outperforms existing  model agnostic approaches with higher precision, coverage and efficiency as well. 

This analysis intends to address downfalls of Its’ predecessor research, LIME  by Ribeiro et al,2016 which models the local behavior around some point in a linear way to generate explanations. Instead of fitting surrogate models as in LIME, this method utilizes rule-based conditions called anchors. The anchors work in a way, when the conditions hold true in the input, the predictions are same most of the time regardless of feature values; by design it is intended to attain higher precision. As conditions are well defined in a discrete manner and easy to comprehend, method has extremely clear coverage; means that the explanation can be applied on unseen instances in the region; this addresses unclear coverage in LIME. 
