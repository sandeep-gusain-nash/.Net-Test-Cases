Please use this command to generate the code coverage as this command excludes program.cs file that cannot be covered by test cases.

**Command : dotnet test /p:CollectCoverage=true /p:CoverletOutputFormat=lcov /p:CoverletOutput=./TestResults/lcov.info /p:ExcludeByFile=**/program.cs**

**Coverage Report Image**

![screen shot](<Screenshot from 2024-04-22 14-06-14.png>)