# RetinaLogos: Fine-Grained Synthesis of High-Resolution Retinal Images Through Captions

This is the implementation of **RetinaLogos: Fine-Grained Synthesis of High-Resolution Retinal Images Through Captions**, a method designed to synthesize high-resolution Color Fundus Photographs (CFPs) from textual descriptions of retinal conditions. Our method overcomes the limitations of current retinal image synthesis models by offering more detailed and fine-grained control over anatomical structures and disease progression using large-scale text-to-image generation.

## 🌟 Abstract

The scarcity of high-quality labelled retinal imaging data poses a significant challenge in ophthalmology. In this work, we introduce **RetinaLogos**, a novel text-to-image framework that utilizes a large-scale synthetic caption dataset (1.4 million entries) to generate high-resolution retinal images. Our method combines Electronic Health Records (EHRs) and multimodal text generation, enabling fine-grained semantic control over the generated images. **RetinaLogos** can synthesize retinal images that capture subtle anatomical variations and disease progressions, which can be beneficial for early detection and clinical training purposes. Our approach shows state-of-the-art performance across multiple datasets, demonstrating a 10%-25% improvement in classification tasks, such as diabetic retinopathy grading and glaucoma detection.

## 🚀 Model Pipelines and Fusion Graphical Illustration:
- **Overview of Method Pipeline**
  ![Method Pipeline](path/to/pipeline_image.png)
  
- **Overview of Method Fusion**
  ![Method Fusion](path/to/fusion_image.png)

## Generated CFP Results and Downstream Datasets

- **Overview of AUthenicity Test with Real CFPs Results**
  ![Authenticity Test](path/to/authenticity_test_image.png)
  
- **Quantitative Comparison of Synthetic CFP with Real CFP**
  ![Synthetic vs Real CFP](path/to/synthetic_vs_real_comparison.png)
  
- **Performance of Diabetic Retinopathy Grading Classification and Glaucoma Detection**
  ![Classification Performance](path/to/classification_performance.png)

## 🖼️ Illustrative Examples:
- **Visual Comparison of Generated CFPs under Different Stages, Resolutions and Pathological Structures**
  ![Visual Comparison](path/to/visual_comparison_image.png)
  
- **Comparison of Ophthalmology Evaluation Scores on Individual Retinal Disease Criteria**
  ![Evaluation Scores](path/to/evaluation_scores.png)

- **More Generated Examples of Rare Diseases**
  ![Rare Diseases Examples](path/to/rare_diseases_examples.png)

- **Fine-Grained Control of Diabetic Retinopathy (DR) Progression with Text Descriptions**
  ![DR Progression](path/to/dr_progression_image.png)

- **More Examples of Different Diseases**
  ![Disease Examples](path/to/disease_examples.png)

## 💡 Highlights

- **Large-scale Synthetic Dataset**: We assembled 1.4 million synthetic retinal caption-image pairs to enable high-resolution, clinically relevant image synthesis.
  
- **Fine-grained Control**: Our method allows for detailed control over retinal anatomical structures and disease stages via free-form textual prompts.
  
- **Superior Performance**: RetinaLogos outperforms existing models in generating clinically accurate and high-quality retinal images.
  
- **Generalizable Framework**: Our framework can be applied to a wide range of ophthalmological conditions, supporting future research in medical image synthesis.

## 🚨 Code Release

We plan to release the source code for **RetinaLogos** if the paper is accepted. Stay tuned for the release, which will be made available on our GitHub repository.
