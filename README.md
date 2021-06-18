~~~sh
brew install mono-libgdiplus
brew install dotnet-sdk
dotnet new webApp -o helloworld_dotnet --no-https
cd helloworld_dotnet
dotnet new gitignore
code . # edit to Hello World!
dotnet run
~~~
