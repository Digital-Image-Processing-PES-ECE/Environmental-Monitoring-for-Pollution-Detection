# Project Name

### Project Description:
#### Summary - This project utilizes aerial imagery to detect and quantify pollution levels, such as oil spills and algal blooms, through color and texture analysis. By segmenting and analyzing distinct visual features of polluted regions, this approach provides an efficient and scalable solution for environmental monitoring and rapid pollution assessment.

#### Course concepts used - 
1. - 	Thresholding: A segmentation technique that uses intensity values to distinguish between pollution and non-pollution areas.
2. -	Morphological Operations: Used to clean up small, irrelevant regions in the binary image by removing noise.
3. -	Statistical Analysis: Calculation of pollution area percentage, average intensity, and Pollution Index for quantitative assessment.

   
#### Additional concepts used -
1. - Overlay Visualization: Mapping detected regions onto the original image for visualization. It helps to validate the detection and measurement process.

   
#### Dataset - 
Google earth engine, NASA’s earth observatory, Sentinal-2 satellite data

#### Novelty - 
1. - Detection Technique: Combines color and texture analysis.
2. - Pollution Severity Assessment:	Custom Pollution Index for severity
3. - Noise Handling: Automatic noise smoothing & morphological operations
4. - Cost & Scalability: Low-cost, scalable using aerial imagery
5. - Quantitative Metrics: Area & intensity-based quantification

   
### Contributors:
1. Khushi J Mule (PES1UG22EC122)
2. Poorvi S Bhat (PES1UG22EC193)
3. Priya S (PES1UG22EC215)

### Steps:
1. Clone Repository
[```git clone https://github.com/Digital-Image-Processing-PES-ECE/Environmental-Monitoring-for-Pollution-Detection
.git `](https://github.com/Digital-Image-Processing-PES-ECE/Environmental-Monitoring-for-Pollution-Detection)``

2. Install Dependencies
```pip install -r requirements.txt```

3. Run the Code
```python main.py (for eg.)```

### Outputs:
* Important intermediate steps
* Final output images
  
### References:
1. - Data Set: Google earth engine
                NASA’s earth observatory
                Sentinal-2 satellite data

2. - Code reference: Course Contents

   
### Limitations and Future Work:

Limitations
1. Image Quality Dependency: Accuracy is affected by low-resolution, poor lighting, and environmental noise.
2. Surface-Level Detection: Limited to visible surface pollution; cannot detect underwater contaminants.
3. Manual Thresholds: Requires manual tuning, reducing adaptability to different conditions.
4. False Positives: Susceptible to mistaking natural elements like vegetation or debris for pollution.

Future Work
1. Machine Learning: Implement deep learning for automatic, more accurate pollution detection.
2. Real-Time Processing: Optimize for faster, real-time analysis using GPU or edge computing.
3. Multi-Spectral Imaging: Use multi/hyperspectral data for detecting a broader range of pollutants.
4. Adaptive Techniques: Develop adaptive thresholding for better accuracy across diverse environments.
5. Temporal Analysis: Add time-based monitoring to track pollution changes and predict future events.
