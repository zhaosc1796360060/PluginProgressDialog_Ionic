# PluginProgressDialog_Ionic
ionic 进度条插件 Android平台 



![](https://github.com/longtaoge/CordovaPluginsDome/raw/master/www/codova_plugin.gif)


###使用方法

    1 cordova plugin add  https://github.com/longtaoge/PluginProgressDialog_Ionic.git

    2 将项目中-->plugins-->org.xiangbalao.progressdialog-->src-->android-->ProgressDialog.java文件
	  import cn.com.ths.hzdatacenter.R修改为自己的R文件路径
	  查看自己R文件路径方法：
	  platforms-->andorid-->AndroidManifest.xml中查找package.
	   
       
    3 提供的方法
      xiangbalao.showdalog("正在加载数据...");    //打开进度条
      xiangbalao.closedalog();     //关闭进度条
	
    4 卸载方法
      cordova plugin rm org.xiangbalao.progressdialog  	