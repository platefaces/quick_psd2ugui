# 解析psd文件，一键生成ugui面板工具
支持文本，图片，按钮，滑动条，网格布局等组件的导出和生成
支持九宫格图片的自动剪切和生成
支持对称图片切半版的导出和生成
支持滑动列表和列表元素自动布局

----------------------------------------------------------------------
  测试所用版本，unity 版本：5.3.3f1，ps版本：cs6 64位<br> 

  v1.0.2<br> 
  2017.02.06
  1.增加网格布局(GridLayoutGroup)组件的导出和生成
  2.增加滑动条(Slider)组件的导出和生成

  v1.0.1
  2017.01.22
  1.修改导出psd时的xml配置结构，改images层级为layer，ugui生成代码对应修改
  2.增加九宫格的导出，根据命名时的border值自动切九宫格图
  3.滑动列表（ScrollRect）的导出和生成，可动态布局滑动项,支持单行和单列，暂不支持grid

  v1.0.0
  2017.01.12
  1.正常文本的导出和生成
  2.静态文本和图片文本的导出和生成
  3.正常图片的导出和生成
  4.九宫格的生成，暂时无法从ps导出，还需手动切图
  5.RawImage的导出和生成
  6.对称图片切半的导出和生成
  7.公用图片的导出和生成
  8.按钮控件的导出和生成
