# 安裝教學 - MacOS

## Enviroment  
OS: MacOS  
晶片: Apple M1  
> Intel 晶片並不適用於本處提供之安裝方法。

## Installation Steps  
1. Dependencies Installation
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install git
brew install cmake
brew install qt@5
brew install mesa-glu
brew install mesa
brew install libxt
brew install mesalib-glw
brew install --cask macsvg
brew doctor
brew install python3
sudo port install qt5-qtxmlpatterns
brew install libyaml
pip3 install bts_tools
brew install open-mpi
brew install tbb
brew install ninja
```
2. 複製最新版
```
git clone https://gitlab.kitware.com/paraview/paraview.git
mkdir paraview_build
cd paraview
git checkout tag (版本號 如下圖 將要安裝版本直接取代`tag`)
```
<img width="253" alt="image" src="https://github.com/1241doobieC/ParaView-Plugin/assets/43471008/9378a8b8-fdaf-42fb-8d95-90362476e4c4">

