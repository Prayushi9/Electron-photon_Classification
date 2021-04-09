# Electron-photon_Classification
A deep learning model (CNN) build to classify Electron and Photon using matrices provided of the two classes.

# Dataset Description
The dataset was provided by the CERN. The files name used here are: 'SingleElectronPt50_IMGCROPS_n249k_RHv1.hdf5' and 'SinglePhotonPt50_IMGCROPS_n249k_RHv1.hdf5'.

- For training set:
    - Input: 39,8400 matrices of size 32x32 and 2 channels
    - Target: 39,8400 values of 0 or 1

- For validation set:
    - Input: 49800 matrices of size 32x32 and 2 channels
    - Target: 49800 values of 0 or 1

- For test set:
    - Input: 49800 matrices of size 32x32 and 2 channels
    - Target: 49800 values of 0 or 1

# ----------KERAS MODEL----------
# Model Description
The model and code description of 'keras model' is mentioned in the table below:
<table>
    <tr>
        <td>DL Framework</td>
        <td>Keras</td>
    </tr>
        <tr>
        <td>Keras version</td>
        <td>2.4.3</td>
    </tr>    
    <tr>
        <td>Libraries</td>
        <td>Numpy, h5py</td>
    </tr>    
    <tr>
        <td>Layers</td>
        <td>Conv2D, Batchnormalization, Flatten, Dense</td>
    </tr>    
    <tr>
        <td>Activation functions</td>
        <td>ReLU, Sigmoid</td>
    </tr>    
    <tr>
        <td>Optimizer</td>
        <td>RMSprop</td>
    </tr>    
      <tr>
        <td>Regularizer</td>
        <td>Dropout</td>
    </tr>
    <tr>
        <td>Learning Rate</td>
        <td>0.0001</td>
    </tr>    
    <tr>
        <td>Batch size</td>
        <td>32</td>
    </tr>    
    <tr>
        <td>Epochs</td>
        <td>50</td>
    </tr>    
    <tr>
        <td>Loss function</td>
        <td>Binary Crossentropy</td>
    </tr>    
    <tr>
        <td>Metrics</td>
        <td>Accuracy</td>
    </tr>    
      
</table>

# Results
<table>
    <tr>
        <td>Dataset</td>
        <td>Loss</td>
        <td>Accuracy</td>
    </tr>
        <tr>
        <td>Train set</td>
        <td>0.5436</td>
        <td>0.7344</td>
    </tr>
    </tr>
        <tr>
        <td>Validation set</td>
        <td>0.5589</td>
        <td>0.7235</td>
    </tr>
    
</table>

