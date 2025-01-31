# embodied ai - 2020_05

## Navigation

[Home](https://lixin97.github.io/arXivRadar) / [Papers](https://lixin97.github.io/arXivRadar/papers) / [embodied ai](https://lixin97.github.io/arXivRadar/papers/embodied_ai)

- Part 1

## Papers

| **Paper** | **Date** | **Comment** |
| --- | --- | --- |
| **[Improving Vision-and-Language Navigation with Image-Text Pairs from the Web](http://arxiv.org/abs/2004.14973v2)**<details>Following a navigation instruction such as 'Walk down the stairs and stop at the brown sofa' requires embodied AI agents to ground scene elements referenced via language (e.g. 'stairs') to visual content in the environment (pixels corresponding to 'stairs'). We ask the following question -- can we leverage abundant 'disembodied' web-scraped vision-and-language corpora (e.g. Conceptual Captions) to learn visual groundings (what do 'stairs' look like?) that improve performance on a relatively data-starved embodied perception task (Vision-and-Language Navigation)? Specifically, we develop VLN-BERT, a visiolinguistic transformer-based model for scoring the compatibility between an instruction ('...stop at the brown sofa') and a sequence of panoramic RGB images captured by the agent. We demonstrate that pretraining VLN-BERT on image-text pairs from the web before fine-tuning on embodied path-instruction data significantly improves performance on VLN -- outperforming the prior state-of-the-art in the fully-observed setting by 4 absolute percentage points on success rate. Ablations of our pretraining curriculum show each stage to be impactful -- with their combination resulting in further positive synergistic effects.</details> | 2020-05-01 |  |
