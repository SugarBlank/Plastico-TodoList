# Plastico-TodoList
Simple Console Todo list that utilizes SQLite.

# Screenshots
![image](https://user-images.githubusercontent.com/64178604/112048481-d72bfd80-8b24-11eb-8b79-c39b34e4a328.png)
![image](https://user-images.githubusercontent.com/64178604/112049182-aa2c1a80-8b25-11eb-9e2f-b47241265cde.png)
![image](https://user-images.githubusercontent.com/64178604/112049249-bf08ae00-8b25-11eb-89d3-02de41ae54f3.png)

# Technologies
Project is created with:
* [CommandLineParser 2.9.0](https://www.nuget.org/packages/CommandLineParser/2.9.0-preview1)
* [SQLite Package 1.0.113.7](https://www.nuget.org/packages/System.Data.SQLite/)
* [DesktopNotifications.FreeDesktop](https://www.nuget.org/packages/DesktopNotifications.FreeDesktop/)
* [C# Dotnet 5.0103](https://dotnet.microsoft.com/)

## Setup
Install the [Dotnet 5.0103](https://dotnet.microsoft.com/) framework for C# and download the [SQLite 1.0](https://www.nuget.org/packages/System.Data.SQLite/)  and [CommandLineParser 2.9.0](https://www.nuget.org/packages/CommandLineParser/2.9.0-preview1) nuget package.
```
$ gitclone https://github.com/SugarBlank/Plastico-TodoList/
$ cd ../Plastico-TodoList
$ dotnet add package CommandLineParser --version 2.9.0-preview1
$ dotnet add package System.Data.SQLite.Core --version 1.0.113.7
$ dotnet add package DesktopNotifications.FreeDesktop --version 1.0.0
$ sudo dotnet publish -r linux-x64 -o /usr/local/bin/ /p:PublishTrimmed=true /p:PublishSingleFile=true
Publish trimmed is for the file to remove uneeded dependencies since dotnet uses a lot of dependencies, and single file is for the app to be compiled as a single file than multiple dlls.
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Suggestions for places to clean up code would be great too.

Please make sure to update tests as appropriate.
