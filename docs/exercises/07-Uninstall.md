# Exercise 07: Optional, Uninstall






2. Run PS>choco uninstall wpfapp2
3. Verify C:\Programdata\chocolatey\lib\wpfapp2 is removed
4. Verify C:\dips\wpfapp2.exe is still present
5. Remove the file manually
6. Add the file chocolateyUninstall.ps1 to the exercise 5 directory
6. Run choco pack to build 
7. Install the package again using the script from exercise 6
8. PS>choco uninstall wpfapp2
9. Verify C:\dips\wpfapp2.exe has been removed



