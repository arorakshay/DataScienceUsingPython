# Customer Segmentation on Banks Data
![Gender.png](Images/Gender.png)

## INTRODUCTION
- The dataset was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0Hz-280Hz (human vocal range).

## DATA
| Column Name | Description |
| --- | --- |
| `meanfreq`  | mean frequency (in khz) |
| `sd`  | standard deviation of frequency |
| `Median`  | median frequency (in khz)|
| `Q25`  | first quantile (in khz) |
| `Q75`  | third quantile (in khz) |
| `IQR`  | interquantile (in khz) |
| `skew`  | skewness (see note in specprop description) |
| `kurt`  | kurtosis (see note in specprop description) |
| `sp.ent`  | spectral entropy |
| `sfm`  | spectral flatness|
| `mode`  | mode frequency|
| `centroid`  | frequency centroid (see specprop)|
| `peakf`  | peak frequency(frequency with highest energy) |
| `meanfun`  | average fundamental frequency measured across accoustic signal |
| `minfun`  | minimum fundamental frequency measured across accoustic signal |
| `maxfun`  | maximum fundamental frequency measured across accoustic signal |
| `meandom`  | average of dominant frequency measured across accoustic signal |
| `mindom`  | minimum of dominant frequency measured across accoustic signal |
| `maxdom`  | maximum of dominant frequency measured across accoustic signal |
| `dfrange`  | range of dominant frequency measured across accoustic signal |
| `mod indx`  | modulation index |
| `label`  | male or female |

#### Objectives:
 - The objective is to predict male/female with highest accuracy based on the accoustic properties.

### Conclusion
- We have used below  __ML algo__ for customer segmentation:
    - Support Vector Machine
- This notebook helps us classiying male/female based on the accoustic properties.
- __We have seen how by finely tuning C and gamma values for differnt kernel choices we can obtain maximum accuracy for our SVM model.__

[Jupyter Notebook](./Gender.ipynb)
