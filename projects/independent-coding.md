---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Crypto Zombies"
date: 2021
published: true
labels:
  - Solidity
  - Blockchain
  - Cryptocurrency
summary: "I embarked on an independent coding study project where I learned the basics of coding in Solidity and making smart contracts for cryptocurrency. I used the Crypto Zombies web course for guidance."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>



Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [(https://cryptozombies.io/)].
