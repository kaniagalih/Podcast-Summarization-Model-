Step To Execute Program :

1. import summary_Pip to calculate ROUGE score 
2. import transcript_api to calculate WER score


IF YOU FIND ERROR IN ASR STEP: 

1.If you find error in ASR step, especialy in "!pip install torch" please upgrade your torch version to 2.0.1 in local cmd. Write this code on your cmd "python -c "import torch; print(torch.__version__)" and then "pip install torch==2.0.1" or the newest version 
2. run again ASR step in "!pip insrall torch --upgrade". Then click ctrl + M + . to restrat runtime
3. run "!pip install huggingsound --upgrade"