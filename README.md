<h1 align="center">Nakshtra Agrawal</h1>

<p align="center">
  <b>Computer vision for things that fly.</b><br/>
  Perception systems for autonomous drones, from model to edge to field.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nakshtra-agrawal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nakshtraagrawal5@gmail.com"><img src="https://img.shields.io/badge/Email-111111?style=flat-square&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Bengaluru-111111?style=flat-square&logo=googlemaps&logoColor=white"/>
</p>

---

**Now**
- Building vision systems for UAVs at **Comono India**
- Leading imagery & CV at **[Edhitha UAS](https://www.edhitha.com/)**, RIT's international UAV team
- ISE @ Ramaiah Institute of Technology

**Wins**
- 🥇 **NIDAR, 1st place** (Disaster Management), out of 350+ teams, for a dual-drone flood response system
- 🌐 **IARC Mission 10**: CV lead, International Aerial Robotics Competition

---

### Selected work

**[Open-Vocabulary FOD Detection](https://drive.google.com/drive/folders/13tT6p7SJaB071FRiUscY6-u1pXEo2Jhr?usp=sharing)**: airstrip debris detection from UAV imagery  
Zero-shot Grounding DINO across 14 loosely defined classes, with no per-class training. Compiled to a **TensorRT** engine on Jetson, taking latency from **~2 s → <1 s** per frame. Validated in SITL, then in live flights at 200 ft.  
`Grounding DINO` `TensorRT` `Jetson` `PyTorch`

**[High-Altitude Human Detection](https://drive.google.com/drive/folders/1PYD_L1IW-Aj2dAPbtT8-CMeXy4sUmWPr?usp=sharing)**: search & rescue perception  
Coarse-to-fine **YOLOv11 cascade**: detect at 150 ft, re-centre, then confirm at 40 ft. Pixel → GPS projection from camera intrinsics, altitude and heading gives a **1.5 m** payload drop radius in real flights.  
`YOLOv11` `OpenCV` `Geolocation`

**[Quatsch](https://github.com/nakshtraagrawal/Quatsch)**: satellite nightlights as an economic signal  
GeoTIFF pipeline over NASA VIIRS rasters (2016–2025): background-fog removal, grid-based hotspot growth analysis, and dark-zone emergence detection, all geo-referenced back to lat/lon.  
`rasterio` `NumPy` `Flask` `React` `Leaflet`

**[Audio Fingerprint](https://github.com/nakshtraagrawal/ps1)**: Shazam-style song identification  
STFT → 2D peak constellation → 32-bit combinatorial hashes in an inverted index. Matches noisy 3–10 s clips by time-offset alignment voting. CI with ruff, mypy and ≥80% test coverage.  
`Python` `DSP` `pytest` `GitHub Actions`

**[hack-a-war](https://github.com/nakshtraagrawal/hack-a-war)**: natural language → cloud architecture  
LLM pipeline (Llama 3.3 70B on **AWS Bedrock**, Gemini 2.5 for refinement) that turns a product description into an AWS design with tiered cost estimates. Generated Mermaid graphs are parsed into an interactive **React Flow** canvas with **dagre** auto-layout. A reverse mode audits an existing architecture for issues and optimisations.  
`AWS Bedrock` `Node/Express` `React Flow` `LLMs`

**[ClearGrid](https://github.com/pratyuxxhh/Deepstation-hackathon)**: multi-agent municipal waste routing  
Forecaster, dispatcher and HazMat agents. Predicts bin overflow before the next pickup, routes with haversine nearest-neighbour TSP, and grounds safety briefs in CPCB / OSH regulations via Llama 3.3 on Groq.  
`FastAPI` `React` `TypeScript` `RAG`

---

### Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,docker,fastapi,postgres,react,nodejs,aws,linux,git&theme=dark"/>
</p>

<sub>Also: YOLO · Grounding DINO · TensorRT · NVIDIA Jetson · rasterio</sub>
