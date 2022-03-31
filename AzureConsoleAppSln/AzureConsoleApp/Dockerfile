#Dockerfile

# Download the base image from the docker hub to run the app.
FROM mcr.microsoft.com/dotnet/framework/runtime:4.8-windowsservercore-ltsc2019

# Make working directory for an application called app.
WORKDIR /app

# Copy all the Release folder content to the app folder.
COPY /bin/Release .

# Inside the app folder, the application will be running.
ENTRYPOINT ["AzureConsoleApp.exe"]