# Pattern-Recognition-Final-Project
Project from my CSC 732: Pattern Recognition and Neural Networks class for the Spring 2020 term at CUNY College of Staten Island. This project focused on utilizing a Convolutional Neural network (CNN) for a classification, and was split into two parts:
Part 1 centered around the classic Dogs-vs-Cats problem or classifying different images into either the cat or dog category.
Part 2 centered around classifying different polyhedral dice and utilizing image augmentation to minimize the effect of imbalanced datasets when training a CNN. Also we used a voting system to create an ensemble classifier in hopes of improving performance on the dataset.

<h1>Dataset Used:</h1>
<h2>Dogs-vs-Cats</h2>
<p>The dogs vs cats dataset refers to a dataset used for a Kaggle machine learning competition held in 2013.

The dataset is comprised of photos of dogs and cats provided as a subset of photos from a much larger dataset of 3 million manually annotated photos. The dataset was developed as a partnership between Petfinder.com and Microsoft.

The dataset was originally used as a CAPTCHA (or Completely Automated Public Turing test to tell Computers and Humans Apart), that is, a task that it is believed a human finds trivial, but cannot be solved by a machine, used on websites to distinguish between human users and bots. Specifically, the task was referred to as “Asirra” or Animal Species Image Recognition for Restricting Access, a type of CAPTCHA We create our own subset that includes 2,000 training images, 1,000 validation images, and 1,000 testing images.</p>

<ul>
    <li><strong>Number of Instances: </strong>25,000</li>
    <li><strong>Number of Classes: </strong>2</li>
    <li><strong>Image Dimensions: </strong>Varies</li>
    <li><strong>Number of Channels: </strong>3</li>
</ul>

<h2>Dice: d4, d6, d8, d10, d12, d20 Images</h2>
<p>Beginner set of 16,000 custom images for categorizing polyhedral dice. 
    Polyhedral dice vary in color, and images are taken at different angles over different background types: blank, colored, and wood. All images were created, edited, and sorted by Mario Lurig.

Fixed camera positions (minimum 2 angles) used to capture video on a rotating platform with two white lights
Minimum 5 different dice used on 6 different backgrounds (white and various colors)
Video was then exported as images and then batch cropped to 480x480
Handheld camera moved over 5+ dice on various wood surfaces (minimum 2) using natural lighting
Video edited and exported to images then batch cropped to 480x480
Images that were partially out of crop were manually removed
</p>

<ul>
    <li><strong>Number of Instances: </strong>16,000</li>
    <li><strong>Number of Classes: </strong>6</li>
    <li><strong>Image Dimensions: </strong>480x480</li>
    <li><strong>Number of Channels: </strong>3</li>
</ul>
