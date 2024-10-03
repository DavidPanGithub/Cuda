## What you need before starting  <br>
!(https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FCUDA&psig=AOvVaw1dR_wPijs0FHouu8XlmhPq&ust=1728057543299000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJCt05PK8ogDFQAAAAAdAAAAABAE)
**-   Ubuntu** <br>

**-   gcc compiler** in Ubuntu <br>

**-   cuda** setup(https://developer.nvidia.com/cuda-downloads) WSL-Ubuntu <br>

**_cuda setup Example (run in Ubuntu)_**: <br>
<br>
```bash
  wget https://developer.download.nvidia.com/compute/cuda/12.6.2/local_installers/cuda_12.6.2_560.35.03_linux.run
  sudo sh cuda_12.6.2_560.35.03_linux.run
```
<br>
run
```bash
  nvcc --version
  nvidia-smi
```
to confirm installation <br>
<br>
<br>
**Basic Linux Commands you should know:**<br>
<br>
<br>
```
```bash
  cd {dir_name}  
```
navigate (dir_name) <br>
```bash
  cd ..    
```
go back to parent dir <br>
```bash
  nano {file_name}
```
create a file and exit the text <br>
```bash
  mkdir {dir_name}, rmdir {dir_name}
```
create and remove dir <br>
```bash
  pwd
```
print out working dir <br>
```bash
  ls
```
show all files/dir under the working dir <br>
