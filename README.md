# Indonesian Misogyny Meme Dataset

## Overview

This dataset contains annotations for Indonesian women-related memes collected from Facebook. The dataset focuses on misogyny detection and content appropriateness classification within the Indonesian social media context.

## Download

### CSV File
Annotation file is included in this repository: `test_dataset.csv`

### Images
Complete image collection is available via Google Drive:
```
https://drive.google.com/file/d/1bo0fFEceYij1D9k8XcceL32bkv6UFxjI/view?usp=drivesdk
```

## Data Description

### CSV File Format

The CSV file contains 3 columns:

| Column | Description | Values |
|--------|-------------|---------|
| `image_path` | Filename of the meme image | JPEG filenames |
| `hate_final` | Hate speech classification | `hate` or `not hate` |
| `appropriateness_final` | Content appropriateness classfication | `appropriate` or `not appropriate` |

### Dataset Statistics

- **Total samples**: 628 memes
- **Hate speech distribution**:
  - Hate content: 207 samples (33%)
  - Non-hate content: 421 samples (67%)
- **Appropriateness distribution**:
  - Appropriate content: 254 samples (40.4%)
  - Not appropriate content: 374 samples (59.6%)

## Contact

For questions about the dataset or collaboration opportunities, please refer to the original data source or repository maintainers.

---

**Disclaimer**: This dataset is intended for academic and research purposes only. The content may include offensive material that does not reflect the views of the researchers or institutions involved in its creation.
