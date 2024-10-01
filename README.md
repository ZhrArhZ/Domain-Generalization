# Domain-Generalization
A collection of recent domain generalization papers (2022 onwards) with code and concise recommendations.

- **Open-set domain generalization (OSDG)**: <br>

   If you're dealing with a problem where your target domains may contain samples from unknown classes—such as 
  in medical imaging, where new and rare diseases may appear that weren’t  present in your training data—and 
  you’re looking for an OSDG method to handle this without resorting to a one-vs-all approach to detect 
  unknown classes, this paper might be useful:

  - [Paper: Generalizable Decision Boundaries: Dualistic Meta-Learning for Open Set Domain Generalization](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Generalizable_Decision_Boundaries_Dualistic_Meta-Learning_for_Open_Set_Domain_Generalization_ICCV_2023_paper.html)
  - [Code: Implementation of the proposed method](https://github.com/zzwdx/MEDIC)

- Single domain generalization (SDG): <br>

  If you only have data from one domain and can't collect more due to privacy concerns or high data collection costs, 
  and you’re looking to expand your dataset, especially for image-related problems, this paper introduces a robust data 
  augmentation method. Unlike traditional methods, it uses a combination of semantic transformations—applying different
  standard augmentation functions that adjust aspects like color, texture, or shape—to enrich your data more effectively:

    - [Paper: AdvST: Revisiting Data Augmentations for Single Domain Generalization](https://ojs.aaai.org/index.php/AAAI/article/view/30184)
    - [Code: Implementation of the proposed method](https://github.com/gtzheng/AdvST)
