# Lab 5: MLPR 

### Aim
The purpose of this lab was learning how distance metrics work and their role in real-world ML tasks. We were required to implement various distances, such as Euclidean and Manhattan, and also apply Haar-cascade for detecting faces in an image, and try out K-Means clustering.

---

### Method
1. **Face Detection:** I use `cv2` and the `haarcascade_frontalface_default.xml` file for find faces in the `Plaksha_Faculty.jpg` photo. I drew boxes around the faces that the model was able to detect.


2. **Implementing Distances:** I have written functions to calculate:
   * **Euclidean Distance:** Which is the straight line path.
   * **Manhattan Distance:** The "city block" or grid-like path.
   * **Hamming Distance:** This counts the differences in bits or strings.


3. **Clustering:** Used `KMeans` from sklearn to group data points based on this distance.

4. **Analysis:** I looked at how cross validation help the model generalize and how the "K" value in KNN affects the bias and the variance.


---

### Conclusion
This lab demonstrates that the choice of distance metric is super important because it changes how the algorithm "sees" the data. If we pick a bad metric, the classification or clustering results wont be accurate. I also learn that face detection with Haar-cascade is fast, but it sometimes miss faces if the lighting or angle is weird. Overall, understanding the balance between bias and variance is key for making a good model that dont overfit.
