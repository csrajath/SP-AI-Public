# SP_AI_P_Attacks_Defenses.
Repository Containing Python Notebooks for Poisoning Attacks and Defenses Implementation for Secure and Private AI Course Work


## Poisoning Attacks

### Adversarial Backdoor Embedding
- [Link to Code](https://colab.research.google.com/drive/1X9uwWQnIm7ZS5qQhxBbrbMi8op0FuY54)
- Image Modificaiton : 
- Poisoned Sample:
<img width="284" alt="Screen Shot 2021-12-08 at 10 58 53 AM" src="https://user-images.githubusercontent.com/23517359/145241787-0fe21e5a-5720-40b6-bcb1-bb3dbde5bdb5.png">

- Attacked Sample
<img width="217" alt="boat" src="https://user-images.githubusercontent.com/23517359/145246977-81f9a2eb-d3b4-4169-9809-431cd4da26b4.png">

- Accuracy for Clean, 500, 1000, 2000 Samples
- 0.63, 0.113, 0.113, 0.122, 
- Loss for Clean, 500, 1000, 2000 Samples
- 1.10, 2.3, 2.128, 2.163

## Poisoning Defenses

## Poisoning Defenses for Feature Collision - Activation Defense
- Comparing the original set of pixels for the images to the both attacked and defended pixels. We could save that the defense was highly successful.
- For each class the defense consumed greater cluster size and time to identify the attacked sample data. Without an attack present, the impact of the defense is negligible to the system
## Poisoning Defenses for Adversarial Backdoor Embedding
## Poisoning Defenses for Bulleye Polytope
## Poisoning Defenses for Backdoor


Links:
[Feature Collision](https://colab.research.google.com/drive/1OfcyCfqF2W5P6kDIXl5svd2djcuKaILT?authuser=3#scrollTo=KSMQW71tVnZQ)
[Backdoor](https://colab.research.google.com/drive/1GXeHTE9OoAHQ1IL-jr1zXcjBgY3yz88j)
[Bulleye Polytope](https://colab.research.google.com/drive/1eBYuJzR4T4HXz7BGQWyL6XRC-SgG7PAF)
[Adversarial_Backdoor_Embedding](https://colab.research.google.com/drive/1X9uwWQnIm7ZS5qQhxBbrbMi8op0FuY54)
