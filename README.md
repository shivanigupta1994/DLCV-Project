
# Layered Representations from a Single Image

## Objective
Generate interpretable layered representations from a single RGB image.

## Deliverables
- Semantic RGBA layers
- Depth ordering from near to far
- Recomposition from layers
- Albedo and shading split per layer

## Semantic Layers
1. Person
2. Car
3. Tree
4. Road
5. Sun
6. Mountains
7. Ground
8. Sky

## Depth Order
Near to Far:

Person → Car → Tree → Road → Sun → Mountains → Ground → Sky

## Technologies Used
- Python
- NumPy
- PIL / Pillow
- Matplotlib

## Output
The project outputs separate RGBA, albedo, and shading images for every semantic layer.
