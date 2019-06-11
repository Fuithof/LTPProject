# LTPProject

## Dependencies



## Running the model

**For training a new model:**  
Set the environment variable 'LASER' to the root of the installation, e.g. `export LASER="${HOME}/projects/laser" `  
Set the lambda_loss value in the code  
Run all cells in Model_with_LASER.ipynb  
  
  
**For testing the model, using a pre-build model:**  
Copy one of the pre-build models (.pth files) to model_storage/ch8/nmt_luong_no_sampling/  
Rename the .pth file to model.pth  
Run all the blocks, except cell 16 (which is the training cell)
