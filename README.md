# Sitecore-System-Check
Check the Sitecore Server within Sitecore CMS, and get server and Sitecore Details.

Sitecore System Check is a Sitecore PowerShell report that provides detailed insights into your Sitecore environment, including memory usage, CPU, database size, and media storage locations. It works across various server setups, including Docker and Kubernetes, with no server access required, just a Sitecore developer account. The tool offers easy installation via Sitecore Package or CLI.

# Install
for installaton 2 option,
 * option-1: Use Sitecore CLI, item serialization
 * option-2: Download and install System Check-1.0.zip  as Sitecore Package

# Run
Go to Desktop in Sitecore, and run the My Server PowerShell report
![Example](https://raw.githubusercontent.com/jbluemink/Sitecore-System-Check/master/start-sitecore-system-server-report.png)

# Get memory cpu database and computer details for you server, works for docker, kubernetes, (Azure app servers? is untestested)
Depend on if you running Sitecore on Docker, Kubernetes or on a bare metal server the results can mean something else, On Docker you running on a clear isolated instances so the CPU count and memory is what is assigned, on Kubernetes you might see the Server CPU and memory with is likely limited.
There are also values of the process, IIS, w3wp.exe and there you can see the actual memory usage.
![Example](https://raw.githubusercontent.com/jbluemink/Sitecore-System-Check/master/sitecore-system-server-report.png)

# Blog
See [Tip: Sitecore System Check PowerShell Report](https://www.stockpick.nl/sitecore/sitecore-system-check-powershell-report/)
