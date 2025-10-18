---
draft: false
title: "AI Project Overview of Schindler-JP AI-team"
snippet: "Difference between OPENAI and other AI start-ups;the main application senarios."
image: {
    src: "https://images.unsplash.com/photo-1667372393119-3d4c48d07fc9?&fit=crop&w=430&h=240",
    alt: "frontend master"
}
publishDate: "2023-06-01 21:39"
category: "Tutorials"
author: "Dapeng Zhang"
tags: [AI, LLM, Chatgpt]
---


## Difference from OPEN-AI:

1.Small model with strong performance
2.Cheap. 
3.Can be deployed locally
4.Customizability. 
5.Data security. 
6.Free of copyright problem.

## List of other start-ups doing similar things:
1.Cyberagent
2.Rinna
3.Retrieva

## Difference from other start-ups:

- Base-Models are different
we plan to use Bloom and chatGLM(Trained by Tsinghua University) MOOS(Trained by FuDan University). Bloom is good at multi-lingual tasks. Models trained in Chinese may be transfered to Japanese tasks conveniently with high performance.
- Application Senarios are different.
1.Publisher (translation) company whose books are mainly digests and combinations of exsited materials.
2.administrative scrivener office　or other offices whose documents are also easy to be composed by generative AI.
- Utilize  model decompositon techniques
These techniques can give the model fine explainability, while the cost is lower than full training.
The cost is approximately 2 million yen (cost of a HPC (with GPU*4)).
Fine-Tuning with cloud GPU in AWS/GCP is about 80,000 yen. Already tested.

## the next step is finishing prototype in application scenario(publisher) 
It will take a while. 
Then we can perfect the prototype to a python package. At least finish all skeletons of the package.

## Compute the develop cost, initial cost, running cost
 

 
