# reproducibility-tutorial
Tutorial

#Clone my repo
    9  git clone https://github.com/yakshiUPR/reproducibility-tutorial.git
#Download and install miniconda
   13  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   16  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda

   20  ln -s /opt/conda/pkgs/*/bin/* /bin
   21  ln -s /opt/conda/pkgs/*/lib/* /usr/lib

   24  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   25  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   26  python3 -m pip install bash_kernel
   27  pip install ipykernel
   28  python3 -m bash_kernel.install
   29  apt- apt install python3-pip
   30  apt-get install python3-pip
   31  apt-get update
   32  apt-get install python3-pip
   33  python -m pip install bash_kernel
   34  python3 -m pip install bash_kernel
   35  python3 -m pip install ipykernel
   36  python3 -m bash_kernel.install
   37  conda search jupyterlab
   38  /opt/conda/bin/conda search jupyterlab
   39  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   40  ln -s /opt/conda/bin/* /bin
   41  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''l --notebook-dir='/scratch/reproducibility-tutorial/'
   42  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''l --notebook-dir='/scratch/reproducibility-tutorial/'
   43  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''l --notebook-dir='/scratch/reproducibility-tutorial/'
   44  jobs
   45  fg %1
   46  fg %1
   47  jobs
   48  kill %1
   49  jobs
   50  kill %1
   51  jobs
   52  kill $!
   53  jobs
   54  kill %3
   55  jobs
   56  kill %2
   57  jobs
   58  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''l --notebook-dir='/scratch/reproducibility-tutorial/'
   59  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password=''l --notebook-dir='/scratch/reproducibility-tutorial/'
   60  /opt/conda/bin/conda search -c bioconda snakemake
   61  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   62  # verify the installation
   63  snakemake --version
   64  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   65  /opt/conda/bin/conda search -c bioconda snakemake
   66  snakemake --version
   67  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   68  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   69  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   70  sudo apt-get update
   71  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   72  docker run hello-world
   73  cd reproducibility-tutorial/
   74  ls
   75  history >>README.md
