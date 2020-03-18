FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim

WORKDIR /app
EXPOSE 80

#COPY ["./bin/Release/netcoreapp3.1/publish", "/app"]

COPY "./bin/Release/netcoreapp3.1/publish" .

RUN ls -lh

ENTRYPOINT ["dotnet", "GitHubBuildTest.dll"]