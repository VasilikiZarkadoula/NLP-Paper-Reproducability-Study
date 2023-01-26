score 0.0.1a0 python library has a bug. In the setup file of the source code, a README file is opened that does not exists. Instead there is as ReadMe file. 
We changed their setup code, line 24, to long_description=open('ReadMe.md').read().
