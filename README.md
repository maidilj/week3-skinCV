# week3-skinCV
Transfer-learning classifier for the HAM10000 skin-lesion dataset (7 classes),
with a static portfolio site and a FastAPI/Docker inference backend.

- `notebooks/` — data prep, training (ResNet-50 + ViT-B/16, wandb-tracked), and
  a research comparison of backbones, strategies, and augmentation.
- `api/` — FastAPI `/predict` serving the exported model.
- `public/` — static showcase + live demo, deployed to GitHub Pages.

**Educational demo — not a medical diagnosis. Consult a dermatologist.**
