# Claim-Validation

Due to the proliferation of social media platforms, people increasingly depend
on these platforms to consume news content. Consequently, propagandists utilize
these platforms to easily spread fake or distorted contents. Hence, the fake news
detection has been a crucial but difficult task so far, due to the lack of comprehensive labelled datasets and the diverse linguistics cues in the fake news statements.
However, recently to aid the design of a computational model for validating the
deceptive contents, a few labelled benchmark datasets have been introduced in
the literature, such as LIAR and FEVER dataset. In this work, we augment the
LIAR dataset’s claim statements and the speakers’ profile features with the evidence retrieved from the Politifact. We utilize this augmented dataset to design a
transfer learning based computational claim verification approach, CALM: Claim
vAlidation by fine-tuning universal Language Model, which leverages Recurrent
Neural Network to extract textual features.


Moreover, we extend CALM to design an evidence retrieval module RESC:
Retrieving Evidence using Sent2veC. This evidence retrieval module of CALM
helps to extract appropriate evidence of claim statements from the LIAR and
FEVER dataset by utilizing the Politifact and Wikipedia knowledge base respectively. We further extend the CALM by leveraging the pre-trained Universal
Language Model to capture the deep contextual feature representation of both
claim and evidence statements. We have designed a multi-layered Recurrent Neural Network to fine tune the Universal Language Model which gives consistent
state-of-the-art result in deception detection task. We also introduce a couple of
other models by employing various subset of the features and utilizing various
learning models to evaluate the performance of our proposed claim validation approach CALM. In the performance analysis, it is shown that our best performing
model, CALM, outperforms the baseline approach by 16.81% on LIAR dataset
and achieved 42.59% accuracy on FEVER dataset. 
