# SportsStoreUbuntu

export DOTNET_ROOT=$HOME/dotnet
export PATH=$PATH:$HOME/dotnet

docker container create -i -t --name mycontainer alpine
docker run -it --name mycontainer2 alpine
sudo chmod 666 /var/run/docker.sock
sudo service docker start && docker-compose up -d

DOTNET_FILE=dotnet-sdk-7.0.403-linux-musl-arm64.tar.gz
export DOTNET_ROOT=$(pwd)/dotnet

mkdir -p "$DOTNET_ROOT" && tar zxf "$DOTNET_FILE" -C "$DOTNET_ROOT"

export PATH=$PATH:$DOTNET_ROOT:$DOTNET_ROOT/tools

docker container create -i -t --name mycontainer alpine
6d8af538ec541dd581ebc2a24153a28329acb5268abe5ef868c1f1a261221752

docker run -it --name mycontainer2 alpine
/ # echo hello world
hello world

sudo docker ps

dotnet new globaljson --sdk-version 6.0.100 --output FirstProje
dotnet new mvc --no-https --output FirstProject --framework net6.0
dotnet new sln -o FirstProject
dotnet sln FirstProject add FirstProject
dotnet new globaljson --sdk-version 6.0.100 --output SportsSln/SportsStore
dotnet new web --no-https --output SportsSln/SportsStore --framework net7.0
dotnet new sln -o SportsSln
dotnet new xunit -o SportsSln/SportsStore.Tests --framework net7.0
dotnet sln SportsSln add SportsSln/SportsStore.Tests
dotnet add SportsSln/SportsStore.Tests reference SportsSln/SportsStore
dotnet add package Microsoft.EntityFrameworkCore.Design --version 6.0.0
dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 6.0.0

Add @usinmg SportsStore.Infrastructure into ProductSummary.cshtml to solve PathandQuery() extention method problem
