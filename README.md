# Dislike-driven-Music-Recommendation-System
Music recommendation systems are more
important than ever in the era of digital technology, but
traditional models do not consider user skips and dislikes,
and thus generate low-quality recommendations. In this
paper, we present Skipify, a novel deep learning-based
music recommendation system that leverages skip and
dislike behavior to improve personalized song
recommendations. The system learns rich audio
features—temporal, spectral, rhythmic, tonal, and
high-level features—from a large dataset of 10 genres
(blues, classical, country, disco, hip-hop, jazz, metal, pop,
reggae, and rock). The features are input to a Multilayer
Perceptron (MLP) model to predict songs to be classified
into four listener types: casual, party, focus, and
adventurous. The model achieves an average precision of
0.95, recall of 0.96, and F1-score of 0.96, with very high skip
prediction performance for adventurous listeners (100%
precision and recall). The system also employs threshold
optimization to adaptively trade precision and recall. For
real-world deployment, Skipify processes individual tracks
by a pipeline, extracting features and predicting skip
likelihood with 92.82% accuracy on synthetic test data. The
experiments demonstrate that skip-based recommendation
systems can have a substantial impact on user engagement
by connecting musical features to listener preferences.
