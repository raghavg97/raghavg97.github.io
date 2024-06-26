---
title: 'Machine Learning and Material Science'
date: 2022-07-30
permalink: /posts/2022/07/MLMS/
tags:
  - ML
  - Material Science
  - AL
  - Phase Diagram
---

How can ML contribute to Material Science?
------------------------------------------


Machine Learning (ML) is simply a statistical tool (well, rather a black box model in most cases) that can predict for "unkwown instances". Can it be used for Material Science(MS)? If yes, how? 

MS is a vastly experiment based engineering field. The most of the understanding of mechanisms of machining orginiated from 
repeated trials, highly developed microscopes, experimental strategies, etc. Traditionally, material science had less to do with computations. But there are a variety of things that can be done. The most famous ones include material discovery. In materials discovery, basically ML (particularly Active Learning) is used for suggesting better molecules to search to do the experiments. So, basically it improved the search strategies for new molecules. 

Recently, I was trying to learn about Graph Neural Networks (GNNs). The most famous use case of GNNs is that it helped identify a "drug" by accelerating and trying to narrow down the search space better. So, the ML in material science is still about accelerating the experiments and it is NEVER ABOUT replacing the experiments. So, I have been thinking what else can be done?

I came across a paper (which I kind of intentionally searched for) which can try to predict the phase diagrams for 3 component mixture given 2 component mixture. That was interesting but now when I think about it, how can you validate it or in fact, more importantly, what is the use of such a model. You cannot provide a black box model to someone saying this is the real phase diagram. What could make ML more useful for Material Science except accelerating the experimentation? Dynamic control sounds the best possible other thing possible to do. Dynamically controlling the microstructure/ material properties during the manufacturing process.


