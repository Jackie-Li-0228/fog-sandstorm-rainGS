# Fog-Sandstorm-RainGS
A non-official partial implementation of the paper "Let it Snow! Animating Static Gaussian Scenes With Dynamic Weather Effects" by Gal Fiebelman et al.

目前实现了静态条件下的雾天，沙尘暴，以及雨天的部分效果（只是添加了静态的雨点），所有效果均还未实现动态场景效果。

## 使用方法 
`python train.py -s <data_path> --weather [rain|fog|sandstorm] `

--weather 参数可选，如果没有该参数即为原版3DGS

## 注意事项

记得创建对应环境以及安装子模块，详情参见`3DGSREADME.md`原MD文件。