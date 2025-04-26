1. **Download Dataset 1**:
   ```bash
   !pip install roboflow
   from roboflow import Roboflow
   rf = Roboflow(api_key="sFsgBqWcv09QR1Yku5mC")
   project = rf.workspace("sion-pardosi-hbf7k").project("identification-cornleaf-diseases")
   version = project.version(1)
   dataset = version.download("folder")
   ```
2. **Download Dataset 2**:
   ```
   https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset
   ```
