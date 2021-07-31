FROM mcr.microsoft.com/dotnet/sdk:3.1

WORKDIR /mydotnetapp

COPY . .

ENV ASPNETCORE_URLS=http://localhost:5000
EXPOSE 5000
CMD ["dotnet", "DotNetCoreWebAPIForAzureAppService.dll"]
