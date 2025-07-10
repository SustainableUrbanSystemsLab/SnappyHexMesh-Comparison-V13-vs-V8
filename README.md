# # SnappyHexMesh-Comparison-V13-vs-V8

# Comparing Mesh Quality in OpenFOAM v8 and v13

I ran SnappyHexMesh on the same geometry using OpenFOAM v8 and v13 with identical settings to compare their performance, mainly to decide which one works better for the **Comfort+ meshing setup**.

Both versions gave valid meshes, but v13 ended up generating about **1,200 more hexahedral cells** and a slightly higher total cell count (~2.02M vs. ~2.01M). Polyhedral counts, point counts, and surface faces were also a bit higher in v13. Quality metrics like **non-orthogonality, skewness, and aspect ratio** were very similar in both, though v13 had a slightly better max aspect ratio and openness.

Overall, even with the same settings, version differences can impact mesh structure. This test helps us move forward with choosing v13 as the preferred version for our Comfort+ workflow.

<img width="2539" height="895" alt="image" src="https://github.com/user-attachments/assets/521b0b01-fde9-4567-85f1-fb89a772d843" />

![1](https://github.com/user-attachments/assets/798254e8-7122-45d3-867e-05ff2eced879)

![2](https://github.com/user-attachments/assets/559efba1-9df5-4a88-a13a-49cc4eec815b)

![3](https://github.com/user-attachments/assets/1cf17c12-0ac0-4dd0-a93a-f0de0366f934)

