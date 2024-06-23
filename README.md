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
- Localstorage manager for list of CSS themes
    - Array of theme lists
- Localstorage manager for current CSS theme
    - One theme list
- List of CSS themes
    - Array of theme lists
- Current CSS Theme
    - One theme list

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
