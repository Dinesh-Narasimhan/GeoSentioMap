# 🧠 GeoSentioMap

GeoSentioMap is an AI-powered tool that maps the emotional feel of public places (starting with Kerala & Chennai) using images and ambient metadata like time and weather.

---

## 🎯 What It Does

- Input: Image + metadata (location, weather, time of day)
- Output: Emotion label like:
  - 🧘 Peaceful
  - 🏙️ Neutral
  - 🕺 Energetic
  - 🔥 Chaotic
 
Challenges we ran into
Working with a limited number of images while trying to maintain balance across emotion classes was a key challenge. We also faced difficulties in fine-tuning the model to accurately learn subtle differences in emotional tone.

---

## 🔧 Tech Stack

- 🔍 Model: ResNet18 (ImageNet) + metadata fusion (PyTorch)
- 🌤️ Metadata: Location, weather, time encoded manually
- 🎛️ Inference UI: Streamlit App
- 📁 Deployment: GitHub + Streamlit Cloud

---

## 🚀 Try It Live

👉 **[Live App](https://geosentiomap.streamlit.app)**  

## 🔐 License & Credits

- Images used in this project are from **Pexels.com**, which provides free-to-use content under the [Pexels License](https://www.pexels.com/license/).
- All images are copyright-safe and used for non-commercial, educational purposes.
- Model and code are released for learning and demonstration only.

---

We plan to scale the model to include more cities, refine emotional categories, incorporate real-time weather APIs, and crowdsource feedback to improve accuracy and personalization.
