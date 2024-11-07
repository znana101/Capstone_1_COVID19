# Capstone_1_COVID19
This proposed a deep learning model using LSTM neural network to predict new cases in Malaysia using the past 30 days of number of cases.
The objective of this project is to forecast Malaysia's Covid-19 cases trend.
## Deep learning model images
![architecture](https://github.com/user-attachments/assets/30f3807d-18ec-491a-93c9-56eab0f735d5)

## Results
### Training Loss
![Screenshot 2024-11-07 193447](https://github.com/user-attachments/assets/3604e7da-996b-49d1-99b6-54ce09caa982)
### Training MAE
![Screenshot 2024-11-07 193332](https://github.com/user-attachments/assets/c494da9e-3a35-44f4-abc9-52736dd42f8b)
### Evaluation
![image](https://github.com/user-attachments/assets/69473d29-a980-47ac-ab66-c9d2d81cf5eb)
### Malaysia's Covid-19 Cases Timeline
![covid19 prediction training](https://github.com/user-attachments/assets/295eba58-0716-465e-886e-848133526746)
## Discussion
1) LSTM, Dense, and Dropout layers are used in the model.
2) The number of nodes used in LSTM layers are 64 and 32.
3) n_steps was set to 30 which is equivalent to 30 days.
4) MAPE error obtained is 0.03% which is lesser than 1% when tested against testing dataset.
5) The lowest value obtained in TensorBoard training loss graph is 0.0009.  
Conclusion: The model is able to predict the Covid-19 cases in Malaysia successfully.

## Credits
GitHub - https://github.com/MoH-Malaysia/covid19-public
Official data on the COVID-19 epidemic in Malaysia. 
Powered by CPRC, CPRC Hospital System, MKAK, and MySejahtera.

