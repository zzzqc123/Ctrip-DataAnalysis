# Ctrip-DataAnalysis
携程网景点数据分析：
		一份较详细的数据分析，内容包括爬虫、数据预处理、数据可视化分析,开发环境是JupyterNotebook.

1. pyecharts文件夹为这个库的源码，可以在自己的设备上用pip安装。由于Python导入第三方库的顺序是先检索项目的目录，再到用pip安装时的那个目录，因此也可这个文件
   夹下载到你的项目目录下就省去pip install时的步骤。
	 
2. pyecharts-assets-master为这个pyecharts库的用到的静态资源文件，默认挂载在https://assets.pyecharts.org/assets/，把它放在本地启动，主要是能在渲染
	 图片时能加快渲染速度。
