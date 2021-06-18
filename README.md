~~~sh
brew install mono-libgdiplus
brew install dotnet-sdk
dotnet new webApp -o helloworld_dotnet --no-https
cd helloworld_dotnet
code . # edit to Hello World!
dotnet run
~~~
