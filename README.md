# Unique Colors for Colorblindness Detection  

## Abstract  
This project focuses on simulating color perception for different types of colorblindness (protanopia, deuteranopia, tritanopia, and monochromacy) and identifying unique color shades that minimize confusion.  

Key components include:  
1. **Dataset** – Generating a base color set and simulating color vision deficiencies.  
2. **Processing**: Unique Colors Detection – Grouping colors using clustering algorithms and selecting distinct shades based on color variance metrics (RGB and LAB).  
3. **Results**: Confusion Samples – Providing optimized palettes for colorblind users, improving accessibility and visual differentiation.  

## Table of Contents  
1. [Introduction](#introduction)  
2. [Installation](#installation)  
3. [Methodology](#methodology)  
   - 3.1 [Dataset Generation](#dataset-generation)  
   - 3.2 [Simulating Colorblindness](#simulating-colorblindness)  
   - 3.3 [Clustering and Optimization](#clustering-and-optimization)  
4. [Results](#results)  
5. [Contributing](#contributing)  
6. [License](#license)  

## Introduction  
Colorblindness affects how individuals perceive colors, making it difficult to distinguish between certain shades. This project aims to improve color accessibility by detecting and optimizing unique shades for different types of colorblindness.  

## Installation  
To set up this project, follow these steps:  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/unique-colors-colorblindness.git  
   ```  

## Methodology  

### 4.1 Dataset Generation  
- Generate a base set of RGB colors.  
- Convert colors to LAB format for further analysis.  

### 4.2 Simulating Colorblindness  
- Apply filters for different types of colorblindness (protanopia, deuteranopia, tritanopia, monochromacy).  

### 4.3 Clustering and Optimization  
- Group transformed colors using clustering.  
- Select unique shades using variance metrics.  

## Results  
Optimized color palettes and confusion samples for each type of colorblindness are generated, providing visual differentiation and accessibility improvements.  

## Contributing  
Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.  

## License  
This project is licensed under the [MIT License](LICENSE).  

---  

Feel free to adjust based on specific features or updates!
