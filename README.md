# AI and Machine Learning Project Portfolio

**Janane Sivakumar**

A collection of seven educational projects spanning exploratory data analysis, predictive modeling, computer vision, application deployment, and retrieval-augmented generation. Each project includes its own overview and an HTML export containing code, saved outputs, visualizations, and analysis.

## Projects

| Project | Focus | Description |
| --- | --- | --- |
| [FoodHub](projects/foodhub/) | Exploratory data analysis | Analyzes restaurant demand, customer ratings, order costs, and preparation and delivery times to develop business recommendations. |
| [Personal Loan](projects/personal-loan/) | Classification and model interpretation | Predicts personal loan campaign acceptance from customer demographic and financial features to inform marketing segmentation. |
| [EasyVisa](projects/easyvisa/) | Ensemble learning and class imbalance | Compares tree-based classifiers and resampling strategies for predicting the case status in an educational visa-certification dataset. |
| [ReneWind](projects/renewind/) | Predictive maintenance and neural networks | Predicts wind turbine generator failures from anonymized sensor features, emphasizing recall to reduce missed failures. |
| [HelmNet](projects/helmnet/) | Computer vision and transfer learning | Classifies worker images as With Helmet or Without Helmet using a CNN baseline and VGG16 transfer learning. |
| [SuperKart](projects/superkart/) | Regression and application deployment | Predicts product-store sales using ensemble regression and documents a Flask API, Streamlit interface, and Docker deployment workflow on Hugging Face Spaces. |
| [Medical Assistant](projects/medical-assistant/) | Generative AI and retrieval-augmented generation | Builds a retrieval-augmented question-answering prototype over a medical reference PDF and compares baseline, prompted, and document-grounded answers. |

## How to Explore

1. Select a project from the table above.
2. Read its project README for the problem, methods, highlights, and evaluation notes.
3. Download its `report.html` file and open it in a browser to view the formatted analysis. GitHub shows HTML files as source rather than rendering the report.

## Repository Contents

- `projects/foodhub/` — food delivery data analysis.
- `projects/personal-loan/` — personal loan campaign response prediction.
- `projects/easyvisa/` — application outcome classification.
- `projects/renewind/` — wind turbine generator failure prediction.
- `projects/helmnet/` — safety helmet image classification.
- `projects/superkart/` — retail sales prediction and deployment workflow.
- `projects/medical-assistant/` — document-grounded question answering.

Each folder contains `README.md` and `report.html`.

## Reproducibility

These files are **HTML notebook exports**, not the original runnable notebooks. Original `.ipynb` files, datasets, trained model files, and deployment assets are not included unless embedded as code or outputs in the reports. Add original notebooks to the matching folders to allow visitors to run the projects.

Dependencies differ across projects. The project READMEs identify the main tools and required data filenames; this repository does not claim a single tested environment for all seven projects. Reported metrics come from the supplied exports and have not been independently reproduced during repository preparation.

## Skills Demonstrated

- Data cleaning, exploratory analysis, and visualization.
- Preprocessing pipelines, feature engineering, and model interpretation.
- Ensemble learning, hyperparameter tuning, and class imbalance handling.
- Neural networks, transfer learning, and image augmentation.
- Model serialization, API development, and frontend/backend deployment workflows.
- Document retrieval, vector stores, prompt design, and RAG evaluation.

## Attribution

These are educational projects supplied by Janane Sivakumar. Assignment scenarios and source datasets are course materials; original prompts remain in the exports. Dataset redistribution and a reuse license are not asserted here.
