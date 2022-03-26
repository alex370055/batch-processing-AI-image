
### Installation
```bash
sudo pip install -r requirements.txt
```
### Usage

```bash
python xmltotxt.py -xml xml -out out
```

### Example

Input xml file.

```xml
<annotation>
	<filename>image-0000016.jpg</filename>
	<size>
		<width>1920</width>
		<height>1080</height>
	</size>
	<object>
		<name>sedan</name>
		<bndbox>
			<xmin>75</xmin>
			<ymin>190</ymin>
			<xmax>125</xmax>
			<ymax>210</ymax>
		</bndbox>
	</object>
</annotation>
```
Output text file.
```text
5 0.052083 0.185185 0.026042 0.018519
```

### Motivation

I used [xml-to-txt](https://github.com/Isabek/XmlToTxt)for YOLOv4，and Modified the required orientation transformation for a large number of training images and definitions.
