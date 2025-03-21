Machine Learning Algorithm for Analyzing Urban Sprawl Expansion

 Overview:
This project applies machine learning techniques to analyze urban sprawl expansion in Vijayawada, India, from 2004 to 2023. The study focuses on land cover classification and temperature variations using Support Vector Machine (SVM) and Geographic Information Systems (GIS).

 Features:
- Satellite Image Analysis: Uses Landsat 5 and Landsat 8 satellite images to monitor land use changes.
- Urban Sprawl Detection: Classifies land cover into built-up, vegetation, water bodies, and barren land.
- Temperature Impact Analysis: Assesses changes in land surface temperature (LST) over the study period.
- Machine Learning Models: Utilizes SVM for classification and clustering techniques for pattern recognition.

 Data Collection:
- Satellite Images: Acquired from Landsat 5 (2004, 2014) and Landsat 8 (2023).
- Study Area: Vijayawada, Andhra Pradesh, India.
- Classification Categories: Built-up areas, vegetation, water bodies, and barren land.

 Methodology:
1. Preprocessing: Image correction and feature extraction.
2. SVM Classification: Training and testing using ground truth samples.
3. Accuracy Assessment: Evaluating classification results using confusion matrix.
4. Land Surface Temperature Analysis: Analyzing temperature variations using satellite thermal bands.
5. Results Interpretation: Examining urban expansion trends and their environmental impacts.

 Results:
- Urban Expansion: Built-up areas increased from 30.24 sq.km (2004) to 41.31 sq.km (2023).
- Vegetation Decrease: Vegetation cover reduced from 41.25 sq.km to 33.49 sq.km.
- Temperature Increase: LST rose from 27.5°C in 2004 to 36.5°C in 2023.
- Model Performance: Overall accuracy of 97% with SVM classification.

 Installation:
1. Clone the repository:
   
   git clone https://github.com/your-repository.git
   
2. Install dependencies:
   
   pip install -r requirements.txt
   
3. Run the analysis:
   
   python analyze_sprawl.py
   

 Dependencies:
- Python
- Google Earth Engine (GEE)
- OpenCV
- NumPy
- SciKit-Learn
- Matplotlib

 Contributors:
- Pamarthi Chenna Rao
- Kanuri Sai Dinesh
- Kesari Bhavani Prasad Reddy
- G. Geetha (Assistant Professor)

 Contact:
For any inquiries, please contact:
- chennapamarthi93@gmail.com
- kanurisaidinesh@gmail.com
- Prasadreddykesari2004@gmail.com
- geetha.g@vrsiddhartha.ac.in

