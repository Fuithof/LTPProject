# LTPProject

## Dependencies
Python 3.7.3  
Pytorch 1.1.0


## Running the model
Use the NMT_with_LASER.ipynb notebook  

**For training a new model:**  
Set the environment variable 'LASER' to the root of the installation, e.g. `export LASER="${HOME}/projects/laser" `  
Set the lambda_loss value in the code  
Run all cells in Model_with_LASER.ipynb  
  
  
**For testing the model, using a pre-build model:**  
Copy one of the pre-build models (.pth files) to model_storage/ch8/nmt_luong_no_sampling/  
Rename the .pth file to model.pth  
Run all the blocks, except the cell marked as Training in comments at the top
