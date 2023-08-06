# Image-compression-using-K-means-algorithm
K-means is a clustering algorithm used to group similar data points in a dataset. The basic idea is
to group similar pixels of an image together and represent them using their mean value. The
motivation for this project is that as new digital data is generated every single day, it is essential to
reduce the cost for storage or transmission of images.

I considered a (640, 427) RGB image. All the pixel values of the image are clustered into ‘k’
clusters until the algorithm converges. Then, each pixel value is replaced with the centroid value
of its cluster. These new values are used to generate the compressed image when clusters = ‘k’.

The image was converted to a 2D array of pixel values, where each row represents a pixel and
each column represents a color channel.

I considered cluster values K = 2, 5, 10, 20, 50, 100. The size of the compressed images decreased
compared to the original size of the image. The quality of the compressed image increases as the
number of clusters increase. As the number of clusters increased, the time taken to compress the
images increased.

Some advantages are it is easy to implement, and the algorithm works particularly well for images
with large areas of uniform color. And some disadvantages are loss of image quality and may not
perform well on complex images.

Image by <a href="https://pixabay.com/users/sarajuggernaut-28237/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=167089">sarajuggernaut</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=167089">Pixabay</a>
