# Microsoft.Owin.Security Extensions

QQ and Webchat extensions for Microsoft.Owin.Security

## Get Started

- Webchat

``` csharp
    // config 
    app.UseWeixinAuthentication("[you appId]", "[you app Secret]");

    // get external login info 
    var weixinInfo = await AuthenticationManager.GetExternalWeixinLoginInfoAsync(); 
```

- QQ

``` csharp
    // config 
    app.UseQQAuthentication("[you appId]", "[you app Secret]");

    // get external login info 
    var qqInfo = await AuthenticationManager.GetExternalQQLoginInfoAsync();    
```   

 

# Microsoft.Owin.Security ��չ

QQ ��΢�� Owin ��չ

## ʹ�÷���

- ΢��

  ``` csharp
    // ���� 
    app.UseWeixinAuthentication("[you appId]", "[you app Secret]");  

    // ��ȡ΢�ŵ�¼����Ϣ
    var weixinInfo = await AuthenticationManager.GetExternalWeixinLoginInfoAsync();   
    
    ```

- QQ

    ``` csharp
    // ���� 
    app.UseQQAuthentication("[you appId]", "[you app Secret]");  

    // ��ȡQQ��¼����Ϣ
    var qqInfo = await AuthenticationManager.GetExternalQQLoginInfoAsync();    
    
    ```
