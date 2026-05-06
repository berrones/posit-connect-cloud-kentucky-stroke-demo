# Kentucky Stroke Demo

Minimal Quarto project for Posit Connect Cloud deployment testing.

## Files

- `index.qmd`: Quarto document with a Kentucky county choropleth
- `data/kentucky_counties.geojson`: local county boundary file for offline rendering

## Render locally

```bash
quarto render
```

## Notes

- The stroke data is fake and generated at render time.
- The Kentucky county boundaries were derived from U.S. Census cartographic boundary shapefiles.
