# Vehicle Re-Identification Dataset
## Dataset Description

The Vehicle Re-ID dataset consists of vehicle images captured from **two different camera perspectives**, enabling researchers to develop and evaluate algorithms for matching the same vehicle across different viewpoints.

### Key Features:
- **Multi-camera setup**: Images from 2 different camera angles
- **Multiple vehicle types**: Cars, motorcycles, trucks, and buses
- **Cross-camera vehicle matching**: Each vehicle appears in both camera views
- **Real-world scenarios**: Diverse lighting conditions and backgrounds

## Dataset Statistics

| Split | Total Images | Vehicle Types | File Lists |
|-------|-------------|---------------|------------|
| **Training** | 1,014 images | Car: 125, Motorcycle: 322, Truck: 56, Bus: 4 | `train.txt` (810 entries), `val.txt` (204 entries) |
| **Testing** | 120 images | Car: 16, Motorcycle: 28, Truck: 13, Bus: 3 | `test.txt` (120 entries) |

## Folder Structure

```
Vehicle-Re-ID-Dataset/
├── train.txt                    # Training set image list
├── test.txt                     # Test set image list  
├── val.txt                      # Validation set image list
├── videos.txt                   # Link to source videos
└── images/
    ├── train/                   # Training images
    │   ├── car_0001_cam1.jpg
    │   ├── car_0001_cam2.jpg
    │   ├── motorcycle_0001_cam1.jpg
    │   ├── motorcycle_0001_cam2.jpg
    │   ├── truck_0001_cam1.jpg
    │   ├── truck_0001_cam2.jpg
    │   ├── bus_0001_cam1.jpg
    │   ├── bus_0001_cam2.jpg
    │   └── ...
    └── test/                    # Test images
        ├── car_XXXX_cam1.jpg
        ├── car_XXXX_cam2.jpg
        └── ...
```

## Source Videos

The original video footage used to create this dataset is available at this
[link](https://drive.google.com/drive/folders/1VIvguu1LzR_S5eywCxP88IQCRAfYVNcP?usp=sharing)

## Contributors

This dataset was created and maintained by:

- **Minh Khoa Truong Nguyen**: [khoanguyentruongminh@gmail.com](mailto:khoanguyentruongminh@gmail.com)
- **Thinh Luong Truong**: [thinhlt.uit@gmail.com](mailto:thinhlt.uit@gmail.com)  
- **Luan Nguyen Thanh**: [ntluan2004@gmail.com](mailto:ntluan2004@gmail.com)

For questions or collaboration, please contact any of the team members above.

## License

This dataset is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.
