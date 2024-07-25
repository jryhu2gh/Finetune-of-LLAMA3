## Inference of LLAMA3
This repository implements files for competition on Kaggle, Chatbot Arena: https://www.kaggle.com/competitions/lmsys-chatbot-arena/code?competitionId=66631&sortBy=voteCount&excludeNonAccessedDatasources=true

Running LoRa Finetuning on Llama3 pretrained model. 

Limited by GPU size (8GB), the current model size is small. (Performance evaluation is needed)

### Compound Model
This work implements a compound model that combines the LoRa model of LLAMA3 and a self-implemented tf-idf thinking model. The output of two models are combined together to give the final result. The motivation is that the tf-idf information may help the large model to better find the correct feature/information.
