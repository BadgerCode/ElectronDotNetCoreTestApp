# Electron .net Core Test App

Using instructions from https://elanderson.net/2018/04/create-a-desktop-application-using-asp-net-core-and-electron-net/

# Environment Setup
Install the Electron CLI globally:
> `dotnet tool install ElectronNET.CLI -g`


# Run the project
Run the following commands inside the folder `./ElectronTestApp/`

> `electronize start`

Or to automatically rebuild
> `electronize start /watch`


# Build the project
Run the following commands inside the folder `./ElectronTestApp/`

**Note**: Use `powershell`

> `electronize build /target win` <br>
> `electronize build /target osx` <br>
> `electronize build /target linux`

The output will appear in the folder `./ElectronTestApp/bin/Desktop`
