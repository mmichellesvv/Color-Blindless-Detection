# Unique Colors for Colorblindness Detection  

Project focuses on simulating color perception for different types of colorblindness (protanopia, deuteranopia, tritanopia, and monochromacy) and identifying unique color shades that minimize confusion.  

Key components include:  
1. **Dataset** – Generating a base color set and simulating color vision deficiencies.  
2. **Processing**: Unique Colors Detection – Grouping colors using clustering algorithms and selecting distinct shades based on color variance metrics (RGB and LAB).  
3. **Results**: Confusion Samples – Providing optimized palettes for colorblind users, improving accessibility and visual differentiation.  

## Table of Contents  
1. [Introduction](#introduction)  
2. [Installation](#installation)  
3. [Methodology](#methodology)  
4. [Results](#results)  
5. [Contributing](#contributing)  
6. [License](#license)  

## Introduction  
Colorblindness affects how individuals perceive colors, making it difficult to distinguish between certain shades.
Project identifies color shades that are either frequently confused for different types of colorblindness. These findings provide a foundation for designing diagnostic tests aimed at evaluating color vision deficiencies.
In the future, this work could support the development of adaptive tools to improve color accessibility and visualization for colorblind users.

## Installation  
To set up this project, follow these steps:  
1. Clone the repository:  
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
Optimized color palettes and confusion samples for each type of colorblindness are generated, providing visual differentiation and accessibility improvements.  

<img src="https://github.com/user-attachments/assets/2f22df3f-917e-436f-9a1f-fce90ed452b6" alt="Description of image" width="985"/>


<img src="https://github.com/user-attachments/assets/720fd483-6ce4-4380-9256-1b2dea08daf9" alt="Description of image" width="240"/>
<img src="https://github.com/user-attachments/assets/77591772-8579-4572-bec2-4ebbc2d9591c" alt="Description of image" width="238"/>
<img src="https://github.com/user-attachments/assets/f705edc3-bfae-4677-84b3-5423bf32b3aa" alt="Description of image" width="253"/>
<img src="https://github.com/user-attachments/assets/7130dd51-5242-48c3-bbaa-ed60b4ee0318" alt="Description of image" width="240"/>

## Contributing  
Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.  

## License  
This project is licensed under the [MIT License](LICENSE).  

---  

Feel free to adjust based on specific features or updates!
