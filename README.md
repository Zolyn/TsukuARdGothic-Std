# TsukuARdGothic Std
筑紫A丸 | [筑紫B丸](https://github.com/Zolyn/TsukuBRdGothic-Std)

筑紫A丸ゴシック 5字重，原作者：宁静之雨

本仓库是在 PC 端上使用筑紫A丸ゴシック字体的一次尝试，由于原作者分享的ttf文件只有Regular字重，所以打算从 Magisk 模块中提取字体

字体提取自原作者分享的 Magisk 模块（`/system/fonts/`目录）

由于提取出来的字体名称为 `Noto Sans SC`，为了防止在 PC 端上和其他字体冲突/混淆，使用 `ttx` ([fonttools](https://github.com/fonttools/fonttools)) 将字体文件转换为`.ttx`文件，并参考 [fontname.py](https://github.com/chrissimpkins/fontname.py) 将 `nameID` 为1,4,6和16的`<namerecord>`标签中的名字改为 `TsukuARdGothic Std`的相应格式，并再使用 `ttx` 按照 `.ttx` 文件内容生成 `.ttf` 文件

`renamed`文件夹为更名后的字体文件，`source`文件夹为原字体文件

如果更改的名字不符合你的需求，可以参考上述方法自行更改

## 声明
字体的版权归字体公司所有，字体仅供学习交流使用，严禁商用或兜售倒卖
