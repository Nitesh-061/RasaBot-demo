# RasaBot-demo
It is just a demo on how to get started with Rasa

## How to Get started / Run  -- 

Step1: Donwload project or clone it in the system - (git clone)
        
Step2: <- Create a separate environment ->
        
        conda create -n myRasaEnv python==3.6.9

Step3:  

        conda activate myRasaEnv

Step4:  
        
        pip install rasa-x==0.32.2 --extra-index-url https://pypi.rasa.com/simple

        pip install spacy
        
        python -m spacy download en
        
        python -m spacy download en_core_web_md


Step5: 
        
        rasa train

Step6: 

        rasa x

Nlu.md  => this file contains the training phrase and the intent name

stories.md => this file contains the flow of the conversation

domains.yml => in this file we are supposed to mention the list of intents and list of utterances
              along with their response text





-- To remove env:
deactivate the env then run then  run --> 
        
        conda env remove --name env_name
