To valid the simulation of ADL, there are five steps to enable the code:
1. Install mathematica 12.1
2. Install Python 3.7. 
3. Activate the python environment. Then install airsim & pyzmq packages with commands: pip install airsim, pip install pyzmq
4. Linking the python env with mathematica by running command in mathematica: RegisterExternalEvaluator["Python", "YOUR PYTHON PATH"] 
5. Clone simula_of_ADL folder to your PC. Unzip the 5 compressed packages in simula_of_ADL, and then run the chy.nb file.



---------------------------
The code is composed of three parts (that are annotated with comments in the code: Model Training, Read Trained Model and Control ICVs in Airsim). To run the code successfully, these three parts need to be run once separately.

-------------------------
You can also directly use our trained model at https://www.kaggle.com/impchai/trainedmodel for testing the effect at https://www.kaggle.com/impchai/testvedio.
