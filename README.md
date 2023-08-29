# UE4_SmoothNormalTool
基于UE4的4.27版本（已修复），主要功能就是平滑模型法线
安装后，右键StaticMesh会出现Toon菜单，菜单下平滑模型法线即可
平滑后的法线信息会存在Texcoords[3]中，只保存平滑法线的在切线空间下的X和Y，Z需要自己在材质里算出
