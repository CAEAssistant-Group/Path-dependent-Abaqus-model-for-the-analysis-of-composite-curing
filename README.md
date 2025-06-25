# Path-dependent-Abaqus-model-for-the-analysis-of-composite-curing

This Project introduces a novel method for investigating cure-induced residual stresses in composite materials through a path-dependent model in Abaqus. The model is implemented within Abaqus CAE using various Fortran subroutines, including USDFLD, UMAT, HETVAL, UEXPAN, and DISP.

![image](https://github.com/user-attachments/assets/8c9bf364-57c7-441b-9b2a-b53793160476)

Since the Abaqus viscoelastic model is an advanced topic, some users may prefer simpler tools, one of the most well-known being the Abaqus path-dependent model. The Abaqus path-dependent curing model is simpler than the Abaqus viscoelastic curing model. In this project, we provided subroutine codes for the Abaqus path-dependent model for curing. We used the Abaqus path-dependent model to analyze residual stresses, strains, temperature, and the degree of cure in AS4/3501-6 prepreg. For verification, we compared the results with the reference solution. For example, as shown in the figure below, the stress during the curing process for AS4/3501-6 prepreg is well verified against the reference solution.

![image](https://github.com/user-attachments/assets/fc940dfd-bc1f-4156-a1b6-0599f01f8af7)

This repository contains the full .inp file along with some portions of the Fortran subroutines used in the Abaqus path-dependent curing model. The included subroutines are DISP, USDFLD, UMAT, HETVAL, and UEXPAN. For a more comprehensive understanding of these models, including theoretical insights and the complete Fortran codes for the Abaqus path-dependent curing model, refer to our full package. The access link is available in the "About" section on the right.

![image](https://github.com/user-attachments/assets/fbcd7b3d-0c9e-49b0-b96e-df8c0da63ee4)

**ℹ️ This is just a demo to show how the code is structured. For the full, working version, please visit our website.**
