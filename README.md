# RazorsPagesMovie

Install [.NET Core SDK](https://dotnet.microsoft.com/download)
Add /dotnet to system PATH

```
dotnet tool uninstall --global dotnet-ef
dotnet tool install --global dotnet-ef
dotnet ef migrations add InitialCreate
dotnet ef database update
```
