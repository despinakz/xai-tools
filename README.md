# xai-tools
University of Piraeus - Thesis Project
This repository ...

```bash
reviewsNN
├── NN-Project
│   ├── IMDB Dataset.csv            : Δεδομένα του Πεδίου Εφαρμογής 1 (NLP) 
│   ├── preprocessPart1.ipynb       : Επεξεργασία δεδομένων & παραγωγή νέου αρχείου με τα δεδομένα 
│   ├── preprocessedData.xls        : Επεξεργασμένα δεδομένα από το αρχείο preprocessPart1 
│   ├── preprocessPart2.ipynb       : Μετατροπη δεδομένων σε TF-IDF μορφή & δημιουργία/εκπαίδευση μοντέλου 
│   ├── my_model.h5                 : Το μοντέλο ενδιαφέροντος (νευρωνικό δίκτυο) 
│   ├── ClassificationRuntime.ipynb : Αρχείο μέτρησης του χρόνου(runtime) της κατηγοριοποίησης του ΝΔ 
│   └── NNPrediction                : Αρχείο με παράδειγμα πρόβλεψης 
└── IMDB Classifier
    ├── imdb_classifier.ipynb       : Χρήση εργαλείου επεξήγησης LIME 
    ├── imdb_classifier_shap.ipynb  : Χρήση εργαλείου επεξήγησης SHAP 
    └── my_model.h5                 : Το μοντέλο ενδιαφέροντος (νευρωνικό δίκτυο) 
        
skinCancer
└── data
    ├── test                                    : Δεδομένα ελέγχου (test dataset)
    ├── train                                   : Δεδομένα εκπαίδευδης (training dataset)
    ├── models
    │   ├── model.h5
    │   ├── model.json
    │   ├── resnet50.h5                         : Το μοντέλο ενδιαφέροντος που χρησιμοποιήθηκε στην εργασία
    │   └── resnet50.json                       : Το μοντέλο ενδιαφέροντος που χρησιμοποιήθηκε στην εργασία
    └── code
        ├── cnn-for-skin-cancer-detection.ipynb : Δεδομένα και δημιουργία/εκπαίδευση μοντέλου
        ├── img_classification_lime.ipynb       : Χρήση εργαλείου επεξήγησης LIME
        ├── img_classification_shap.ipynb       : Χρήση εργαλείου επεξήγησης SHAP
        ├── save_arr_to_npy_files.ipynb
        ├── Untitled.ipynb
        ├── X_test.npy
        ├── X_train.npy
        ├── y_test.npy
        └── y_train.npy
```
