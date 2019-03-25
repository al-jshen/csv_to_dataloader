# csv_to_dataloader

Tool to read a csv file and turn it into a Pytorch dataloader ready to be used for training a network. 

`preprocess()` returns a trainloader and a testloader

Arguments to pass in: 
1. filepath of csv file with headers 
2. columns of features (with support for index slicing)
3. columns of label
4. validation set size
5. batch size

Example usage:

```
import csv_to_dataloader
trainloader, testloader = csv_to_dataloader.preprocess('data.csv', 0:6, 6, 0.3, 32)
```
