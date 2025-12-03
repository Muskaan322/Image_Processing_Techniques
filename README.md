Tasks Overview
Task 1: Image Zoom In and Zoom Out

Description:
Resize images using custom bilinear interpolation.

Zoom out an image by reducing its DPI.

Zoom in back to the original size while preserving image quality.

Libraries Used: Pillow, Matplotlib

Key Functions:

resize_image_handler() – Custom bilinear interpolation for resizing.

zoom_out() – Shrinks image based on DPI ratio.

zoom_in() – Restores image to original size.

display_images() – Display original, zoomed-out, and zoomed-in images.

Task 2: Log Transformation and Power-Law (Gamma) Transformation

Description:
Enhance grayscale images using pixel intensity transformations:

Log Transformation: Expands darker pixel values.

Power-Law Transformation: Adjusts image brightness using gamma correction.

Libraries Used: OpenCV, NumPy, Matplotlib

Key Parameters:

log_scaling_constant – Controls intensity scaling for log transform.

gamma_value – Controls brightness in power-law transform.

Task 3: Reducing Intensity Levels (Quantization)

Description:
Reduce the number of grayscale intensity levels in an image to simplify or compress it.

Input: Desired number of intensity levels (must be a power of 2, e.g., 2, 4, 8, 16).

Libraries Used: OpenCV, NumPy, Matplotlib

Key Function:

quantize_intensity_levels() – Reduces the number of intensity levels for a grayscale image.

Task 4: Region-Based Histogram Equalization

Description:
Improve local contrast by applying histogram equalization to a selected region (ROI) in the image.

Note: Mouse-driven ROI selection works best on local machines (e.g., VS Code), not Google Colab.

Libraries Used: OpenCV, NumPy, Matplotlib

Key Functions:

apply_histogram_equalization() – Applies histogram equalization to a given ROI.

onselect() – Handles interactive ROI selection using RectangleSelector.
