FROM mcr.microsoft.com/dotnet/sdk:6.0

WORKDIR /app

# Copy project files
COPY . .

# Restore NuGet packages
RUN dotnet restore
