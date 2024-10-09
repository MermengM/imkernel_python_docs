
# Install  
## InstallImkernel
### From Pypi
  
使用 pip 安装 IM Kernel Python SDK：  
  
```
pip install imkernel
```

## imkernel 扩展依赖安装  
### 三维显示扩展

三维展示采用pyvista+jupyter，故需要安装如下包：  
  
```  
pip install jupyterlab vtk trame ipywidgets 'pyvista[all,trame]' trame_jupyter_extension
```  
jupyter设置中文需要安装包：
```  
pip install jupyterlab-language-pack-zh-CN  
```  
### 几何核心扩展
采用pyocc作为几何核心 
  
安装pyocc (需要通过Conda)

```  
conda install conda-forge::pythonocc-core  
```  
  
### 绘图库扩展
提供了matplotlib的一些封装，需要安装如下包：  
  
```  
pip install matplotlib
```