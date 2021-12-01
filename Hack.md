# Dino Hack
Wanna hack a dino game?  
Try this! chrome://dino (**Real game**) or [**Trex runner**](https://www.trex-runner.com) (*Fake?* **game**)  
And show your friend that you are real **hacker**!

## 1. Open Console

- Right click anywhere on the page and click **Inspect**.
- Go to Console tab. This is where we will enter the commands to tweak the game.

## 2. Use Hack Command

### Speed Boost

Paste this command and hit enter to boost your speed.  
(You can change 100 to any number you want for it to be faster!)

```js
Runner.instance_.setSpeed(100) 
```

### Jump Boost

Paste this command and hit enter to jump higher.  
(You can change 10 to any number you want for it to jump higher!)

```js
Runner.instance_.tRex.setJumpVelocity(10)
```

### Undeath

Paste this command and hit enter to make you never lose the game.

```js
Runner.instance_.gameOver = () => {}
```

### Score Set

Paste this command and hit enter to set your own score.  
(You can change 500 to any number you want for more score!)

```js
Runner.instance_.distanceRan = 500
```
