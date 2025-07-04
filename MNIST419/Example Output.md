parameters {
  conv1.weight: 50,
  conv1.bias: 2,
  conv2.weight: 54,
  conv2.bias: 3,
  fc.weight: 270,
  fc.bias: 10,
  bn1.weight: 2,
  bn1.bias: 2,
  bn2.weight: 3,
  bn2.bias: 3,
  bn3.weight: 10,
  bn3.bias: 10,
}
total: 419
epoch 1 test loss 0.31758, test loss diff(ema) -0.005915, patience hits 0(+0)/10
epoch 2 test loss 0.20398, test loss diff(ema) -0.002657, patience hits 0(+0)/10
early stopping at epoch 2+86% test loss 0.18872, test loss diff(ema) -0.001230, patience hits 10(+10)/10
accuracy 94.54%

![image](https://github.com/user-attachments/assets/516e8637-c336-478d-89b0-2682c8f997a8)
![image](https://github.com/user-attachments/assets/5b6b5919-2307-4cd4-b603-a90feabe5142)
![image](https://github.com/user-attachments/assets/3d2e5119-9ae4-4fe7-b3fb-acb498279328)
