# Image Matcher: Profile Picture and Banner Matching Tool
This tool helps users find the best matches for their profile pictures against a set of banners (and vice-versa) based on color distribution (Histogram Matching) and image structure (Feature Matching). It's a helpful utility for those wanting to choose banners that harmonize well with their profile photos.

Features
Histogram Matching: Compares the color distribution of images.<br>
Feature Matching: Matches structural features between images.<br>
Overlay Generation: Places the profile picture onto the top-scoring banners, making visualization of matches easier.
Custom Preference: Allows users to set a preference for color matching, feature matching, or both.
<br>
Prerequisite
Python 3.x
OpenCV (cv2)
NumPy
<br>
Installation<br>
Clone the repository:
```git clone https://github.com/YourUsername/ImageMatcher.git```
Navigate to the directory:
```cd ImageMatcher```
Install the required packages:
```pip install opencv-python numpy```
Usage<br>
Run the main script:
```python main.py```
<br>
Follow the prompts to provide the required image and directory paths, and set your matching preferences.
The tool will display the top matches based on your input and generate overlay images for visualization.
<br>
Contribution
Contributions are welcome! Please make sure to create a pull request for any enhancements or bug fixes.

License
-
