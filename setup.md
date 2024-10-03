# What you need before starting  <br>
**- Ubuntu** <br>
**- gcc compiler** in Ubuntu <br>
**- cuda** setup(https://developer.nvidia.com/cuda-downloads) WSL-Ubuntu <br>

  {Example: <br>
    ```
    wget https://developer.download.nvidia.com/compute/cuda/12.6.2/local_installers/cuda_12.6.2_560.35.03_linux.run
    sudo sh cuda_12.6.2_560.35.03_linux.run 
    ```
run nvcc --version, nvidia-smi to confirm installation <br>
Very basic Linux Commands you should know:<br>
  cd {dir_name}  //navigate (dir_name) <br>
  cd ..          //go back to parent dir <br>
  nano {file_name} //create a file and exit the text <br>
  mkdir {dir_name}, rmdir {dir_name}  //create and remove dir <br>
  pwd            //print out working dir <br>
  ls             //show all files/dir under the working dir <br>
