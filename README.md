# Trimps.github.io

## The Game

Play the game on 
[Github](http://trimps.github.io/) "Play the game" 


## Modern Theme
![Modern Theme Example](https://i.imgur.com/msctQJX.png)

This is a redesign in the middle of development. The goal of this theme is to modernize the game and make it more relaxing to look at.

<dl>
  <dt>Current version:</dt>
  <dd>0.1.3</dd>
  
  <dt>Highest zone tested:</dt>
  <dd>Zone 330</dd>


  <dt>Optimized for Trimps version</dt>
  <dd>5.4.3</dd>

  <dt>only testen on</dt>
  <dd>1680 x 1050</dd>
  <dd>1600 x 900</dd>
</dl>

## Add modern theme to Trimps
Right click in the browser and open the inspector by clicking on Inspect.
Open the console tab an add the code below to the console.

*This theme doesn't stick. So when you reload the page you need to re-add the code*

```javascript
javascript: (function(){
  var modernCss = '<link rel="stylesheet" type="text/css" href="https://rawcdn.githack.com/StefGeraets/Trimps.github.io/feature/modern-theme/css/modern.min.css" />';
  document.querySelector('head').innerHTML += modernCss;
}());
```

After adding this you CAN still switch switch theme's from settings, but these aren't supported.
