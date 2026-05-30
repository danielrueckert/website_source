+++
# An instance of the Blank widget — the Research section.
# Documentation: https://wowchemy.com/docs/page-builder/

widget = "blank"
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Research"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[advanced]
  # Custom CSS.
  css_style = ""

  # CSS class.
  css_class = ""
+++

The Lab for AI in Medicine at [TU Munich](https://www.tum.de/) develops algorithms and models to improve medicine for patients and healthcare professionals. Our aim is to develop artificial intelligence (AI) and machine learning (ML) techniques for the analysis and interpretation of biomedical data. The group focuses on pursuing blue-sky research, including:

- AI for the early detection, prediction and diagnosis of diseases
- AI for personalized interventions and therapies
- AI for the identification of new biomarkers and targets for therapy
- Safe, robust and interpretable AI approaches
- Privacy-preserving AI approaches

We have particularly strong interest in the application of imaging and computing technology to improve the understanding of brain development (in-utero and ex-utero), to improve the diagnosis and stratification of patients with dementia, stroke and traumatic brain injury, as well as for the comprehensive diagnosis and management of patients with cardiovascular disease and cancer.

The following research groups are based at the chair:

- [AI for biomedical image analysis and interpretation](#ai-for-biomedical-image-analysis-and-interpretation)
- [Inverse problems in biomedical imaging](#inverse-problems-in-biomedical-imaging)
- [Privacy-preserving and trustworthy AI in medicine](#privacy-preserving-and-trustworthy-ai-in-medicine)
- [AI for vision](#ai-for-vision)
- AI for opportunistic cardiac MRI

---

## AI for biomedical image analysis and interpretation

[Huaqi (Harvey) Qiu](/author/huaqi-harvey-qiu/)

Medical imaging allows doctors to examine the interior structure or function of the human body, often without the need for invasive surgical procedures. It comprises a range of different techniques, such as computed tomography (CT), magnetic resonance imaging (MR) and ultrasound (US). Clinicians rely on the information provided by medical imaging to monitor patients, diagnose illnesses and decide on treatment.

Our mission is to support doctors in the clinical process and improve patient care by developing advanced algorithms that use artificial intelligence (AI) techniques. To this end, we create and improve machine learning (ML) algorithms for various parts of the medical imaging pipeline. At the image level, we develop methods to tackle tasks such as segmentation of relevant anatomical structures, registration of images across time or modalities, and enhancement of image quality. At the decision level, we innovate solutions to extract clinically useful information from medical images, diagnose diseases and predict future outcomes.

Developing these algorithms in the medical domain presents many challenges which we are striving to overcome. Medical data is often sparse and annotations for algorithm training are costly to acquire, with problems such as domain shift plaguing the few available data, which could be detrimental to ML algorithms. For this, we are developing data-efficient and domain-robust solutions, as well as exploring opportunities provided by the increasing availability of large public datasets / biobanks. Medical images are usually accompanied by additional information from different sources such as doctor's notes, laboratory test results or genomics data, all of which should be considered when interpreting the images. Part of our research centers on developing multi-modal AI solutions that integrate these diverse data sources. Finally, to successfully deploy these algorithms in a hospital setting, we work in close collaboration with medical professionals to align our research with clinical value and to improve the interpretability of our ML algorithms to foster trust and facilitate adoption.

<div class="hrv-carousel">
  <div class="hrv-track">
    <figure class="hrv-slide" id="hrv-slide-1">
      <img src="/home/harvey_research_1.png" alt="Deep learning segmentation of biomedical images: whole body segmentation (left) and spine segmentation from MR images (right)" loading="lazy">
      <figcaption>One of the main focuses of our research is the use of deep learning approaches for the segmentation of biomedical images (e.g. left: whole body segmentation, right: spine segmentation from MR images).</figcaption>
    </figure>
    <figure class="hrv-slide" id="hrv-slide-2">
      <img src="/home/harvey_research_2.png" alt="Registration of a pair of T1-weighted and T2-weighted brain MR images using implicit neural representation of deformation" loading="lazy">
      <figcaption>Image registration is an essential task in medical image analysis. One of our research directions is exploring accurate, robust and efficient image registration. Here, for example, a pair of T1-weighted and T2-weighted brain MR images is registered using an implicit neural representation of deformation.</figcaption>
    </figure>
    <figure class="hrv-slide" id="hrv-slide-3">
      <img src="/home/harvey_research_3.png" alt="Multi-modal AI leveraging ECG and tabular data alongside cardiac MRI for cardiovascular analysis" loading="lazy">
      <figcaption>We are developing multi-modal AI algorithms that can incorporate multiple modalities and sources of information. For example, the methods shown here leverage ECG and tabular data alongside cardiac MRI to improve cardiovascular analysis.</figcaption>
    </figure>
  </div>
  <div class="hrv-dots">
    <a href="#hrv-slide-1" aria-label="Go to slide 1"></a>
    <a href="#hrv-slide-2" aria-label="Go to slide 2"></a>
    <a href="#hrv-slide-3" aria-label="Go to slide 3"></a>
  </div>
</div>

<style>
.hrv-carousel { margin: 1.5rem 0 2rem; }
.hrv-track {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
  gap: 0;
  -webkit-overflow-scrolling: touch;
  border-radius: 8px;
}
.hrv-track::-webkit-scrollbar { display: none; }
.hrv-track { scrollbar-width: none; }
.hrv-slide {
  flex: 0 0 100%;
  scroll-snap-align: center;
  margin: 0;
  padding: 0;
  text-align: center;
}
.hrv-slide img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  display: block;
  object-fit: contain;
  background: #f5f5f5;
}
.hrv-slide figcaption {
  font-size: 0.85rem;
  color: #6c757d;
  margin-top: 0.6rem;
  padding: 0 0.5rem;
  line-height: 1.45;
  text-align: left;
}
.hrv-dots {
  display: flex;
  justify-content: center;
  gap: 0.6rem;
  margin-top: 0.9rem;
}
.hrv-dots a {
  width: 11px;
  height: 11px;
  border-radius: 50%;
  background: #ccc;
  transition: background 0.2s, transform 0.2s;
}
.hrv-dots a:hover { background: #888; transform: scale(1.15); }
</style>

<details>
<summary><strong>Key publications</strong></summary>

- Hager, P., Jungmann, F., Holland, R., Bhagat, K., Hubrecht, I., Knauer, M.M., Vielhauer, J., Makowski, M., Braren, R., Kaissis, G., & Rueckert, D. (2024). Evaluation and mitigation of the limitations of large language models in clinical decision-making. *Nature Medicine, 30*, 2613–2622.
- Dima, A.F., Zimmer, V.A., Menten, M.J., Li, H.B., Graf, M., Lemke, T., Raffler, P., Graf, R., Kirschke, J.S., Braren, R.F., & Rueckert, D. (2023). 3D Arterial Segmentation via Single 2D Projections and Depth Supervision in Contrast-Enhanced CT Images. *MICCAI*.
- Turgut, Ö., Müller, P., Hager, P., Shit, S., Starck, S., Menten, M.J., Martens, E., & Rueckert, D. (2023). Unlocking the Diagnostic Potential of ECG through Knowledge Transfer from Cardiac MRI.
- Müller, P., Kaissis, G., & Rueckert, D. (2024). ChEX: Interactive Localization and Region Description in Chest X-rays. *European Conference on Computer Vision*.
- Mueller, T.T., Starck, S., Bintsi, K., Ziller, A., Braren, R., Kaissis, G., & Rueckert, D. (2024). Are Population Graphs Really as Powerful as Believed? *Trans. Mach. Learn. Res., 2024*.
- Sideri-Lampretsa, V., McGinnis, J., Qiu, H., Paschali, M., Simson, W., & Rueckert, D. (2024). SINR: Spline-enhanced implicit neural representation for multi-modal registration. *Medical Imaging with Deep Learning*.
- Berger, A.H., Stucki, N., Lux, L., Buergin, V., Shit, S., Banaszak, A., Rueckert, D., Bauer, U., & Paetzold, J.C. (2024). Topologically faithful multi-class segmentation in medical images. *MICCAI*.
- Dannecker, M., Kyriakopoulou, V., Cordero-Grande, L., Price, A., Hajnal, J.V., & Rueckert, D. (2024). CINA: Conditional Implicit Neural Atlas for Spatio-Temporal Representation of Fetal Brains. *MICCAI*.
- Starck, S., Sideri-Lampretsa, V., Ritter, J. J., Zimmer, V. A., Braren, R., Mueller, T. T., & Rueckert, D. (2024). Using UK Biobank data to establish population-specific atlases from whole body MRI. *Communications Medicine, 4*(1), 237.
- Zhang, Y., Chen, C., Shit, S., Starck, S., Rueckert, D., & Pan, J. (2024). Whole heart 3D+t representation learning through sparse 2D cardiac MR images. *MICCAI* (pp. 359–369). Springer.

</details>

---

## Inverse problems in biomedical imaging

[Ivan Ezhov](/author/ivan-ezhov/)  ·  [Sevgi Gokce Kafali](/author/sevgi-gokce-kafali/)

Our group is working on inverse problems in biomedical imaging and their solution using artificial intelligence and machine learning.

The development of algorithms to solve inverse problems arising in sensor and imaging systems has a long tradition. Examples include compressed sensing approaches, e.g. for medical and computational imaging. Until recently, most algorithms for inverse problems were based on statistical or physical signal models, such as wavelets or sparse representations. Our research focuses on novel approaches based on deep learning to accelerate solving such problems.

We study how these deep learning-based approaches can be optimized for clinical applications and how they can be combined with image analysis methods. Deep learning-based approaches for reconstructing magnetic resonance imaging (MRI) or computed tomography (CT) provide efficient AI models, allowing the reconstruction of high-quality MRI images, and high-quality CT images from low-dose X-ray images. Recent works on generative models have shown great promise for accelerating reconstruction tasks to shorten the scan time in MRI, as well as generating images with much higher resolution than the acquired resolution (e.g. super-resolution). Here, we tackle these problems by utilizing AI (i.e., diffusion models) guided by readily available MR images from other organs/tissues, MRI scanning parameters, or other MRI physics-guided information.

<details>
<summary><strong>Key publications</strong></summary>

- Schlemper, J., Caballero, J., Hajnal, J.V., Price, A.N. & Rueckert, D. (2017). A deep cascade of convolutional neural networks for dynamic MR image reconstruction. *IEEE Transactions on Medical Imaging*.
- Qin, C., Schlemper, J., Caballero, J., Price, A.N., Hajnal, J.V. & Rueckert, D. (2018). Convolutional recurrent neural networks for dynamic MR image reconstruction. *IEEE Transactions on Medical Imaging*.
- Hammernik, K., Schlemper, J., Qin, C., Duan, J., Summers, R.M. & Rueckert, D. (2021). Systematic evaluation of iterative deep neural networks for fast parallel MRI reconstruction with sensitivity-weighted coil combination. *Magnetic Resonance in Medicine*.
- Hammernik, K., Küstner, T., Yaman, B., Huang, Z., Rueckert, D., Knoll, F. & Akçakaya, M. (2023). Physics-Driven Deep Learning for Computational Magnetic Resonance Imaging. *IEEE Signal Processing Magazine*.
- Huang, W., Li, H.B., Pan, J., Cruz, G., Rueckert, D. & Hammernik, K. (2023). Neural implicit k-space for binning-free non-cartesian cardiac MR imaging. *IPMI*.
- Pan, J., Hamdi, M., Huang, W., Hammernik, K., Kuestner, T. & Rueckert, D. (2024). Unrolled and rapid motion-compensated reconstruction for cardiac CINE MRI. *Medical Image Analysis*.
- Pan, J., Huang, W., Rückert, D., Küstner, T. & Hammernik, K. (2024). Reconstruction-driven motion estimation for motion-compensated MR CINE imaging. *IEEE Transactions on Medical Imaging*.
- Ezhov, I., Scibilia, K., Giannoni, L., Kofler, F., Iliash, I., Hsieh, F., Shit, S., Caredda, C., Lange, F., Montcel, B., Tachtsidis, I., & Rueckert, D. (2024). Learnable real-time inference of molecular composition from diffuse spectroscopy of brain tissue. *Journal of Biomedical Optics*.
- Chung, H., Lee, D., Wu, Z., Kim, B. H., Bouman, K. L., & Ye, J. C. (2025). ContextMRI: Enhancing Compressed Sensing MRI through Metadata Conditioning. *arXiv:2501.04284*.
- Jiang, L., Mao, Y., Wang, X., Chen, X., & Li, C. (2023). Cola-diff: Conditional latent diffusion model for multi-modal MRI synthesis. *MICCAI* (pp. 398–408). Springer.
- Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). High-resolution image synthesis with latent diffusion models. *CVPR* (pp. 10684–10695).

</details>

---

## Privacy-preserving and trustworthy AI in medicine

[Alexander Ziller](/author/alexander-ziller/)

Our group is developing the next generation of privacy-preserving, secure, and trustworthy AI algorithms for medical applications.

AI in medicine requires large, diverse, and representative datasets to train fair, generalizable, and reliable models. However, such datasets often contain sensitive personal information. Privacy-preserving machine learning bridges the gap between data utilization and data protection by enabling the training of AI models on private data while providing formal privacy guarantees. Our group focuses on:

- Differential privacy (DP) theory and applications to machine learning and deep learning, targeting both unstructured datasets (e.g., images) and structured data (e.g., tabular and graph databases).
- Generative models and their applications, such as large language models (LLMs) and agentic systems, integrating differential privacy to ensure secure and privacy-preserving outcomes.
- Data attribution techniques, which enable transparent and accountable data usage in training and inference.
- Developing techniques to mitigate trade-offs between privacy, model utility, and computational efficiency.
- AI security, including the study of vulnerabilities in collaborative machine learning protocols (e.g., federated learning) and designing robust defense mechanisms against adversarial attacks.

Building trust in AI necessitates a comprehensive approach encompassing privacy, reliability, and security. Our work on trustworthy machine learning includes quantifying uncertainty in model outputs, incorporating domain expertise, developing probabilistic models to counteract poorly calibrated predictions, employing computational Bayesian techniques, and exploring the intersection of probabilistic and privacy-preserving machine learning. As AI systems increasingly integrate generative models like LLMs, we also work on establishing formal guarantees of safety and reliability for agentic LLM applications, exploring robustness in generative systems, and ensuring alignment of generative models with human values and ethical guidelines, particularly in high-stakes domains like healthcare.

<div class="hrv-carousel">
  <div class="hrv-track">
    <figure class="hrv-slide" id="priv-slide-1">
      <img src="/home/privacy_research_2.png" alt="Threat models in privacy-preserving machine learning and their impact on the necessary privacy protection and model performance" loading="lazy">
      <figcaption><strong>a,</strong> Adversaries can have various capabilities depending on the setting. <strong>b,</strong> The combination of the adversary's capabilities defines the threat model. In a worst-case analysis, they have all capabilities. However, access to the database is a pessimistic, practically irrelevant scenario. <strong>c,</strong> The necessary privacy protection depends on the threat model. In a worst-case threat model, the adversary only needs to match the model and gradient to an image in the database. In a practically more relevant scenario, the image must be reconstructed from the model and gradient. Here, much less privacy protection is necessary. <strong>d,</strong> The more stringent the privacy protection is chosen, the higher the impacts on the model performance are. Thus, if a realistic threat model is considered appropriate, models can perform better.</figcaption>
    </figure>
    <figure class="hrv-slide" id="priv-slide-2">
      <img src="/home/privacy_research_1.png" alt="Integrated framework for privacy-preserving and secure AI across the machine learning lifecycle" loading="lazy">
      <figcaption>This diagram presents an integrated framework for privacy-preserving and secure AI, highlighting technologies that safeguard both data and algorithms throughout the machine learning lifecycle. Under the Private AI paradigm, techniques like differential privacy protect sensitive medical data from identity leakage and inference attacks. On the Secure AI side, methods such as federated learning, secure multiparty computation, and homomorphic encryption enable collaborative model training without direct data sharing, defending against model theft, inversion, and adversarial manipulation. Together, these methods ensure that both patient data and algorithmic integrity are preserved in sensitive domains like healthcare.</figcaption>
    </figure>
  </div>
  <div class="hrv-dots">
    <a href="#priv-slide-1" aria-label="Go to slide 1"></a>
    <a href="#priv-slide-2" aria-label="Go to slide 2"></a>
  </div>
</div>

<details>
<summary><strong>Key publications</strong></summary>

- Kaiser, J., Ziller, A., Triantafillou, E., Rückert, D., & Kaissis, G. (2026). Your Privacy Depends on Others: Collusion Vulnerabilities in Individual Differential Privacy. *4th IEEE Conference on Secure and Trustworthy Machine Learning (SaTML)*.
- Lockfisch, S., Schwethelm, K., Menten, M., Braren, R., Rueckert, D., Ziller, A., & Kaissis, G. (2025). On Arbitrary Predictions from Equally Valid Models. *AAAI Workshop on Navigating Model Uncertainty and the Rashomon Effect (MURE)*.
- Kaiser, J., Mueller, T., & Kaissis, G. (2025). Differential privacy in medical imaging applications. In *Trustworthy AI in Medical Imaging* (pp. 411–424). Academic Press.
- Koeken, A., Ziller, A., Knolle, M., & Rueckert, D. (2025). Sensitivity, Specificity, and Consistency: A Tripartite Evaluation of Privacy Filters for Synthetic Data Generation. *ICCV 2025 Workshop on Responsible Imaging*.
- Schwethelm, K., Kaiser, J., Kuntzer, J., Yiğitsoy, M., Rückert, D., & Kaissis, G. (2025). Differentially Private Active Learning: Balancing Effective Data Selection and Privacy. *IEEE SaTML* (pp. 858–878). doi:[10.1109/SaTML64287.2025.00053](https://doi.org/10.1109/SaTML64287.2025.00053).
- Schwethelm, K., Kaiser, J., Knolle, M., Lockfisch, S., Rueckert, D., & Ziller, A. (2025). Visual privacy auditing with diffusion models. *Transactions on Machine Learning Research*.
- Ziller, A., Mueller, T., Stieger, S., Feiner, L., Brandt, J., Braren, R., Rueckert, D., & Kaissis, G. (2024). Reconciling Privacy and Accuracy in AI for Medical Imaging. *Nature Machine Intelligence*.
- Kaess, P., Ziller, A., Mantz, L., Rueckert, D., Fintelmann, F. J., & Kaissis, G. (2024). Fair and private CT contrast agent detection. *MICCAI Workshop on Fairness of AI in Medical Imaging* (pp. 34–45). Springer.
- Kaissis, G., Kolek, S., Balle, B., Hayes, J., & Rueckert, D. (2024). Beyond the calibration point: Mechanism comparison in Differential Privacy. *International Conference on Machine Learning*.
- Tayebi Arasteh, S., Ziller, A., Kuhl, C., Makowski, M., Nebelung, S., Braren, R., Rueckert, D., Truhn, D., & Kaissis, G. (2024). Preserving fairness and diagnostic accuracy in private large-scale AI models for medical imaging. *Communications Medicine*.
- Hölzl, F. A., Rueckert, D., & Kaissis, G. (2023). Equivariant differentially private deep learning: Why DP-SGD needs sparser models. *16th ACM Workshop on Artificial Intelligence and Security* (pp. 11–22).
- Kaissis, G., Ziller, A., Kolek, S., Riess, A., & Rueckert, D. (2023). Optimal privacy guarantees for a relaxed threat model: Addressing sub-optimal adversaries in differentially private machine learning. *NeurIPS*.
- Mueller, T.T., Paetzold, J.C., Prabhakar, C., Usynin, D., Rueckert, D., & Kaissis, G. (2022). Differentially Private Graph Neural Networks for Whole-Graph Classification. *IEEE TPAMI*.
- Usynin, D., Ziller, A., Makowski, M., Braren, R., Rueckert, D., Glocker, B., Kaissis, G., & Passerat-Palmbach, J. (2021). Adversarial interference and its mitigations in privacy-preserving collaborative machine learning. *Nature Machine Intelligence*.
- Kaissis, G., Ziller, A., Passerat-Palmbach, J., Ryffel, T., Usynin, D., Trask, A., Lima Jr, I., Mancuso, J., Jungmann, F., Steinborn, M.M., & Saleh, A. (2021). End-to-end privacy preserving deep learning on multi-institutional medical imaging. *Nature Machine Intelligence*.
- Kaissis, G., Makowski, M.R., Rückert, D., & Braren, R.F. (2020). Secure, privacy-preserving and federated machine learning in medical imaging. *Nature Machine Intelligence*.

</details>

---

## AI for vision

[Martin Menten](/author/martin-menten/)

The AI for Vision group focuses on blue-sky research in medical image analysis with a particular focus on the application of machine learning and computer vision algorithms in the field of ophthalmology. Specifically, we are working on:

**Self-supervised learning.** Labeling medical data is very expensive, as it is time-consuming and requires expert knowledge. Moreover, medical data often includes highly sensitive information, making it challenging to share without compromising the privacy of the subjects involved. To overcome the limited availability of large annotated medical datasets, we are researching self-supervised learning, leveraging unlabeled medical data to enable neural networks to extract meaningful features that can be effectively adapted to a wide range of downstream tasks.

**Multimodal deep learning.** Clinicians rarely rely on a single source of information when diagnosing patients and deciding on a course of action. They consider an array of multimodal data, such as demographic and genomic information, patient interviews, laboratory test results and biomedical images. Our research focuses on developing deep learning algorithms capable of integrating diverse multimodal data to support autonomous and effective clinical decision making.

**Deep learning for ophthalmology.** Good vision is essential for navigating our environment, communicating, and performing everyday activities. As of 2020, more than 200 million people worldwide suffered from moderate to severe vision impairment. Driven by the comparative ease of imaging the eye and obtaining large imaging datasets, ophthalmology has been an early adopter of deep learning in healthcare. Our group's work in machine learning for ophthalmology simultaneously evaluates new algorithmic innovations while aiming to improve medical care for patients affected by ocular diseases.

<details>
<summary><strong>Key publications</strong></summary>

- Holland, R., Leingang, O., Bogunović, H., Riedl, S., Fritsche, L., Prevost, T., Scholl, H. P. N., Schmidt-Erfurth, U., Sivaprasad, S., Lotery, A. J., Rueckert, D., & Menten, M. J. (2024). Metadata-enhanced contrastive learning from retinal optical coherence tomography images. *Medical Image Analysis, 97*:103296.
- Kreitner, L., Paetzold, J. C., Rauch, N., Chen, C., Hagag, A. M., Fayed, A. E., Sivaprasad, S., Rausch, S., Weichsel, J., Menze, B. H., Harders, M., Knier, B., Rueckert, D., & Menten, M. J. (2024). Synthetic optical coherence tomography angiographs for detailed retinal vessel segmentation without human annotations. *IEEE Transactions on Medical Imaging, 43*(6):2061–2073.
- Menten, M. J., Paetzold, J. C., Zimmer, V. A., Shit, S., Ezhov, I., Holland, R., Probst, M., Schnabel, J. A., & Rueckert, D. (2023). A skeletonization algorithm for gradient-based optimization. *ICCV*, 21394–21403.
- Holland, R., Leingang, O., Holmes, C., Anders, P., Kaye, R., Riedl, S., Paetzold, J. C., Ezhov, I., Bogunović, H., Schmidt-Erfurth, U., Scholl, H. P. N., Sivaprasad, S., Lotery, A. J., Rueckert, D., & Menten, M. J. (2023). Clustering disease trajectories in contrastive feature space for biomarker proposal in age-related macular degeneration. *MICCAI*, 724–734.
- Menten, M. J., Holland, R., Leingang, O., Bogunović, H., Hagag, A. M., Kaye, R., Riedl, S., Traber, G. L., Hassan, O. N., Pawlowski, N., Glocker, B., Fritsche, L. G., Scholl, H. P. N., Sivaprasad, S., Schmidt-Erfurth, U., Rueckert, D., & Lotery, A. J. (2023). Exploring healthy retinal aging with deep learning. *Ophthalmology Science, 3*(3):100294.
- Hager, P., Menten, M. J., & Rueckert, D. (2023). Best of both worlds: Multimodal contrastive learning with tabular and imaging data. *CVPR*, 23924–23935.
- Menten, M. J., Paetzold, J. C., Dima, A., Menze, B. H., Knier, B., & Rueckert, D. (2022). Physiology-based simulation of the retinal vasculature enables annotation-free segmentation of OCT angiographs. *MICCAI*, 330–340.

</details>