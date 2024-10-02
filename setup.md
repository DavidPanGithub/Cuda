#What you need before starting 
- Ubuntu
- gcc compiler in Ubuntu
- cuda setup(https://developer.nvidia.com/cuda-downloads) WSL-Ubuntu
  {Example: wget https://developer.download.nvidia.com/compute/cuda/12.6.2/local_installers/cuda_12.6.2_560.35.03_linux.run
            sudo sh cuda_12.6.2_560.35.03_linux.run }
run nvcc --version, nvidia-smi to confirm installation 
Very basic Linux Commands you should know:\n
  cd {dir_name}  //navigate (dir_name)
  cd ..          //go back to parent dir
  nano {file_name} //create a file and exit the text
  mkdir {dir_name}, rmdir {dir_name}  //create and remove dir
  pwd            //print out working dir
  ls             //show all files/dir under the working dir
