# whale_identification
## The demo file is [whale_identification_demo.ipynb](https://github.com/ReBachtr/whale_identification/blob/master/whale_identification_demo.ipynb)
## There are trained-models should be download before running.
### Trained models should be download to [./model/](https://github.com/ReBachtr/whale_identification/tree/master/model) 
 https://drive.google.com/file/d/1ohorCjRBg-d9dTYZBEViW_nlnOI6ce0E/view?usp=sharing 
 https://drive.google.com/file/d/1qOrfbHP4qA-XcM6-T_N5mkS5jYiJYnN-/view?usp=sharing
## The main project is in [Merged_models.ipynb](https://github.com/ReBachtr/whale_identification/blob/master/src/Merged_model.ipynb) and [kw6.8.ipynb](https://github.com/ReBachtr/whale_identification/blob/master/src/kw6.8.ipynb)
## Code organization
 demotest                     --The dataset for the demo
 src                          --The python scripts and training notebook
     kw6.8.ipynb              --The notebook of baseline's training
     Merged_model.ipynb       --The notebook of ensembel model training
 model                        --The well-trained models with parameters
 whale_identification_demo.ipynb
                              --The demo notebook
 xxx.csv                      --The labels for data
 split-to_testset.py          --The data split python script
