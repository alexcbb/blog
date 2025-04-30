---
title: "Dataset Guidelines" 
thumbnail: /blog/assets/
authors:
- user: danaaubakirova
- user: Beegbrain
- user: villekuosmanen
---

# LeRobot data collection guidelines : How-to collect a proper dataset ?

## Introduction
As the number of users of the LeRobot library grows substantially, the volume of collected data is also increasing rapidly. Our ultimate goal is to gather the largest community dataset ever, primarily collected with affordable hardware. This initiative has the potential to become the biggest open-source robotics dataset built by the community.

In recent weeks, the number of datasets has grown exponentially. However, with this growth comes the responsibility to ensure that the datasets remain clean, well-organized, and of high quality. This guide aims to provide clear instructions on how to collect a proper dataset, ensuring that our collective efforts result in a valuable and reliable resource for the robotics community.

## Better data = Better models ?
Why does data quality matter? In fact, data is the key behind the best models. Poor-quality data results in poor downstream models. High-quality datasets lead to better-performing algorithms, which in turn accelerate innovation and discovery in the field. By maintaining high standards for our datasets, we can ensure that the LeRobot initiative reaches its full potential and becomes an invaluable resource for researchers and enthusiasts worldwide.

## What is a good dataset ?

A "good dataset" in robotics is characterized by several key attributes. These include:
### Image Quality

- *Two Cameras*: Use two cameras to capture different angles and perspectives.
- *Steady Video*: Ensure that the video footage from the cameras is steady and free from unnecessary movements.
- *Neutral Lighting*: Maintain stable, neutral lighting that is not too yellow or harsh.
- *Consistent Exposure and Focus*: Keep the exposure and focus consistent throughout the recording.
- *Leader Arm Visibility*: Ensure that the leader arm does not appear in the frame.
- *Minimal Distractions*: The only moving objects should be the follower arm and the things it is interacting with. Avoid having human arms or bodies in the frame.
- *Static Background*: Use a static, non-distracting background. If variations are necessary, they should be controlled.
- *High Resolution*: Record at a resolution of 720p or higher to capture detailed information.

### Metadata Accuracy
- *Robot Type*: Clearly specify the correct robot type in the metadata.
- *Frame Rate*: Prefer, if possible the use of a camera that records at approximately 30 frames per second (fps).
- *Consistent Metadata*: If episodes are deleted from the video folder, ensure that the metadata files are updated accordingly to maintain consistency.

### Task Annotation
- *Detailed Description*: Use the task field to describe exactly what the robot is doing. For example, "Pick the yellow lego and put it in the box."

By adhering to these guidelines, we can ensure that the datasets contributed to the LeRobot initiative are of the highest quality, setting a new standard for excellence in the field of robotics.

## Additionnal ressources