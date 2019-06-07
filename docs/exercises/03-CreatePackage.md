### Exercise 3: Create a package the old fashioned way

 

This is meant to be an exploratory exercise and intentionally doesn't doesn't provide much direction. Most other exercises contain all steps and are very reflective.

 

1. Download Google Chrome from <https://dl.google.com/tag/s/dl/chrome/install/googlechromestandaloneenterprise64.msi> and <https://dl.google.com/tag/s/dl/chrome/install/googlechromestandaloneenterprise.msi>. OFFLINE: These files should be in C:\vagrant\resources\installers.
2. From a command line, call `choco new googlechrome`
3. Go into the googlechrome folder and read the readme, look through the files that were created and try to create a package just using the 64 bit Google Chrome MSI.
4. Run `choco pack`
5. Install the package using Chocolatey - `choco install googlechrome -y -s .`

 

Note that first time packaging this kind of throws you into the thick of it to see if the information provided is enough to move forward.