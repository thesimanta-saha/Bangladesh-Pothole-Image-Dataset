# 🚧 Bangladesh Pothole Detection Dataset

<div align="center">

![Bangladesh](https://img.shields.io/badge/Country-Bangladesh-green?style=flat-square)
![Divisions](https://img.shields.io/badge/Divisions-7-blue?style=flat-square)
![Total Images](https://img.shields.io/badge/Total%20Images-4%2C314-orange?style=flat-square)
![Total Potholes](https://img.shields.io/badge/Total%20Annotated%20Potholes-6%2C183-red?style=flat-square)
![Distance](https://img.shields.io/badge/Coverage-538.38%20km-purple?style=flat-square)
![Platform](https://img.shields.io/badge/Annotations-Roboflow-blueviolet?style=flat-square)

**A large-scale, real-world pothole image dataset collected across 7 divisions of Bangladesh, annotated via Roboflow for road condition monitoring and AI-based pothole detection research.**

[📊 Dataset Stats](#-dataset-statistics) • [📍 Data Collection Locations](#-data-collection-locations) • [🗂️ Dataset Structure](#️-dataset-structure) 
</div>

---

## 📖 Overview

This dataset provides annotated pothole images collected through extensive field surveys across Bangladesh's road network — covering **urban streets, national highways, and rural roads**. Data was gathered across **7 administrative divisions**, spanning **538.38 km** of road coverage.

Each image is annotated with **bounding boxes** around detected potholes, with per-image pothole counts ranging from single to septuple (1–7 potholes per image). Annotations were managed and exported through **Roboflow**.

### Key Highlights

- 📸 **4,314 total images** across 7 divisions
- 🕳️ **6,183 total annotated potholes**
- 📍 **538.38 km** of road surveyed
- 🗺️ Coverage across **urban, highway, and rural** environments
- ⏰ Images captured across **morning, noon, afternoon, and night**
- ☀️ Varied weather: **sunny, gloomy, and clear** conditions
- 🛣️ Road conditions: **dry and wet**

---

## 📊 Dataset Statistics

### Overall Summary

| Category | Subcategory | Images | Annotated Potholes |
|---|---|---|---|
| **Location** | Urban | 1,315 | 1,814 |
| | Highway | 1,873 | 2,855 |
| | Rural | 1,126 | 1,514 |
| **Time Frame** | Morning | 554 | 685 |
| | Noon | 2,767 | 4,039 |
| | Afternoon | 930 | 1,297 |
| | Night | 123 | 162 |
| **Road Condition** | Dry | 3,557 | 5,162 |
| | Wet | 757 | 1,021 |
| **Weather** | Sunny | 3,990 | 5,723 |
| | Gloomy | 201 | 247 |
| | Clear | 123 | 162 |

### Potholes per Image Distribution (Overall)

| Potholes per Image | Number of Photos | Total Potholes |
|---|---|---|
| Single (1) | 3,001 | 3,001 |
| Double (2) | 912 | 1,824 |
| Triple (3) | 288 | 864 |
| Quadruple (4) | 83 | 332 |
| Quintuple (5) | 20 | 100 |
| Sextuple (6) | 8 | 48 |
| Septuple (7) | 2 | 14 |
| **Total** | **4,314** | **6,183** |

---

### Division-wise Breakdown

#### 1. 🟢 Barishal Division — 761 images | 1,494 potholes | 111.40 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Urban | 41 | 59 |
| | Highway | 718 | 1,433 |
| | Rural | 2 | 2 |
| Time Frame | Noon | 563 | 1,176 |
| | Afternoon | 155 | 257 |
| | Night | 43 | 61 |
| Road Condition | Dry | 761 | 1,494 |
| Weather | Sunny | 718 | 1,433 |
| | Clear | 43 | 61 |

---

#### 2. 🔵 Chattagram Division — 33 images | 42 potholes | 2.33 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Highway | 33 | 42 |
| Time Frame | Noon | 33 | 42 |
| Road Condition | Dry | 11 | 14 |
| | Wet | 22 | 28 |
| Weather | Sunny | 11 | 14 |
| | Gloomy | 22 | 28 |

---

#### 3. 🟠 Dhaka Division — 2,015 images | 2,708 potholes | 218.21 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Urban | 1,135 | 1,579 |
| | Highway | 66 | 84 |
| | Rural | 814 | 1,045 |
| Time Frame | Morning | 103 | 133 |
| | Noon | 1,475 | 1,948 |
| | Afternoon | 471 | 606 |
| | Night | 26 | 21 |
| Road Condition | Dry | 1,647 | 2,243 |
| | Wet | 368 | 465 |
| Weather | Sunny | 1,932 | 2,563 |
| | Gloomy | 57 | 73 |
| | Clear | 26 | 21 |

---

#### 4. 🟡 Khulna Division — 586 images | 708 potholes | 112.84 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Urban | 16 | 19 |
| | Highway | 524 | 631 |
| | Rural | 46 | 58 |
| Time Frame | Morning | 333 | 411 |
| | Noon | 133 | 157 |
| | Afternoon | 96 | 110 |
| | Night | 24 | 30 |
| Road Condition | Dry | 505 | 593 |
| Weather | Sunny | 562 | 678 |
| | Clear | 24 | 30 |

---

#### 5. 🟣 Mymensingh Division — 280 images | 404 potholes | 15.66 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Highway | 122 | 146 |
| | Rural | 158 | 258 |
| Time Frame | Morning | 118 | 141 |
| | Noon | 4 | 5 |
| | Afternoon | 158 | 258 |
| Road Condition | Wet | 280 | 404 |
| Weather | Gloomy | 122 | 146 |
| | Sunny | 158 | 258 |

---

#### 6. 🔴 Rajshahi Division — 622 images | 791 potholes | 60.05 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Highway | 410 | 519 |
| | Urban | 123 | 157 |
| | Rural | 89 | 115 |
| Time Frame | Noon | 559 | 711 |
| | Afternoon | 50 | 66 |
| | Night | 13 | 14 |
| Road Condition | Dry | 616 | 782 |
| | Wet | 6 | 9 |
| Weather | Sunny | 609 | 777 |
| | Clear | 13 | 14 |

---

#### 7. 🟤 Sylhet Division — 17 images | 36 potholes | 2.23 km

| Category | Detail | Images | Potholes |
|---|---|---|---|
| Location | Rural | 17 | 36 |
| Time Frame | Night | 17 | 36 |
| Road Condition | Dry | 17 | 36 |
| Weather | Clear | 17 | 36 |

---

### Division Summary Table

| Division | Images | Annotated Potholes | Road Covered (km) |
|---|---|---|---|
| Barishal | 761 | 1,494 | 111.40 |
| Chattagram | 33 | 42 | 2.33 |
| Dhaka | 2,015 | 2,708 | 218.21 |
| Khulna | 586 | 708 | 112.84 |
| Mymensingh | 280 | 404 | 15.66 |
| Rajshahi | 622 | 791 | 60.05 |
| Sylhet | 17 | 36 | 2.23 |
| **Total** | **4,314** | **6,183** | **538.38** |

---

## 📍 Data Collection Locations

All images were geo-tagged. Below is the full list of data collection points by division and district.

### Barishal Division (111.40 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Barisal | Barisal_Sadar | 22.710, 90.376 *(+ 4 more points)* | 7.64 |
| Patuakhali | Dhaka-Kuakata Highway | 21.829, 90.122 *(+ 16 more points)* | 98.92 |
| Patuakhali | Dumki | 22.4643, 90.3806 | 4.84 |

### Chattagram Division (2.33 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Cox's Bazar | Marine Drive | 21.3911, 92.0016 *(+ 1 more point)* | 2.33 |

### Dhaka Division (218.21 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Dhaka City | 19 urban locations (Aftabnagar, Badda, Banasree, Bangla_Motor, Baridhara, Bashabo, Demra, Gulistan, Hatirjheel, Kakraill, Kamalapur, Khilgaon, Mog_Bazar, Mohammadpur, Purbachal, Sadarghat, Shahbag, Tejgaon, Wari) | Various | 92.42 |
| Faridpur | Boalmari | 23.3039, 89.7310 *(+ 2 more)* | 7.72 |
| Faridpur | Saltha | 23.6801, 89.7690 *(+ 2 more)* | 22.36 |
| Gopalganj | Gopalganj_Sadar | 23.0083, 89.8275 *(+ 2 more)* | 2.25 |
| Gopalganj | Tungipara | 22.8858, 89.8983 *(+ 1 more)* | 9.36 |
| Munshiganj | Mawa | 23.4741, 90.2652 | — |
| Shariatpur | Jajira | 23.3289, 90.3196 *(+ 8 more)* | 65.13 |
| Shariatpur | Palong | 23.2606, 90.3487 *(+ 2 more)* | 6.05 |
| Tangail | Tangail_Sadar | 24.2450, 89.9106 *(+ 4 more)* | 12.92 |

### Khulna Division (112.84 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Bagherhat | Chitalmari | 22.8263, 89.9387 *(+ 1 more)* | 4.64 |
| Bagherhat | Khulna-Mongla Highway | 22.5745, 89.6156 *(+ 3 more)* | 21.49 |
| Jashore | Jhikargacha | 23.0996, 89.1081 | — |
| Jashore | Sharsha | 23.2819, 89.1561 *(+ 9 more)* | 41.10 |
| Jhenaidah | Harinakunda | 23.5418, 89.2230 | — |
| Jhenaidah | Jhenaidah_Sadar | 23.5501, 89.1692 *(+ 3 more)* | 11.14 |
| Jhenaidah | Kaliganj | 23.4663, 89.1414 *(+ 3 more)* | 17.04 |
| Khulna | Khulna_Sadar | 22.9745, 89.4743 | — |
| Kustia | Kumarkhali | 23.7671, 89.1180 *(+ 7 more)* | 12.96 |
| Magura | Magura_Sadar | 23.5129, 89.3277 | — |
| Narail | Kalia | 23.0895, 89.4565 | — |
| Narail | Narail_Sadar | 23.0895, 89.4565 *(+ 1 more)* | 4.47 |

### Mymensingh Division (15.66 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Mymensingh | Gouripur | 24.8103, 90.5143 | — |
| Mymensingh | Mymensingh_Sadar | 24.7602, 90.4430 | — |
| Netrokona | Durgapur | 25.1181, 90.6657 *(+ 1 more)* | 5.46 |
| Netrokona | Kalmakanda | 25.0679, 90.8826 *(+ 2 more)* | 10.20 |
| Netrokona | Kendua | 24.9090, 90.8010 | — |

### Rajshahi Division (60.05 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Bogura | Sherpur | 24.8611, 89.3258 *(+ 1 more)* | 2.20 |
| Naogaon | Naogaon_Sadar | 24.8285, 88.9377 *(+ 3 more)* | 5.55 |
| Naogaon | Patnitala | 24.7504, 88.8161 *(+ 2 more)* | 11.57 |
| Naogaon | Sapahar | 24.4103, 88.6090 | — |
| Natore | Bagatipara | 24.4196, 88.9910 | — |
| Pabna | Bera | 24.3912, 89.0349 | — |
| Pabna | Sujanagar | 24.2922, 89.0812 *(+ 8 more)* | 26.82 |
| Rajshahi | Rajshahi_Sadar | 24.3758, 88.6303 *(+ 1 more)* | 5.35 |
| Sirajganj | Sirajganj_Sadar | 24.4501, 89.7211 *(+ 3 more)* | 8.56 |

### Sylhet Division (2.23 km)

| District | Location | Coordinates (Lat, Lon) | KM |
|---|---|---|---|
| Moulovibazar | Sreemangal | 24.3065, 91.7347 | 2.23 |

---

## 🗂️ Dataset Structure

```
bangladesh-pothole-detection/
│
├── README.md                      ← You are here
├── locations.csv                  ← All GPS coordinates (lat/lon) per location
├── dataset_statistics.md          ← Full per-division statistics
│
├── annotations/                   ← Roboflow export (YOLO / COCO / VOC format)
│   ├── train/
│   │   ├── images/
│   │   └── labels/
│   ├── valid/
│   │   ├── images/
│   │   └── labels/
│   └── test/
│       ├── images/
│       └── labels/
│
├── data.yaml                      ← YOLO dataset config file
└── LICENSE
```

> ⚠️ **Note:** Raw images and annotation files are hosted on [Roboflow](https://roboflow.com). See [Getting Started](#-getting-started) for access instructions.

---


## 📋 Annotation Details

- **Annotation Tool:** Roboflow
- **Annotation Type:** Bounding Box (Object Detection)
- **Class:** `pothole`
- **Images per label:** 1 to 7 potholes per image
- **Export formats available:** JSON, TXT, XMAL, CSV  and others.

---

## 🌍 Coverage Map

Data was collected across the following 7 divisions of Bangladesh:

| Division | Districts Covered |
|---|---|
| Barishal | Barisal, Patuakhali |
| Chattagram | Cox's Bazar |
| Dhaka | Dhaka City, Faridpur, Gopalganj, Munshiganj, Shariatpur, Tangail |
| Khulna | Bagherhat, Jashore, Jhenaidah, Khulna, Kustia, Magura, Narail |
| Mymensingh | Mymensingh, Netrokona |
| Rajshahi | Bogura, Naogaon, Natore, Pabna, Rajshahi, Sirajganj |
| Sylhet | Moulovibazar |

---



## 📜 License

This dataset is released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.
You are free to share and adapt the material for any purpose, provided appropriate credit is given.


