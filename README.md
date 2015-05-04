# gitbatch

Batch file for affecting multiple git repos in a specific folder

## Installation

```shell
cd ~/bin/
git clone git@github.com:4stern/gitbatch.git
cd gitbatch
chmod +x gitrepos
echo "export PATH=$PATH:~/bin/" >> ~/.profile
```

Edit the file and edit the line by adding your folder with your git-repos
```
zielverzeichnis="/gitprojects/"
```

## Usage

Write where ever you are:
```
gitrepos status
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Robert Beyer <4sternrb@googlemail.com>

## License

MIT
