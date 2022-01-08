# Dataset description

## Overall structure
- The dataset includes `/train` and `/test` folders
- The training set and the test set contain 198 and 50 images with annotation, respectively.
- Originally, the dataset is collected for training YOLO with Darknet: The image's format is `.png` while its annotation's format is `.xml` .

## Specificality
- The images and their annotations are named after the time they have been captured, with the following format: YYYY-MM-DD-hh-mm-ss.*
- Annotation `xml` format:
Sample entry:
### Dataset Format ###

Sample Entry:
~~~
<annotation>
	<folder>AlertTrap-Dataset/train</folder>
	<filename>2020-04-11-08-15-00.jpg</filename>
	<path>AlertTrap-Dataset/train/2020-04-11-08-15-00.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>3280</width>
		<height>2464</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>yellowFly</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>1157</xmin>
			<ymin>254</ymin>
			<xmax>1447</xmax>
			<ymax>489</ymax>
		</bndbox>
	</object>
</annotation>
~~~
