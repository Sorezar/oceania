# oceania

The goal of this project is the detection and identification of sharks in real time and in videos for oceanologists, then automatic isolation of “interesting” observation sequences.
It is a Flask web interface for importing camera files/streams and logging detections.

### Model used
At first I was using a self made RCNN but after implementing YOLO I had better result so I switched to YOLO which was far simpler to use. 

### Example of a train batch
![val_batch1_pred](https://github.com/user-attachments/assets/0803300d-18ce-4723-9d96-135826b4db72)

### Video example of isolated "interesting" sequence
https://github.com/user-attachments/assets/be4a0b08-cf63-4e3b-95f8-0e169ec8686a

