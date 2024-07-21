# Spotify-WIN

1、复制下列终端命令粘贴到powershell

```c
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/mrpond/BlockTheSpot/master/install.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify"
```

![powershell](/Untitled.png)

powershell

2、等待执行完毕

![Untitled](Untitled%201.png)

3、等待执行完毕

![Untitled](Spotify-WIN%2073874e20321d470892d960190b359310/Untitled%202.png)

4、命令运行后截图

![Untitled](Spotify-WIN%2073874e20321d470892d960190b359310/Untitled%203.png)

5、最后就是登录问题，这里需要注意下上网的姿势

![Untitled](Spotify-WIN%2073874e20321d470892d960190b359310/Untitled%204.png)

6、结果展示

![Untitled](Spotify-WIN%2073874e20321d470892d960190b359310/Untitled%205.png)

注：感谢GitHub[**BlockTheSpot](https://github.com/master131/BlockTheSpot)大佬和[BlockTheSpot](https://github.com/mrpond/BlockTheSpot)大佬提供的自动化终端命令。**
