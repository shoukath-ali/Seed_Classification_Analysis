# Seed_Classification_Analysis

I'm a data scientist working at a large sunflower seed processing factory. The company
produces different varieties of sunflower seeds for the food and agricultural sectors. Ensuring
quality and proper classification of sunflower seeds is crucial to the business. As the company
scales, massive amounts of seed data are collected from sensors and quality control
checkpoints. Your role is to develop a machine learning model that can classify the sunflower
seeds based on their characteristics. The goal is to improve classification speed and accuracy
for efficient seed sorting into categories such as "high quality" and "low quality."

### Dataset Information:
You will be working with a dataset containing various geometric and physical characteristics of
sunflower seeds. The goal is to build a binary classification model that predicts the seed’s
quality (e.g., High Quality, Low Quality) based on its features.
### Variable Descriptions:
<p>
Total Area: The total surface area of the sunflower seed within its boundaries, representing
how much space the seed covers.

Boundary Length: The total length around the outer edge of the sunflower seed, or its
circumference.

Max Length:The length of the longest straight line that can be drawn across the sunflower
seed, corresponding to the seed’s major axis (typically from one end to the other).

Min Length : The length of the shortest straight line that can be drawn across the sunflower
seed, perpendicular to the long axis, representing the minor axis.
Seed Eccentricity: A measure of how stretched or oval-shaped the sunflower seed is. A
value of 0 indicates a perfect circle, and a value approaching 1 indicates a more elongated
shape.

Convex Boundary Area: The total surface area of the smallest convex shape (like a
tight-fitting shell) that can fully enclose the sunflower seed. It represents how much area is
covered by a tightly drawn boundary around the seed.

Coverage Ratio: The ratio of the sunflower seed’s area to the area of the smallest rectangle
that can fully enclose the seed. It indicates how efficiently the seed fills its bounding box.
Circular Diameter: The diameter of a circle that would have the same surface area as the
sunflower seed. This is calculated as if the irregularly shaped seed were a perfect circle.

Shape Ratio: A measure of how closely the sunflower seed's shape resembles a perfect
circle. It's the ratio of the seed’s area to the area of a circle with the same perimeter. The more
compact the shape, the closer it is to a circle.

Convexity Factor: The ratio of the sunflower seed's actual area to the area of its convex hull.
This gives an indication of how much the seed's shape deviates from being perfectly convex
(solid). A solidity close to 1 means the shape is almost fully convex.

Shape Roundness: A measure of how circular the sunflower seed is, without considering any
roughness or distortion at the edges. A rounder seed will have a higher roundness value.
Ovality Index: The ratio of the seed’s major axis length to its minor axis length. This gives an
indication of the seed's overall shape—whether it is more elongated (high aspect ratio) or
more circular (low aspect ratio).
</p>
<h3>
Currently, the factory relies on manual inspection and basic sorting techniques, which are
time-consuming and prone to errors. With thousands of seeds passing through quality control
every hour, the company needs a more efficient and accurate method to classify the seeds
into categories, such as “high quality,” and “low quality.” By building a predictive model using
the available data, your team aims to automate the classification process, improving speed
and accuracy while reducing costs. The challenge is to use big data technologies, like
PySpark, to handle the large volume of data and create a model to provide a binary
classification aiding in risk assessment and decision-making processes for product
distribution.
</h3>
