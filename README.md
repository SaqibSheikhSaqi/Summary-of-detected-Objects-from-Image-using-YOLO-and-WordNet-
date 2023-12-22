Textual Summary of detected Objects from Image using YOLO and WordNet.
We used 303 pictures from the internet using Google Image search store in ‘SampleDataSetimages’ folder. The pictures had one or more things in them, and each picture was labeled with what was in it in file ‘InputImageData.xlsx’. 
File ‘Summary-of-detected-Objects-from-Image-using-YOLO-and-WordNet.ipynb’ will use ‘SampleDataSetimages’ and YOLO files (downloaded from https://pysource.com/2019/06/27/yolo-object-detection-using-opencv-with-python/) and generate following files as output:
-	Detected objects from all images as “DetectedImageObjects.xlsx”
-	Height, Width and Channel of each Image as “hwc-ImagesAnalysis.xlsx’
-	Definition of each detected object as “GeneratedDefinitions.xlsx”
-	Summary of each object with Rouge Scores “SummaryRoughScore.xlsx’
