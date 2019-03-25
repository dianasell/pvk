# Git kasutamise meelespea

Git repo initsialiseerimine:

``` 
$ git init
```

Faili nimega fail lisamine  git-ile ja commitimine:

``` 
$ git add Fail
$ git commit -m "Lisasin failli nimega Fail"
```

repo staatuse kontroll

``` 
$ git status
```

mitme failide lisamine git-ile ühe committi jaoks

``` 
$ git add my-first-file.ts another-file.js my-third-file.rb
$ git commit -m "Add three files"
```

giti logide vaatamine

``` 
$ git log
```

git puu vahetamine

``` 
$ git checkout <name>
```

giti taastamine

``` 
$ git reset
```

commitide tühistamine 

``` 
$ git reset --soft HEAD^
```