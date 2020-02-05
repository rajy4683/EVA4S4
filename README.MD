    #### First attempt ####
      1. No doubling of layers.
      2. Include BN.
      3. Max Accuracy = 99.48% within 20 Epochs
      4. Total params: 13,402
    #### 2nd attempt ####
      1. Swapped the last layers with GAP and 1x1 conv
      2. Max Accuracy = 99.46 within 20 Epochs
      3. Total params: 12122
    
