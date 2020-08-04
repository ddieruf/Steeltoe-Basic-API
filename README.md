# Steeltoe-Basic-API
A very basic from scratch .net webapi using the bare minimum Steeltoe packages.

1. Create a new WebAPI project in Visual Studio: File > New > Project
	
	<code class="inline">dotnet new webapi</code>
	
	|<img src="/site-data/labs/vs-new-proj.png" class="img-fluid" />|<img src="/site-data/labs/vs-new-proj.png" class="img-fluid" />|<img src="/site-data/labs/vs-new-proj.png" class="img-fluid" />|
	|:-:|:-:|:-:|
	

1. Bring in the dependency for `Steeltoe.Management.Endpointcore`
	<ul class="nav nav-tabs">
		<li id="" class="vs_tab nav-item active">
			<a role="tab" 
				onclick="document.getElementsByClassName('cli_tab')[1].classList.remove('active');
				document.getElementsByClassName('cli')[1].classList.add('hide');
				document.getElementsByClassName('vs_tab')[1].classList.add('active');
				document.getElementsByClassName('vs')[1].classList.remove('hide')">Visual Studio</a></li>
		<li id="" class="cli_tab nav-item">
			<a role="tab" 
				onclick="document.getElementsByClassName('vs_tab')[1].classList.remove('active');
				document.getElementsByClassName('vs')[1].classList.add('hide');
				document.getElementsByClassName('cli_tab')[1].classList.add('active');
				document.getElementsByClassName('cli')[1].classList.remove('hide')">dotnet cli</a></li>
	</ul>
	<div class="nav-tabs-body">
	<div id="vs">
	<img src="/site-data/labs/vs-add-endpointcore.png" class="img-fluid" />
	</div>
	<div id="cli" class="hide">
	<code class="inline">dotnet add package Steeltoe.Management.Endpointcore</code>
	</div>
	</div>
