## Project Title: Enhancing Doodles with Bezier Curves and Circle Fitting

Here is the colab notebook link:
- Regularization.ipynb: https://colab.research.google.com/drive/1L0jli7v26hM0yPadoTW8-m_TrsRkQpVI?usp=sharing
- Symmetry and Occlusion.ipynb: https://colab.research.google.com/drive/1GyEIuJzwvbksrrBzNMhIfDyTUF85N5AW?usp=sharing

### Introduction

This project explores innovative methods to enhance and regularize doodles by focusing on symmetry enhancement and completing incomplete curves. Utilizing advanced geometric techniques, specifically Bezier curves and a specialized circle fitting algorithm, we aim to transform doodles into more aesthetically pleasing and coherent artworks.

### Problem Statement

Doodles often lack symmetry and may have incomplete segments, which can detract from their overall appeal. This project seeks to address these issues by applying mathematical models to doodles, thereby improving their visual harmony and completeness.

### Approach

#### Bezier Curves for Smoothness

- **Objective**: To enhance the smoothness and flow of doodles by fitting cubic Bezier curves through selected points.
- **Method**: Segmentation of doodles into individual lines or strokes, followed by curve fitting to create a continuous, symmetrical path.

![WhatsApp Image 2024-08-11 at 14 26 07_ee7433ae](https://github.com/user-attachments/assets/c541424c-99f0-48ab-aed8-9b61bf7f7d77)


#### Circle Fitting for Symmetry

- **Objective**: To introduce symmetry within doodles by identifying and incorporating circles.
- **Method**: Application of a circle fitting algorithm to select points within the doodle, forming circles that complement the doodle's organic form.

![WhatsApp Image 2024-08-11 at 22 21 56_ba5779d0](https://github.com/user-attachments/assets/ec73d66f-6a05-4dfd-9c9f-76c38800015c)


### Methodology

1. **Segmentation**: Divide the doodle into discrete segments.
2. **Bezier Curve Fitting**: Apply cubic Bezier curves to each segment, optimizing control points for smooth transitions.
3. **Circle Identification**: Use circle fitting to locate potential circles within the doodle.
4. **Integration**: Integrate identified circles into the doodle, enhancing symmetry and completeness.

### Challenges and Learnings

- **Complexity of Doodles**: The variability in doodle styles poses challenges in generalizing the regularization process.
- **Subjectivity in Aesthetics**: The perception of symmetry and aesthetics varies among individuals, affecting the evaluation of the regularization outcome.
- **Computational Considerations**: Geometric operations, such as circle fitting and Bezier curve fitting, demand significant computational resources, especially for complex doodles.

### Conclusion

While the project aimed to leverage Bezier curves and circle fitting to enhance doodles, the complexity of doodle styles and the subjectivity of aesthetics presented significant challenges. Despite these obstacles, the project contributed valuable insights into the application of geometric techniques in the realm of digital art and design. Future iterations will focus on overcoming these challenges to further refine the doodle regularization process.

### Getting Started

This project is currently under development. Detailed setup instructions and code snippets will be available once the project reaches a stable phase.



#

This README provides a comprehensive overview of the project, detailing the problem statement, methodology, challenges faced, and future directions. It serves as a foundational document for anyone interested in learning more about the project or contributing to its development.

