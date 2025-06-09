# ez-frcnn.inferencing

---
``` py
def inferencing.load_model(model_name, MODEL_DIR, NUM_CLASSES):
```
::: library.inferencing.load_model

---
``` py
def inferencing.saveResultsToCSV(csvFileName, results, OUT_DIR):
```
::: library.inferencing.saveResultsToCSV

---
``` py
def inferencing.inference_video(DIR_TEST, OUT_DIR, vidName, model, detection_threshold, CLASSES, save_detections=False):
```
::: library.inferencing.inference_video

---
``` py
def inferencing.inference_images(DIR_TEST, model, OUT_DIR, detection_threshold, CLASSES, tqdmBar, inf_fig):
```
::: library.inferencing.inference_images

---
``` py
def inferencing.load_and_preprocess_image(file_path, target_size=(800, 800)):
```
::: library.inferencing.load_and_preprocess_image

---
``` py
def inferencing.scale_boxes_to_original(boxes, original_size, resized_size=(800, 800)):
```
::: library.inferencing.scale_boxes_to_original

---
``` py
def inferencing.inference_images_fast(DIR_TEST, model, OUT_DIR, detection_threshold, CLASSES, tqdmBar, batch_size=4):
```
::: library.inferencing.inference_images_fast

---
``` py
def inferencing.inference_images_figs(DIR_TEST, model, OUT_DIR, detection_threshold, CLASSES):
```
::: library.inferencing.inference_images_figs