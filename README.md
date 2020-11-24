# Gitpod_Dotnet

```
dotnet new sln --name Gitpod_Dotnet
dotnet new mvc -au Individual -o Gitpod_Dotnet.MVC
dotnet sln add Gitpod_Dotnet.MVC/Gitpod_Dotnet.MVC.csproj
dotnet new gitignore
echo "# Gitpod_Dotnet" >> README.md
echo "image: gitpod/workspace-dotnet" >> .gitpod.yml
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/ecoprintec/Gitpod_Dotnet.git
git push -u origin master
```