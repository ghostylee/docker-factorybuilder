# docker-factorybuilder
timesys factory build environment
## How to use
```
cd $PROJECT_ROOT
```

```
docker run -t --rm -v $PWD:/home/worker/building ghostylee/factorybuilder make
```

or set alias for

bash
```
echo "alias factorybuilder='docker run -t --rm -v \$PWD:/home/worker/building ghostylee/factorybuilder'" >> .bashrc
```
zsh
```
echo "alias factorybuilder='docker run -t --rm -v \$PWD:/home/worker/building ghostylee/factorybuilder'" >> .zshrc
```
fish
```
echo "alias factorybuilder='docker run -t --rm -v \$PWD:/home/worker/building ghostylee/factorybuilder'" >> .config/fish/config.fish
```
then run

```factorybuilder make```
