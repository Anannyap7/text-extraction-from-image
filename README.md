# Text Extraction from Image (Optical Character Recognition)

Automated text extraction from images of handwritten text to facilitate convenient information retrieval and digitization.

## Models Used:
1. **Encoder Architecture** - Experimented with Wide and Deep Convolutional Neural Networks (CNN) and a pretrained ResNet50 to extract spatial features of the document image.
2. **Decoder Architecture** - Transformer model with spatial encoding in input sequence (latent representation of the image).

## Metrics Used:
1. **Character Error Rate (CER)** using Levenshtein distance / Edit Distance
2. **Word Error Rate (WER)** using Levenshtein distance / Edit Distance

## Loss Used:
Cross-Entropy Loss
