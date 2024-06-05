### DL LAB PROGRAMS


This is a set of Notebooks for DL LAB. Since all the codes are written in PyTORCH, from the requirements.txt - tensorflow and keras can be removed in order to save time :))

Also while performing data preprocessing as shown in the example snippet below:


 `train_dataset = torchvision.datasets.CIFAR10(root='./data', train=True,
                                                download=True, transform=transform)
test_dataset = torchvision.datasets.CIFAR10(root='./data', train=False,
                                            download=True, transform=transform)`

                                            
set `download=False` instead of `True` if you have already downloaded the dataset in the data folder
