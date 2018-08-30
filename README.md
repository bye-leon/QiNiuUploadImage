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
