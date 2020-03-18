FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim

WORKDIR /app
EXPOSE 80

COPY ./publish/ .

RUN ls -lh
RUN echo '----------------------------------------'

ENTRYPOINT ["dotnet", "GitHubBuildTest.dll"]
