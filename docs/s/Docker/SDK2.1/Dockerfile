FROM mcr.microsoft.com/dotnet/core/sdk:2.1
RUN dotnet tool install --global NuKeeper --version 0.28.0
ENV PATH="${PATH}:/root/.dotnet/tools"
ENTRYPOINT ["nukeeper"]
