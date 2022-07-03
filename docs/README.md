# Главная страница

## sdfasdfsa

| Заголовок |     |     |     |
|:---------:|-----|-----|-----|
|   текст   |     |     |     |
|           |     |     |     |
|           |     |     |     |
|           |     |     |     |
|           |     |     |     |

```mapbox
{
  "map": {
    "container": "map",
    "style": "mapbox://styles/mapbox/light-v10",
    "center": [-77.04, 38.907],
    "zoom": 12
  },
  "layers": [
    {
      "id": "places",
      "type": "circle",
      "source": {
        "type": "geojson",
        "data": {
          "type": "FeatureCollection",
          "features": [
            {
              "type": "Feature",
              "properties": {
                "description":
                "<strong>Make it Mount Pleasant</strong><p><a href='#/page1'>Статья 1</a></p>"
              },
              "geometry": {
                "type": "Point",
                "coordinates": [-77.038659, 38.931567]
              }
            },
            {
              "type": "Feature",
              "properties": {
                "description":
                "<strong>Mad Men Season Five Finale Watch Party</strong><p><a href='#/page2'>Статья 2</a></p>"
              },
              "geometry": {
                "type": "Point",
                "coordinates": [-77.003168, 38.894651]
              }
            },
            {
              "type": "Feature",
              "properties": {
                "description":
                "<strong>Big Backyard Beach Bash and Wine Fest</strong><p><a href='#/page2'>Статья 3</a></p>"
              },
              "geometry": {
                "type": "Point",
                "coordinates": [-77.090372, 38.881189]
              }
            }
          ]
        }
      },
      "paint": {
        "circle-color": "#23822e",
        "circle-radius": 6,
        "circle-stroke-width": 2,
        "circle-stroke-color": "#ffffff"
      }
    }
  ]
}
```
