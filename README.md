# Unique Colors for Colorblindness Detection  

Project focuses on simulating color perception for different types of colorblindness (protanopia, deuteranopia, tritanopia, and monochromacy) and identifying unique color shades that maximize confusion.  

Key components include:  
1. **Dataset** – Generating a base color set and simulating color vision deficiencies.  
2. **Processing**: Unique Colors Detection – Grouping colors using clustering algorithms and selecting unique shades.  
3. **Results**: Confusion Samples – Providing the most common palettes for colorblindness, while ensuring the most distinct ones for healthy vision..  

## Table of Contents  
1. [Introduction](#introduction)  
2. [Installation](#installation)  
3. [Methodology](#methodology)  
4. [Results](#results)  
5. [Contributing](#contributing)  
6. [License](#license)  

## Introduction  
Colorblindness affects how individuals perceive colors, making it difficult to distinguish between certain shades.
Project identifies color shades that are either frequently confused for different types of colorblindness. These findings provide *a foundation for designing diagnostic tests aimed at evaluating color vision deficiencies*.

## Installation  
To set up this project - clone the repository:  
   ```bash  
   git clone https://github.com/your-username/unique-colors-colorblindness.git  
   ```  

## Methodology  
- Generate a base set of RGB colors.  
- Convert colors to LAB format for further analysis.  
- Apply filters for different types of colorblindness (protanopia, deuteranopia, tritanopia, monochromacy).  
- Group transformed colors using clustering.  
- Select unique shades using variance metrics.  

## Results  

*- Unique confusion samples based on original color palettes for each type of colorblindness are detected.* 

<img src="https://github.com/user-attachments/assets/2f22df3f-917e-436f-9a1f-fce90ed452b6" alt="Description of image" width="945"/>

<img src="https://github.com/user-attachments/assets/720fd483-6ce4-4380-9256-1b2dea08daf9" alt="Description of image" width="230"/>
<img src="https://github.com/user-attachments/assets/77591772-8579-4572-bec2-4ebbc2d9591c" alt="Description of image" width="228"/>
<img src="https://github.com/user-attachments/assets/f705edc3-bfae-4677-84b3-5423bf32b3aa" alt="Description of image" width="243"/>
<img src="https://github.com/user-attachments/assets/7130dd51-5242-48c3-bbaa-ed60b4ee0318" alt="Description of image" width="230"/>

## Contributing  
Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.  

## License  
This project is licensed under the [MIT License](LICENSE).  

---  

Feel free to adjust based on specific features or updates!
