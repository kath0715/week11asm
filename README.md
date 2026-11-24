# PixPlot Visualization — B24 Photos + Additional Images

This is an interactive PixPlot visualization containing 36 images:
- 29 B24 archaeological photos (B24P03–B24P31)
- 7 additional images from the "new" folder

## How to deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload ALL files from this folder to the repository root
3. Go to Settings > Pages > Source, select your branch and **/(root)**
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/` in 1-2 minutes

## How to use the viewer

- Zoom/pan the scatter plot to explore image relationships
- Switch between UMAP (similarity), grid (alphabetic), and RasterFairy layouts using the toolbar
- Click clusters to see hotspot highlights
- Hover over individual images to view them at full resolution

## Notes

- Images are arranged by visual similarity using UMAP dimensionality reduction on InceptionV3 neural network features
- Clusters are automatic visual similarity groupings from KMeans — not guaranteed subject labels
- The `.nojekyll` file tells GitHub Pages to serve files as-is without Jekyll processing
