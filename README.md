# Enter the Metrix!

Using https://huggingface.co/nvidia/NV-Embed-v2 to embed metric schemata from Hypotactic.

See metric-clustering-iliad.ipynb for naive clustering of the Iliad. Interestingly, the clustering seems **completely uninformative** and random: the all have almost *exactly* the same ratio of feminine to masculine caesuras and number of resolutions (taken as an integer 0-5).

How to make the clusters informative?
1) Provide some markup of the lines i.e. connect them somehow to semantics
2) Finetune, i.e. algorithmically make some groupings of common features such as caesuras, resolutions, word forms and bridges