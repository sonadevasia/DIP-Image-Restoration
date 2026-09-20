# Restoration and Enhancement of Degraded Images Using Digital Image Processing

## Project Description

This project demonstrates the restoration and enhancement of degraded images using Digital Image Processing techniques.

Four images were used as reference images. Gaussian noise was artificially added to simulate image degradation. The degraded images were then processed using Median Filtering, Gaussian Filtering, and CLAHE-based contrast enhancement.

The restoration techniques were evaluated using Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Structural Similarity Index (SSIM).

## Objectives

- Simulate image degradation using Gaussian noise.
- Restore degraded images using Median Filtering.
- Restore degraded images using Gaussian Filtering.
- Improve image contrast using CLAHE.
- Compare restoration techniques using MSE, PSNR, and SSIM.

## Techniques Used

- Gaussian Noise
- Median Filtering
- Gaussian Filtering
- CLAHE Contrast Enhancement
- MSE
- PSNR
- SSIM

## Tools and Technologies

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- Pandas
- scikit-image

## Results

For the four images used in the experiment, Gaussian Filtering produced the best quantitative results.

| Method | Average MSE | Average PSNR | Average SSIM |
|---|---:|---:|---:|
| Degraded | 618.04 | 20.22 dB | 0.501 |
| Median Filter | 137.44 | 27.56 dB | 0.750 |
| Gaussian Filter | 93.77 | 28.76 dB | 0.833 |
| Enhanced Restoration | 696.63 | 19.78 dB | 0.618 |

## Project Files

- `DIP_Old_Photo_Restoration.ipynb` – Google Colab implementation
- `DIP_Project_Report.pdf` – Complete project report
- `requirements.txt` – Required Python libraries

## Conclusion

The experiment demonstrated that spatial filtering can effectively reduce simulated image degradation. Among the tested methods, Gaussian Filtering achieved the best quantitative restoration results for the four selected images.
