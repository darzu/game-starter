Setup:
- Install git: https://git-scm.com/download/win
- Install typescript compiler: https://www.typescriptlang.org/#download-links

Fork this repository.

Clone:
```
cd ~/repos/
git@github.com:YOUR_ACCOUNT_NAME/game-starter.git
```

Run continuous compilation:
```
$ cd ~/repos/game-starter/
$ tsc -w
```

Run the server:
```
$ cd ~/repos/game-starter/public
$ python -m SimpleHTTPServer 4321
```

Visit the webpage:
```
$ open http://localhost:4321
```

To build the game
- Edit src/main.ts (DON'T edit public/main.js, it is automatically generated)
