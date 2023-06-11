# 安裝教學 - MacOS

## Enviroment  
OS: MacOS  
晶片: Apple M1  
> Intel 晶片並不適用於本處提供之安裝方法。

## Installation Steps  
Dependencies Installation
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
