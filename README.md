# EXPAAI - Explainable Patent Analysis using Artificial Intelligence
This repository consists of all the codes developed for the experiments conducted in the paper entitled "Explainable Artificial Intelligence for Highlighting and Searching in Patent Text". 

#### Note: 
More details regarding the accessibility of Chrome extensions are available [here](https://github.com/Renuk9390/expaai_browser_extension_cli). Further queries regarding the project will be answered via: renukswamy.chikkamath@hm.edu

#### Quick links:
1. [Chromium browser extension](https://github.com/Renuk9390/expaai_browser_extension_cli)
2. [Flask API for our fine-tuned models](https://github.com/Renuk9390/expaai_model_api)
3. [Fine-tuned models used in API](https://huggingface.co/fassahat)
4. Manually labeled data and different evaluations on it is here: Paper_Experiments

#### A use-case scenario in Windows system:
1. Make sure API is deployed locally in your system, refer https://github.com/Renuk9390/expaai_model_api
    After installing, run the app.py by traversing to the directory while keeping tensorflow environment active as follows:
![image](https://github.com/Renuk9390/expaai_model/assets/34164541/92ae2c96-8558-479b-8d6c-480278e36c45)
2. To verify that API is built successfully, go to [localhost:](http://localhost:3000/hello)http://localhost:3000/hello as follows:
![image](https://github.com/Renuk9390/expaai_model/assets/34164541/51d554a1-4f75-4ec3-905d-80adf18f9b2e)
3. Make sure Chrome extension is installed properly, refer https://github.com/Renuk9390/expaai_browser_extension_cli
    Successful installation and once the extension is pinned, you can verify by clicking the icon as follows:
![image](https://github.com/Renuk9390/expaai_model/assets/34164541/7096f322-a114-4b8e-af3f-a578533b7e61)
4. Hit the 'Analyse' button to automatically highlight the technical aspects, a successful run will look as below:
![image](https://github.com/Renuk9390/expaai_model/assets/34164541/863105c4-322b-464e-bffa-8e777686d80b)
5. Refreshing the opened patent page in Google Patents and reloading the extension helps sometimes if there are any issues!
6. Runtime of this application is completely dependent on the users' local machine, for instance, in Windows machines with high hardware configurations with GPU, then the application is much faster as compared with only CPU-based machines.
7. Runtime and responsiveness vary from a few seconds to even a few minutes for instance in machines like Nvidia RTX 2060 8Gb GPU, 32 GB RAM, and i7 CPU machine with 16GB RAM respectively.
8. Runtime and responsiveness also vary based on the length of the patent document.
9. This is just a working preliminary prototype with limited capabilities in terms of usability, however, can be modified and extended for personal customizations.

#### Usage tip:
1. This Chrome extension application is user-friendly if there is good hardware being used to handle large models like Google BERT Large during the inference time.
2. Implementing this application in large-scale machines like cloud environments with 32 GB of GPU would provide results within a fraction of a second. 



