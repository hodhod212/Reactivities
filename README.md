## dotnet new sln

## dotnet new webapi -n API

## dotnet new classlib -n Application

## dotnet new classlib -n Domain

## dotnet new classlib -n Persistence

## dotnet sln add API/API.csproj

## dotnet sln add Application

## dotnet sln add Persistence

## dotnet sln add Domain

## dotnet sln list

## cd API

## dotnet add reference ../Application

## cd ..

## cd Application

## dotnet add reference ../Persistence

## dotnet add reference ../Domain

## cd ..

## cd Persistence

## dotnet add reference ../Domain

## cd API

## dotnet watch run

## //shortcut ctrl . help us to fix problem when we get red underline

## cd ..

## dotnet tool list --global

## dotnet tool install --global dotnet-ef --version 5.0.8

## dotnet tool update --global dotnet-ef --version 5.0.8

## dotnet ef -h

## dotnet ef migrations add InitialCreate -p Persistence -s API

## cd ..

##

## ---

##

## cd API

## dotnet watch run

##

## ---

##

## cd ..

## git init

## dotnet new -l

## dotnet new gitignore

## git add .

## git branch -M main

## git remote add origin https://github.com/hodhod212/Reactivities.git

## git push -u origin main

## npx create-react-app client-app --use-npm --template typescript
