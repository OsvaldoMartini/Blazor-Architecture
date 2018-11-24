Clone Blazor from GitHub

	Two New Organizations
	
	Forks-SteveSanderson
	https://github.com/Forks-SteveSanderson
	
	and
	
	Forks-CSharpFritz
	https://github.com/Forks-CSharpFritz

	Create Remote (fork) -> "When I ready to pull in Changes" named as "upstream"

		From Steve Sanderson (My Fork)
			git clone https://github.com/Forks-SteveSanderson/Blazor.git
			cd Blazor
			git remote add sanderson-upstream https://github.com/SteveSanderson/Blazor
		
		From CSharp Fritz Tests (My Fork)
			git clone https://github.com/Forks-CSharpFritz/Blazor.git
			cd Blazor
			git remote add fritz-upstream https://github.com/aspnet/Blazor.git
  

	From CSharp Fritz Tests
		cd Blazor

		dotnet build

		Open the Solution in Visual Studio

		.\Blazor.sln


	
	
	Others Infos
	
	Prerequisites:

		Node.js (>8.3)

	Other Pages	
		
	Restore Git submodules by running the following command at the repo root:

		cd Blazor
		git submodule update --init --recursive
		
		
	Got to the page: 
	
	https://github.com/aspnet/AspNetCore/wiki/Building-from-source
	
	Environment System Variables:
	Remove "C:\Program Files\dotnet\" from Path:
	
	Add User Variables:
	%USERPROFILE%\.dotnet\x64 to Path
	
	Add Too in System Variables by the way VS Code and VS Studio it will goingo to need.
	
	Add System Variables:
	%USERPROFILE%\.dotnet\x64
	
	Execute:
	
	build.cmd /t:Restore and wait to Update dotnet and other installs...
	
	
	Get started with Blazor Page

	https://blazor.net/docs/get-started.html	
	
	
	
	
	
	
	