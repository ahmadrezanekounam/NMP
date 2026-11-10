# Neko MIC Predictor (NMP) 🧬💻
**An Explainable Machine Learning Framework for Forecasting the MIC and MFC of Antifungal Metal Nanoparticles**

Welcome to the official repository for the **Neko MIC Predictor (NMP)**. This AI-powered software provides a streamlined graphical user interface (GUI) to predict Minimum Inhibitory Concentration (MIC) and Minimum Fungicidal Concentration (MFC) values using tree-based ensemble algorithms (Random Forest and XGBoost).

---

## 🚀 How to Use the Software

Follow these sequential steps to utilize the predictive modules effectively:

### Step 1: Load the Knowledge Base
Download the NMP_DataBase.xlsx provided in this repository and load it into the software to initialize the XGBoost engines.
Before running any predictions, the software requires a foundational dataset to calibrate the machine learning models.
1. Open the NMP software.
2. Click on the **"Load Knowledge base (Excel)"** button located at the top of the interface.
3. Select your prepared Excel database to import the data into the software.

### Step 2: Single Prediction Module
Designed for the rapid *in silico* estimation of individual nanoparticle formulations.
1. Go to the **"Single Prediction"** tab.
2. Select the **Nanoparticle (NP)** type (e.g., Ag, Cu, Fe).
3. Choose the **Synthesis Method** (Chemical, Physical, or Biological).
4. If "Biological" is selected, specify the **Bio Source** (Plant, Fungi, Bacteria).
5. Set the exact **Size (nm)** using the input slider (Range: 2 to 270 nm).
6. Click the **"Predict Result (MIC & MFC)"** button.
7. View the estimated results and download the detailed prediction output as a PDF file.

### Step 3: Batch Analysis Module
Engineered for high-throughput screening of multiple formulations or large datasets.
- **Manual Entry:** Select individual parameters (NP, Method, Source, Size) and click the **"+ Add"** button to append multiple rows to the batch list.
- **Automated Entry:** Click the **"Excel"** button to upload a large dataset containing multiple test cases at once.
- Once your list is ready, click **"Process Batch Predictions"** to analyze the entire dataset simultaneously. 
- Export the final tabulated results via the **"Download Batch Report (PDF)"** button.

### Step 4: Validate Data via AI Insights (⚠️ Mandatory)
**Crucial Note:** To ensure the scientific reliability of your predictions, you *must* validate the loaded database before proceeding. Predictions are not scientifically citable without this verification.
1. Navigate to the **"AI Insights"** tab.
2. Review the model validation metrics (e.g., $R^2$, RMSE) and analytical charts (Actual vs. Predicted, Feature Importance).
3. Export the comprehensive AI report. This confirms that the data has been successfully processed and the model is accurately stabilized.

## 💻 Data & Source Code Availability
The standalone executable software (`.exe`) is fully available in the **Releases** section for immediate use by researchers. 
However, to protect intellectual property and comply with our laboratory's data-sharing policies, the raw Python source code and training datasets are not publicly hosted in this repository. 

Researchers or reviewers interested in accessing the raw source code for non-commercial or verification purposes can obtain it upon reasonable request by contacting the lead developer at:
📧 **ahmadreza_nekounam@modares.ac.ir**

## 📚 Citation
If you use the NMP framework or this repository in your research, cite our primary manuscript.
