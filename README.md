# p2pFLsim

### ns3FL : A Simulator for P2P FL

Model training on Python (using Keras/TF)   
Network simulation using ns3   
Device constraints like available RAM, GPU applied   

Simulation1 : CIFAR dataset across 10 clients

### Project folder structure

#### Channel
Defines the testing with regards to network structures using ns3

#### Device


#### Model
Currently contains a jupyter notebook testing the implementation of FL


### How to use:
To generate the data, you need to run ```./Device/data_for_docker.py```. This requires tensorflow and matplotlib to be installed. 
In that file, first uncomment the line on ```create_and_save_clients()``` and specify the number of clients you want to generate the data for.
Make a copy of the ```saved_data_test``` folder and place it into the node folder.
