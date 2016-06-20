# Notes


## Web net46

Simple Visual Studio Project. Just Build & Publish

* File > New Project > Web > Asp.NET Core Web Application (.NET Framework)
* Change .net framework to net46
* deploy and plublish
* Note scm  url
* While Publishing, review Cloud Explorer (review Settings)
	- File 
	- Logs
	- Deployment Slots
* Site goes live, review `scm` / Debug Console (Kudu) 
	- It's just IIS 
	-  with tweaks ~200 tweaks		
		- On Prem = protect the server
		- Azure = Protect the app
* Reviuew Live Editing  from SCM Console
* Process Explorer Tools
* End on Deployment Slots - no deployment slots.
* Review, republish code. Changes are gone - We really need a better way to manage what's on the server

### Summary

* Adtantage
	- Easy for Developers to push
* Disadtangage 
	- No idea what version is on the server
* ** Next Step. We needs some ALM**


