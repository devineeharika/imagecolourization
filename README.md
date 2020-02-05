we will convert all training images from rgb to lab then given l as the input to the caffee model and predict a(red to green) and b(blue to yellow) then after predicion combine l and a b then convert it back to rgb.
caffee model:
Step 1 - Data preparation: In this step, we clean the images and store them in a format that can be used by Caffe. We will write a Python script that will handle both image pre-processing and storage.
Step 2 - Model definition: In this step, we choose a CNN architecture and we define its parameters in a configuration file with extension 
Step 3 - Solver definition: The solver is responsible for model optimization. We define the solver parameters in a configuration file with extension
Step 4 - Model training: We train the model by executing one Caffe command from the terminal. After training the model, we will get the trained model in a file with extension
