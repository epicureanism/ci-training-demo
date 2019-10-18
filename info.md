
- Project URL:
  - https://git.gis.tw/pub/ci-training-xx
- Repo URL
  - git@git.gis.tw:pub/ci-training-xx.git
- 建置
  - 執行 Windows 批次指令
    - "c:\Program Files (x86)\NuGet\nuget.exe" restore 
  - Build a Visual Studio project or solution using MSBuild
    - MSBuild Build File
	  - WebApplication1\WebApplication1.csproj
	- Command Line Arguments
	  - /p:Configuration=Release
		/p:OutDir=../web

- 建置後動作
  - ftp 
	- transfer -> source files, remove prefix
		- web\_PublishedWebsites\WebApplication1\
- 發佈後的網站瀏覽
  - http://www.gis.tw/ci-training-xx