# MNIST-reader
Simple python object that can read the original MNIST files into numpy arrays.
Reader object initialised with the directory that contains the MNIST files, as found here http://yann.lecun.com/exdb/mnist/. E.g ./data. Reader.read_data() then takes boolean arguments normalize and vectorize_labels which determine if the pixels of images are normalised to between 0 and 1 and if the labels are returned as single numbers or as vectors of length 10 with a 1 in the corresponding digit position. It returns a tuple X_train, y_train, X_test, y_test.
