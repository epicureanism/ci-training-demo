
- Project URL:
  - https://git.gis.tw/pub/ci-training-xx
- Repo URL
  - git@git.gis.tw:pub/ci-training-xx.git
- �ظm
  - ���� Windows �妸���O
    - "c:\Program Files (x86)\NuGet\nuget.exe" restore 
  - Build a Visual Studio project or solution using MSBuild
    - MSBuild Build File
	  - WebApplication1\WebApplication1.csproj
	- Command Line Arguments
	  - /p:Configuration=Release
		/p:OutDir=../web

- �ظm��ʧ@
  - ftp 
	- transfer -> source files, remove prefix
		- web\_PublishedWebsites\WebApplication1\
- �o�G�᪺�����s��
  - http://www.gis.tw/ci-training-xx