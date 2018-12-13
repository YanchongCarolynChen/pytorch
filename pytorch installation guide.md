# pytorch installation guide
This Markdown recorded how I install pytorch on Mac OSX as well as on Windows 10
## Mac OSX
* create a new environment  

```
conda create --name pytorch_envr
source activate pytorch_envr
```
**delete an environment**

```
conda remove --name pytorch_envr --all
```

**list all environment**

```
conda list
```

* activate the environment

```
source activate pytorch_envr
```

* *deactivate your environment*

```
source deactivate pytorch_envr
```

* download pytorch & torchvision  
go to [pytorch website](https://pytorch.org/get-started/locally/), it will give you what commands you need based on your OS  
For me, it is 

```
conda install pytorch torchvision -c pytorch
```

* make environment available on Jupyter Notebook  
*the kernel available in Jupyter are iPython kernels*  
_so install your conda envs into iPython_

```
conda install ipykernel
```
*then open Jupyter Notebook and under kernel can switch kernel*

## Window 10
* create a new environment  

```
conda create --name pytorch_envr
source activate pytorch_envr
```
**delete an environment**

```
conda remove --name pytorch_envr --all
```

**list all environment**

```
conda list
```

* activate the environment

```
activate pytorch_envr
```

* *deactivate your environment*

```
deactivate pytorch_envr
```

* download pytorch & torchvision  
go to [pytorch website](https://pytorch.org/get-started/locally/), it will give you what commands you need based on your OS  
For me, it is 

```
conda install pytorch torchvision -c pytorch
```

* make environment available on Jupyter Notebook  
*the kernel available in Jupyter are iPython kernels*  
_so install your conda envs into iPython_

```
conda install ipykernel
```
*then open Jupyter Notebook and under kernel can switch kernel*
