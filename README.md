# AI-Art-Classification
## Abstract
Controversy over the ownership of digital art concepts and the art pieces themselves has arisen 
with the proliferation of artificial-intelligence tools. Efforts can be made in the distinction between 
“human-created” art and those of text-to-image generative models, as well as between popular AI 
art generators. Various image classifiers were tested for accuracy in distinguishing between the 
artwork created by the DALLE-2, Midjourney, and StableDiffusion generators, and common 
patterns among the generators were identified to improve classification performance. Among the 
tested supervised learning algorithms, a random forest approach was most effective at correctly 
assigning AI artist to its corresponding artwork, and dimensionality reduction can vastly decrease 
computation efforts while preserving predictive power of the models.

## Files
`ai-art-retrieval`: scrape or download images from DALLE-2, Midjourney, and StableDiffusion databases

`ai-art-classfication`: run classification algorithms and PCA

`ai-art-report`: reported results
