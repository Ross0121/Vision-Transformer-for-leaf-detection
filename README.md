# Vision Transformer for Leaf Disease Detection

1. Developed a custom `ShiftedPatchTokenization` layer to enhance the standard patch extraction process by including diagonally shifted patches, improving spatial information capture.
2. Enhanced the multi-head attention mechanism with a learnable temperature parameter (`MultiHeadAttentionLSA`) and a diagonal attention mask, improving the model's attention focus.
3. Achieved around 90%+ accuracy on apple, grape, corn, and tomato disease classification from the Plant Village dataset with up to 5 classes.
4. Training time was efficient, taking only 2-3 minutes per epoch.
5. Deployed the model on an app with a user-friendly interface.

## Results for Disease Detection
![Disease Detection Results](https://github.com/user-attachments/assets/38dc1645-3483-4bc3-b182-31e231018878)

## Client Side App View
![Client Side App View](https://github.com/user-attachments/assets/ce7604ba-d8ac-4fad-9d0e-d58a13495aae)
