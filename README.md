# Colour Academy - CSS Variable Generator Website

## Routes

- "/" : Homepage
    - CSS Generator available here
- "/cssvariables" : CSS Generator Page
    - CSS Generator available here
- "/generator/saved" : view list of saved themes
    - reads localstorage

## Contexts

- Base Colour
    - Hex colour of new theme
- Current CSS theme
	- one theme list 
	- localstorage 
- List of CSS themes
	- array of theme list
	- localstorage 

## Data 

### Colour object

```js
{
    hex: "#00000",
    strength: 100,
    rgba: [255, 255, 255, 255]
}
```
### Theme list

```js
{
    name: "violet eggplant"
    colours: [
        Colour Objects go here
    ]
}
```
