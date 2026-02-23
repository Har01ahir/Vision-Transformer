# Vision Transformer

This project implements a Vision Transformer (ViT) model for image classification.  
The Vision Transformer treats an image as a sequence of patches, similar to how words are treated in text, and uses a transformer architecture to predict class labels. :contentReference[oaicite:0]{index=0}

---

## How It Works

1. **Image Input**  
   Load an input image that you want to classify.

2. **Patch Extraction**  
   The image is divided into fixed‑size patches.

3. **Embedding and Position Encoding**  
   Each patch is converted into a vector and enriched with positional information.

4. **Transformer Encoder**  
   The sequence of patch embeddings is processed by transformer layers.

5. **Classification**  
   The final output from the transformer is passed to a classification layer to predict the image class.

---

## Project Files

- `augment.py` – Data augmentation utilities.
- `train_final.py` – Main training script.
- `train_updated.py` – Updated version of training utilities.
- `train_using_pretrained_model_image_classifier.ipynb` – Notebook example using a pretrained model.
- `requirements.txt` – List of Python libraries required.

---

## How to Use

### 1. Clone the Repository


git clone https://github.com/Har01ahir/Vision-Transformer.git

cd Vision-Transformer


### 2. Install Dependencies

Make sure Python is installed, then install requirements:

pip install -r requirements.txt


### 3. Train or Test the Model

- To train the model from scratch, run:

python train_final.py
