XML

### Dataset Details
- **RGB Images:** These are standard color images captured using visible light cameras.
- **Infrared (IR) Images:** These images are captured using infrared sensors, providing unique data for low-light and night-time conditions.
- **Annotations (XML files):** The XML files contain annotation information, including bounding boxes, labels, and object locations. These annotations can be used to train models for tasks like object detection or segmentation.

### Example Annotation Format (XML)

Here is an example of what a typical XML file for annotations looks like:
---xml
<annotation>
    <folder></folder>
    <filename></filename>
    <path></path>
    <source>
        <database></database>
    </source>
    <size>
        <width></width>
        <height></height>
        <depth></depth>
    </size>
    <object>
        <name></name>
        <difficult></difficult>
        <bndbox>
            <xmin></xmin>
            <ymin></ymin>
            <xmax></xmax>
            <ymax></ymax>
        </bndbox>
    </object>
</annotation>
