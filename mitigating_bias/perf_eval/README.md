score 0.0.1a0 python library has a bug. In the setup file of the source code, a README file is opened that does not exists. Instead, there is as ReadMe file in the source code. We changed the setup.py code, line 24, to long_description=open('ReadMe.md').read(). The changed script with the solved bug can be found in score1 folder. In order to be able to use this library, download the source code from https://pypi.org/project/score/, make the appropriate change in the code as descriped and then run the setup.py as illustrated in our notebooks.

Run the notebooks after placing them in the parth: /mitigating_bias/performance_eval/WMT/ of authors' repo and use our requirements.txt. Our trained adapters can be found in the provided drive link.

In order to run perfomance evaluation without using adapters, you can follow the steps:

  -for BART score comment out in file eval_bart_score.py : self.model.load_adapter(adapter_path,set_active=True)
  
  -for BLEURT score comment out in file  eval_bleurt.py : self.model.load_adapter(adapter_path,set_active=True)
  
  -for BERT score comment out in file scorer.py : self._model.load_adapter(adapter_path,set_active=True)
