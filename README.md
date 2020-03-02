**UNDER CONSTRUCTION**


How to deal with 3 repos 

from https://github.com/PaintLab/PixelFarm/issues/37#issuecomment-429516843



*Shallow*
```
git clone https://github.com/LayoutFarm/HtmlRenderer.Build.git
git submodule init
git submodule update --depth 10
```

*Full*
```
git clone https://github.com/LayoutFarm/HtmlRenderer.Build.git --recursive
```


--- 

I you want to create an issue, Please create on an associated repos ... 

1) https://github.com/LayoutFarm/HtmlRenderer

2) https://github.com/PaintLab/PixelFarm

3) https://github.com/LayoutFarm/Typography




