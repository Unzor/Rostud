# Rostud
JavaScript tool for opening Roblox games and their source.

# Usage
To use Rostud, use one of these three functions:

```rostudObject.copyGame(game id)``` - Opens a (uncopylocked) game in Roblox Studio.

```rostudObject.openStudio()``` - Opens Roblox Studio.

```rostudObject.openGame(game id)``` - Opens a game in the Roblox player. (Beta, most likely will not work)

Sample code:
```html
<!DOCTYPE HTML>
<html>
<head>
<script src="https://unzor.github.io/Rostud/rostud.js">
</head>
<body>
<h1>
Rostud sample
</h1>
<a href="javascript:location.href=myRostudObject.copyGame(6691388484)">Open My Game!</a>
</body>
</html>
```
