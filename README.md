**UNDER CONSTRUCTION**


How to deal with 3 repos 

from https://github.com/PaintLab/PixelFarm/issues/37#issuecomment-429516843



*Shallow*
```
git clone https://github.com/PaintLab/pxdev.git
git submodule init
git submodule update --depth 10
```

*Full*
```
git clone https://github.com/PaintLab/pxdev.git --recursive
```

