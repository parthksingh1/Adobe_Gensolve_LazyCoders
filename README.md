# Curvetopia

## Team: Lazy_Coders

### Project Overview

Curvetopia focuses on advancing the handling of curves in 2D Euclidean space, with a progression from simple closed curves to more intricate shapes involving symmetry and curve completion.

### Key Features

1. **Cubic Bézier Curve Transformation**:
   - Convert line art into smooth cubic Bézier curves.
   - Simplify by transforming polylines into regularized, symmetrical curves.

2. **Shape Recognition**:
   - **Straight Lines**: Regularization of basic linear shapes.
   - **Circles and Ellipses**: Identification of curves with specific distance properties.
   - **Rectangles and Rounded Rectangles**: Differentiation between standard and curved-edge rectangles.
   - **Regular Polygons**: Identification of polygons with equal sides and angles.
   - **Star Shapes**: Recognition of shapes with radial arms.

3. **Symmetry in Curves**:
   - Focus on identifying reflection symmetries, even when Bézier curves create identical shapes differently.
   - Curve fitting to symmetric points.

4. **Curve Completion**:
   - Use of computer vision techniques to complete incomplete curves.
   - Handle various levels of shape occlusion, including planarized curves.

### Expected Results

1. **Isolated Shapes**: Single polyline shapes.
2. **Fragmented Shapes**: Multiple polylines forming shapes.
3. **Connected Occlusion**: Shapes that are partially blocked but still connected.
4. **Disconnected Occlusion**: Shapes fragmented into multiple paths.

### Evaluation Criteria

- Measurement of regular geometric shapes and symmetry, including:
  - Rectangles with two lines of symmetry.
  - Circles with radial symmetry.

### Visualization

- **SVG Format**: For accurate and visually appealing representation of curves.
