# RetinaLogos: Fine-Grained Synthesis of High-Resolution Retinal Images Through Captions

This is the implementation of **[RetinaLogos: Fine-Grained Synthesis of High-Resolution Retinal Images Through Captions](#)**, a method designed to synthesize high-resolution Color Fundus Photographs (CFPs) from textual descriptions of retinal conditions. Our method overcomes the limitations of current retinal image synthesis models by offering more detailed and fine-grained control over anatomical structures and disease progression using large-scale text-to-image generation.

## 🌟 Abstract

The scarcity of high-quality labelled retinal imaging data poses a significant challenge in ophthalmology. In this work, we introduce RetinaLogos, a novel text-to-image framework that utilizes a large-scale synthetic caption dataset (1.4 million entries) to generate high-resolution retinal images. Our method combines Electronic Health Records (EHRs) and multimodal text generation, enabling fine-grained semantic control over the generated images. RetinaLogos can synthesize retinal images that capture subtle anatomical variations and disease progressions, which can be beneficial for early detection and clinical training purposes. Our approach shows state-of-the-art performance across multiple datasets, demonstrating a 10%-25% improvement in classification tasks, such as diabetic retinopathy grading and glaucoma detection.

## 🚀 Model Pipelines and Fusion Graphical Illustration:

![Overview of Method Pipeline](./path/to/your/pipeline_image.png)
![Overview of Method Fusion](./path/to/your/fusion_image.png)

## 🖼️ Illustrative Examples

Below are some examples demonstrating the impact of textual prompts on synthetic retinal image generation:

### Example 1: Diabetic Retinopathy (DR) Progression
| Prompt | Generated Image |
| --- | --- |
| **Age: 50, Stage: Early DR** | ![Early DR](./path/to/early_dr_image.png) |
| **Age: 50, Stage: Advanced DR** | ![Advanced DR](./path/to/advanced_dr_image.png) |

### Example 2: Glaucoma Detection
| Prompt | Generated Image |
| --- | --- |
| **Diagnosis: Glaucoma** | ![Glaucoma](./path/to/glaucoma_image.png) |

### Example 3: Pathological Features
| Prompt | Generated Image |
| --- | --- |
| **Diagnosis: Macular Hole** | ![Macular Hole](./path/to/macular_hole_image.png) |

## 🎉 More Examples
Here are additional examples demonstrating diverse generation capabilities based on different retinal conditions and disease stages.

- **Example 1: Stage-wise Diabetic Retinopathy**
- **Example 2: Retinal Nerve Fiber Layer Analysis**

## 💡 Highlights

- **Large-scale Synthetic Dataset**: We assembled 1.4 million synthetic retinal caption-image pairs to enable high-resolution, clinically relevant image synthesis.
- **Fine-grained Control**: Our method allows for detailed control over retinal anatomical structures and disease stages via free-form textual prompts.
- **Superior Performance**: RetinaLogos outperforms existing models in generating clinically accurate and high-quality retinal images.
- **Generalizable Framework**: Our framework can be applied to a wide range of ophthalmological conditions, supporting future research in medical image synthesis.
