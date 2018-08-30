# QiNiuUploadImage
七牛图片上传

#使用方式：    
替换宏文件  
#define Scope @""  
#define AccessKey @""  
#define SecretKey @""

#思路：1、获取图片 2、沙盒路径存储 3、将路径提交七牛

#常见出错：
1、拼接token参数是否正确
      error=bad token   
          2、Code=614 "(null)" UserInfo={error=file exists} 文件名重复
    修改key字段即可   NSString * key = @"dcx"; 
 选择图片
![image.png](https://upload-images.jianshu.io/upload_images/7915183-af53c51109f41bf9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
![image.png](https://upload-images.jianshu.io/upload_images/7915183-c69bd9a27cd8b0a3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
提交成功
![image.png](https://upload-images.jianshu.io/upload_images/7915183-98e2d2af84495812.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
