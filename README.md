# csv_to_dataloader
read a csv file and turn it into a pytorch dataloader ready to be used for training a network

`preprocess()` returns a trainloader and a testloader

Arguments to pass in: filepath (csv format with headers), columns of features, columns of label, test size, batch size
