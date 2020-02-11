    #### First attempt ####
      1. No doubling of layers
      2. Use 16 input channels for all layers
      3. Include BN.
      4. Max Accuracy = 99.48% within 20 Epochs
      5. Total params: 13,402
    #### 2nd attempt ####
      1. Swapped the last layers with GAP and 1x1 conv
      2. Max Accuracy = 99.46 within 20 Epochs
      3. Total params: 12122
    #### 3rd attempt ####
      1. Used 8 channels in first layer and 16 in the rest
      2. Max Accuracy = 99.43 within 20 Epochs
      3. Total params: 10,874
    #### 4th attempt ####
      1. Used 8 channels in first layer and 16 in the rest
      2. Max Accuracy = 99.41 within 20 Epochs
      3. Total params: 10,874
      4. Moved BN after RelU
      5. Training accurac
    #### 5th attempt ####
      1. Used 8 channels in first 2 layers
      2. Introduced Dropout as there was large delta between Training Accuracy and Test Accuracy
      2. Max Accuracy = 99.46 within 20 Epochs
      3. Total params: 9122
      
    
