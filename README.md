## [Tibetan Game](https://shangshungfoundation.github.io/tibetan_game/)
[1st Merigar Hackathon project](https://github.com/ShangShungFoundation/1st_merigar_hackathon) organized by [Shang Shung Foundation](shangshungfoundation.org)

**[Website](https://shangshungfoundation.github.io/tibetan_game/)** | 
[Github](https://github.com/ShangShungFoundation/tibetan_game/) | 
[Tasks](https://github.com/ShangShungFoundation/tibetan_game/projects/1) | 
[Issues](https://github.com/ShangShungFoundation/tibetan_game/issues)

## Project Coordinator: 

## Description
Online tibetan turn game following simple rules with simple interface. 
Proposed game is _Mig Mang_ (tib. Many Eyes)

## Purpose
Developement of online 2 paricipant game with optional AI
and porting it to native mobile apps using React Native

## Who it’s for? 
Anyone interested

## Why they would want to use it?
Fun, developement of personal logic skills, strategy

## Expected Features: 
- Unicode support
- Multilanguage

## Checkpoints: 
- [ ] Interface done 
- [ ] Game logic implemented
- [ ] Players interaction, turns (backend)
- [ ] Players chat
- [ ] AI [Monte_Carlo_tree_search](https://en.wikipedia.org/wiki/Monte_Carlo_tree_search)
- [ ] Mobile versions

## Technologies: 
[JavaScript](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics), [ES6](https://babeljs.io/learn-es2015/), [React](https://facebook.github.io/react/), [Bootstrap](http://getbootstrap.com/getting-started/), [Browserify](https://codeutopia.net/blog/2016/01/25/getting-started-with-npm-and-browserify-in-a-react-project/)

## Backend:
node.js, with [websockets](https://devcenter.heroku.com/articles/node-websockets) or Webrtc messanging

## Difficulty: 
Medium/High

## Recommended toolset:
   - Editor: [Sublime Text 3](https://www.sublimetext.com/3) with [react support](https://medium.com/@adrianli/setting-up-sublime-text-3-for-reactjs-3bf6baceb73a), [Atom](https://atom.io/) [with react](https://medium.com/productivity-freak/my-atom-editor-setup-for-js-react-9726cd69ad20) or Vim ;)
   - Git client: Shell, [Git Desktop](https://desktop.github.com/)

## Resources:
### Ming Mang Game
tib. many eyes
* [wikipedia](https://en.wikipedia.org/wiki/Ming_Mang_(game))
* http://homepages.di.fc.ul.pt/~jpn/gv/mingmang.htm
* http://www.gosymposium.org/papers/peter_shotwell_migmang.docx

Very similar to Othello or Reversi game
* https://github.com/kana/othello-js
* https://github.com/jbub/reversi-js
* https://www.reddit.com/r/reviewmycode/comments/59wc58/javascript_and_p5js_othello_game/
* https://www.lemoda.net/games/othello/index.html
* http://othellogame.net/
* http://en.doc.boardgamearena.com/Tutorial_reversi
* https://www.somewhereincanada.com/games/board_/reversi3/ https://www.somewhereincanada.com/games/board_/reversi3/js/reversi.js
* http://www.p-six.de/othello-game-replayer.html
* https://www.npmjs.com/package/reversi
* https://www.youtube.com/watch?v=EngA8C4Xpno

### multiplayer game in javascript
* https://hackernoon.com/how-to-build-a-multiplayer-browser-game-4a793818c29b
* http://www.dynetisgames.com/2017/03/06/how-to-make-a-multiplayer-online-game-with-phaser-socket-io-and-node-js/
* http://lance.gg/
* http://buildnewgames.com/real-time-multiplayer/
* https://couchfriends.com/news/4-built-a-real-time-multiplayer-game-with-html5-in-less-than-30-minutes

## node
* https://nodeschool.io/

## Starting Project
Assuming that you have node.js installed globally More [info](https://github.com/facebookincubator/create-react-app)
```sh
npm install -g create-react-app

create-react-app tibetan_game
cd tibetan_game/
npm install --save gh-pages
git init
rm package.json README.md
git add .
git commit -m "First commit"
git remote add origin https://github.com/ShangShungFoundation/tibetan_game.git
git pull origin master --allow-unrelated-histories
npm start

```
###  Start Project
`npm start`

###  Deploy Project
`npm run deploy`

## Acknowledgements
We are grateful to following persons for their ideas and collaboration:

### Licence: [MIT License](LICENSE)
