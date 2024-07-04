SUNSPOT PREDICTION USING AN LSTM. 

About:


Sunspots are phenomena seen on the sun's surface that are darker than the rest and represent a flux in the Sun's magnetic field. Although rare, these spots can help determine the sun's general activity and how space is affected. This Jupyter Notebook aims to predict the possibility of sunspots occurring using a data set of sunspot activity and train a neural network based on the data. The neural network's purpose is to aid in predicting future sunspots. 

How to use:


The Jupyter notebooks are organized as follows. The first section imports all relevant libraries. This is important as one of the libraries enables the neural network to use the GPU for a faster process as compared to using the CPU. The notebook then reads and parses the relevant .csv file into its components such as the indices and number of data entries. This is essential as this will allow the data to be spliced into bins for more effective neural network training. Finally, the notebook trains the neural network with 67% of the data as the training set. The rest of the data is used to test the neural network. After this Neural Network was trained with 2000 epochs. The neural network went over and parsed the entire training set 2000 times. To test the quality of this neural network, the Mean Squared Error (MSE) was used to plot the loss curve. This curve showed a slight underfit but regardless good fit. Finally, the neural network was used to predict the frequency of future sunspots. 

Contact:


Any inquiries about this project can be sent to my email: dodibanzon@gmail.com


