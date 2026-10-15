# Adaptive Spatial Information Flow via Dynamic Feature Relocation for Unified Image Restoration (ASIF-IR)

---

## 📊 Benchmark Results and Download URLs

Download links for each dataset's full restoration visual results are provided below.

| Benchmark Setting | Evaluation Tasks / Datasets | Restoration Results Download |
|:---|:---|:---:|
| **3-Task All-in-One** | Denoising (CBSD68), Dehazing (SOTS), Deraining (Rain100L) | [📥 Download Results](https://drive.google.com/file/d/185b_yamUaJDdlLtd2IG0CIvVrfTgA8wq/view?usp=sharing) |
| **5-Task All-in-One** | Denoising, Dehazing, Deraining, Deblurring (GoPro), Low-Light (LOL) | [📥 Download Results](https://drive.google.com/file/d/1iti0Dha5OvAg1iIPfUIB6hC28-eUrhy7/view?usp=sharing) |
| **CDD11** | 11 Single, Double, and Triple Multi-degradation Combinations | [📥 Download Results](https://drive.google.com/file/d/159J0hClE_OJLEERdcElQG00qTj7ES9Hp/view?usp=sharing) |
| **AllWeather** | Snow100K-S, Snow100K-L, Outdoor-Rain, RainDrop | [📥 Download Results](https://drive.google.com/file/d/1qqR_3kTTiVuQ-hghXKdhU6M2u2bBxK_V/view?usp=sharing) |
| **WeatherBench** | Real-world Dehazing, Deraining, Desnowing | [📥 Download Results](https://drive.google.com/file/d/1SSlyNbyI18FiIMLfKcPvZCkZ_g8DakkE/view?usp=sharing) |

---

### 1. Three-Task All-in-One Benchmark


| Method | Venue | CBSD68 ($\sigma=15$) | CBSD68 ($\sigma=25$) | CBSD68 ($\sigma=50$) | SOTS Outdoor | Rain100L | Average | Params |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ASIF-IR (Ours) | 2026 | 34.14 / 0.936 | 31.49 / 0.892 | 28.24 / 0.804 | 31.75 / 0.982 | 38.93 / 0.985 | 32.91 / 0.920 | 12M | 

---

### 2. Five-Task All-in-One Benchmark


| Method | Venue | Denoising (CBSD68) | Dehazing (SOTS) | Deraining (Rain100L) | Deblurring (GoPro) | Low-Light (LOL) | Average | Params | 
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ASIF-IR (Ours) | 2026 | 31.41 / 0.891 | 31.70 / 0.981 | 38.63 / 0.983 | 28.24 / 0.861 | 23.71 / 0.859 | 30.74 / 0.915 | 12M | 

---

### 3. CDD11 Composite Degradation Benchmark


| Method | Params | Low (L) | Haze (H) | Rain (R) | Snow (S) | L+H | L+R | L+S | H+R | H+S | L+H+R | L+H+S | Overall Avg. | 
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| ASIF-IR (Ours) | 12M | 27.48 / .833 | 32.78 / .990 | 34.40 / .969 | 36.14 / .979 | 26.58 / .828 | 26.56 / .811 | 26.44 / .804 | 30.17 / .964 | 30.32 / .969 | 25.68 / .800 | 25.80 / .798 | 29.30 / .886 | 

---

### 4. Adverse Weather Removal Benchmark


| Method | Venue | Snow100K-S | Snow100K-L | Outdoor-Rain | RainDrop | Average | 
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| ASIF-IR (Ours) | 2026 | 38.64 / 0.970 | 32.85 / 0.934 | 33.32 / 0.950 | 33.12 / 0.948 | 34.48 / 0.950 |

---

### 5. Real-World WeatherBench Benchmark


| Method | Venue | Dehazing (PSNR / SSIM / LPIPS) | Deraining (PSNR / SSIM / LPIPS) | Desnowing (PSNR / SSIM / LPIPS) | Average (PSNR / SSIM / LPIPS) |
|:---|:---:|:---:|:---:|:---:|:---:|
| ASIF-IR (Ours) | 2026 | 26.31 / 0.785 / 0.318 | 38.84 / 0.966 / 0.157 | 31.26 / 0.895 / 0.155 | 32.14 / 0.882 / 0.210 | 

---




## 📑 Citation

If you find this work or the benchmark results useful for your research, please cite our paper:

```bibtex
@article{nguyen2026asifir,
  title     = {Adaptive Spatial Information Flow via Dynamic Feature Relocation for Unified Image Restoration},
  author    = {Nguyen, Xuan-Tuan and Lee, Seongsoo and Hong, Min-Cheol},
  journal   = {},
  year      = {2026},
  doi       = {}
}
```
