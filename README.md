# MangoGuard
AI-powered mango leaf disease detection — a simple, user-friendly web tool to help farmers and agronomists detect common mango leaf diseases and get suggested remedies.
> *MangoGuard* analyzes an uploaded mango leaf photo and returns a predicted disease (or "Healthy Leaf") along with confidence and suggested remediation steps.
## Demo / Preview
The project includes a responsive UI with:
- Drag & drop or file-picker image upload
- Preview of uploaded leaf image
- Predict button with loading indicator
- Result card showing disease name, confidence, description and remedies

(Design and content derived from the provided mg.html upload.) 
---
## Features
- Upload image (JPG / PNG / JPEG)
- Preview uploaded leaf image
- Simulated model inference (plug-in your ML API easily)
- Disease info & suggested remedies for:
  - Anthracnose
  - Powdery Mildew
  - Bacterial Canker
  - Gall Midge
  - Die Back
  - Cutting Weevil
  - Sooty Mould
  - Healthy Leaf
- Mobile-friendly and accessible UI
---
## Tech stack
- Frontend: HTML, CSS, vanilla JavaScript
- Optional: Any backend or model-serving API (Flask, FastAPI, Node/Express, TensorFlow Serving, TorchServe, or a cloud ML endpoint)
---
## Installation / Run locally
This is a static frontend — you can run it locally or host it on GitHub Pages / Netlify / Vercel.

### Option A — Quick local preview (no server)
1. Put mg.html (or index.html) in a folder.
2. Open the file in a browser: double-click the file or Open File in the browser.

### Option B — Simple HTTP server (recommended)
Using Python:
```bash
