# Awesome 3D Drawing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of 3D drawing papers and related resources on using motion-tracked controllers in XR to create art and animation, combined with ML processing and rendering of frame-by-frame volumetric representations. These approaches are yielding results of increasing interest to mainstream animation and VFX production.

## Contents
- [Papers](#papers)
  - [3D Drawing Implementations](#3d-drawing-implementations)
  - [3D Drawing Techniques and Analysis](#3d-drawing-techniques-and-analysis)
  - [Related 3D Processing Techniques](#related-3d-processing-techniques)
  - [Related Mocap and Volcap](#related-mocap-and-volcap)
  - [Related Dissertation / Thesis](#related-dissertation--thesis)
  - [Related Graphics History](#related-graphics-history)
- [Datasets](#datasets)
 
## Papers
### 3D Drawing Implementations
- Richard Liu et al - [WIR3D: Visually-Informed and Geometry-Aware 3D Shape Abstraction](https://arxiv.org/abs/2505.04813) (2025). {[code](https://github.com/threedle/wir3d)}
- Changwoon Choi et al - [3Doodle: Compact Abstraction of Objects with 3D Strokes](https://arxiv.org/abs/2402.03690) (2024). {[code](https://github.com/changwoonchoi/3Doodle)}
- Nick Fox-Gieg - [Lightning Artist Toolkit: A Hand-Drawn Volumetric Animation Pipeline](https://doi.org/10.1145/3664221) (2024). {[code](https://github.com/n1ckfg/latk_blender)}
- Yunfan Ye et al - [NEF: Neural Edge Fields for 3D Parametric Curve Reconstruction from Multi-View Images](https://arxiv.org/abs/2303.07653) (2023). {[code](https://github.com/yunfan1202/NEF_code)}
- Caroline Chan et al - [Learning to Generate Line Drawings That Convey Geometry and Semantics](https://arxiv.org/abs/2203.12691) (2022). {[code](https://github.com/carolineec/informative-drawings)}
- Geonmo Gu et al - [Towards Light-weight and Real-time Line Segment Detection](https://arxiv.org/pdf/2106.00186) (2022). {[code](https://github.com/navervision/mlsd)} {[code2](https://github.com/keijiro/MlsdBarracuda)}
- Wangziwei Jiang et al - [GPU-Driven Real-Time Mesh Contour Vectorization](https://diglib.eg.org/bitstream/handle/10.2312/sr20221159/093-105.pdf) (2022). {[code](https://github.com/JiangWZW/Realtime-GPU-Contour-Curves-from-3D-Mesh)}
- Emilie Yu et al - [CASSIE: Curve and Surface Sketching in Immersive Environments](https://www-sop.inria.fr/reves/Basilic/2021/YASBS21/CASSIE_author_version.pdf) (2021). {[code](https://gitlab.inria.fr/D3/cassie)}
- Yulia Gryaditskaya et al - [Lifting Freehand Concept Sketches into 3D](https://repo-sam.inria.fr/d3/Lift3D/Gryaditskaya_SigAsia20_Lifting%20_Freehand_Concept_Sketches_into_3D.pdf) (2020). {[code](https://github.com/ygryadit/LiftConceptSketches3D)}
- Bastien Wailly and Adrien Bousseau - [Line Rendering of 3D Meshes for Data-Driven Sketch-Based Modeling](https://www-sop.inria.fr/reves/Basilic/2019/WB19b/bwailly_JFIGRV_2019.pdf) (2019). {[code](https://gitlab.inria.fr/D3/contour-detect)}
- Pierre Bénard et al - [Active Strokes: Coherent Line Stylization for Animated 3D Models](https://inria.hal.science/hal-00693453/en) (2012). {[code](https://github.com/benardp/ActiveStrokes)}

### 3D Drawing Techniques and Analysis
- Karran Pandey et al - [Painting with 3D Gaussian Splat Brushes](https://dl.acm.org/doi/10.1145/3721238.3730724) (2025).
- Zhi-Zheng Xiang et al - [BrushGaussian: Brushstroke-Based Stylization for 3D Gaussian Splatting](https://www.mdpi.com/2076-3417/15/12/6881) (2025).
- Hao Li et al - [An Inverse Procedural Modeling Pipeline for Stylized Brush Stroke Rendering](https://diglib.eg.org/server/api/core/bitstreams/f12e87c6-6eda-4376-b77a-71eb945ebd8a/content) (2024).
- Yuta Noma et al - [Surface-Filling Curve Flows via Implicit Medial Axes](https://www.dgp.toronto.edu/projects/surface-filling-curves/surface-filling-curves.pdf) (2024).
- Richard Rodriguez et al - [Artists' Perspectives on Natural Interactions for Virtual Reality 3D Sketching](https://dl.acm.org/doi/10.1145/3613904.3642758) (2024).
- Yael Vinker et al - [CLIPasso: Semantically-Aware Object Sketching](https://arxiv.org/abs/2202.05822) (2022).
- Kevin Frans et al - [CLIPDraw: Exploring Text-to-Drawing Synthesis through Language-Image Encoders](https://arxiv.org/abs/2106.14843) (2021).
- Ying Jiang et al - [HandPainter: 3D Sketching in VR with Hand-based Physical Proxy](https://yingjiang96.github.io/handpaintermaterial/handpainter.pdf) (2021).
- Enrique Rosales et al - [Adaptive General and Predictable VR Ribbon Brush](https://www.cs.ubc.ca/labs/imager/tr/2021/AdaptiBrush/) (2021).
- Aaron Hertzmann - [Why Do Line Drawings Work? A Realism Hypothesis](https://arxiv.org/abs/2002.06260) (2020).
- Difan Liu et al - [Neural Contours: Learning to Draw Lines from 3D Shapes](https://arxiv.org/abs/2003.10333) (2020).
- Mayra Barrera-Machuca et al - [The Effect of Spatial Ability on Immersive 3D Drawing](https://vvise.iat.sfu.ca/pubs/machuca2019spatial) (2019).
- Rahul Ahora et al - [Experimental Evaluation of Sketching on Surfaces in VR](https://www.research.autodesk.com/app/uploads/2023/03/experimental-evaluation-of-sketching.pdf_recSPFZ4RbLaE2Uio.pdf) (2017).
- David Ha and Douglas Eck - [A Neural Representation of Sketch Drawings](https://arxiv.org/abs/1704.03477) (2017).
- Daniel Keefe et al - [Drawing on Air: Input Techniques for Controlled 3D Line Illustration](https://cs.brown.edu/research/pubs/pdfs/2007/Keefe-2007-DOA.pdf) (2007).
- Scott Snibbe et al - [Springs and Constraints for 3D Drawing](https://www.researchgate.net/publication/228584605_Springs_and_constraints_for_3D_drawing) (1998).
- Michael Deering - [Holosketch: A Virtual Reality Sketching/Animation Tool](https://dl.acm.org/doi/10.1145/210079.210087) (1995).

### Related 3D Processing Techniques
- Marco Domenico Cirillo et al - [Vox2Vox 3D-GAN for Brain Tumour Segmentation](https://arxiv.org/abs/2003.13653) (2020). {[code](https://github.com/mdciri/Vox2Vox)} {[code2](https://github.com/enochkan/vox2vox)}
- Phillip Isola et al - [Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004) (2016).
- Manuel Ruder et al - [Artistic Style Transfer for Videos](https://arxiv.org/abs/1604.08610) (2016).
- Dena Bazazian et al - [Fast and Robust Edge Extraction in Unorganized Point Clouds](https://ieeexplore.ieee.org/document/7371262) (2015). {[code](https://github.com/denabazazian/Edge_Extraction)}
- Leon Gatys et al - [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) (2015).
- Sergio Orts-Escolano et al - [3D Colour Object Reconstruction Based on Growing Neural Gas](https://ieeexplore.ieee.org/document/6889546) (2014). {[code](https://github.com/rendchevi/growing-neural-gas)}
- Tongjie Zhang and Ching Yee Suen - [A Fast Parallel Algorithm for Thinning Digital Patterns](https://dl.acm.org/doi/10.1145/357994.358023) (1984). {[code](https://github.com/LingDong-/skeleton-tracing)}

### Related Mocap and Volcap
- Christopher Remde et al - [Sparse Camera Volumetric Video Applications: A Comparison of Visual Fidelity, User Experience, and Adaptability](https://www.frontiersin.org/journals/signal-processing/articles/10.3389/frsip.2025.1405808/full) (2025).
- Haiyong Jiang et al - [Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds](https://openaccess.thecvf.com/content_ICCV_2019/papers/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.pdf) (2019).
- Naureen Mahmood et al - [AMASS: Archive of Motion Capture As Surface Shapes](https://files.is.tue.mpg.de/black/papers/amass.pdf) (2019). {[code](https://github.com/nghorbani/amass)}
- Joao Regateiro et al - [Hybrid Skeleton Driven Surface Registration for Temporally Consistent Volumetric Video](https://cvssp.org/projects/4d/HSDSR/Regateiro_3DV2018.pdf) (2018).
- Marek Kowalski et al - [LiveScan3D: A Fast and Inexpensive 3D Data Acquisition System for Multiple Kinect v2 Sensors](https://www.researchgate.net/publication/308807023_Livescan3D_A_Fast_and_Inexpensive_3D_Data_Acquisition_System_for_Multiple_Kinect_v2_Sensors) (2015). {[code](https://github.com/BuildingVolumes/LiveScan3D)}

### Related Dissertation / Thesis
- Nick Fox-Gieg - [Lightning Artist Toolkit: A Hand-Drawn Volumetric Animation Pipeline](https://hdl.handle.net/10315/42999) (2025).
- Emilie Yu - [Designing Tools for 3D Content Authoring Based on 3D Sketching](https://theses.hal.science/tel-04484971v1) (2023).
- Rahul Arora - [Creative Visual Expression in Immersive 3D Environments](https://utoronto.scholaris.ca/items/e41e9604-a6ed-40f2-891d-222c212f4cb3) (2021).
- Maria Shugrina - [The Design of Playful and Intelligent Creative Tools](https://utoronto.scholaris.ca/items/30b67df3-138b-4f3f-8304-6e22bbc4b449) (2021).
- Emilie Yu - [Interactive 3D Sketching in Virtual Reality](https://em-yu.github.io/media/papers/MSc_Thesis__Emilie_Yu_v3.pdf) (2020).
- Caroline Chan - [First Principles of Line Drawings](https://dspace.mit.edu/bitstream/handle/1721.1/139322/Chan-cmchan-SM-EECS-2021-thesis.pdf) (2017).
- Jennifer Jacobs - [Dynamic Drawing: Broadening Practice and Participation in Procedural Art](https://www.media.mit.edu/publications/dynamic-drawing-broadening-practice-and-participation-in-procedural-art/) (2017).
- Johannes Schmid - [Methods for Artistic Stylization in 3D Animation](https://cgl.ethz.ch/Downloads/Publications/Dissertations/Schm12.pdf) (2012).
- Alexander Kolliopoulos - [Image Segmentation for Stylized Non-Photorealistic Rendering and Animation](https://www.dgp.toronto.edu/~alexk/segnpr.html) (2005).
- Steven Schkolne - [3D Interfaces for Spatial Construction](https://thesis.caltech.edu/2127/1/phd.pdf) (2004).
- Aaron Hertzmann - [Algorithms for Rendering in Artistic Styles](https://cs.nyu.edu/media/publications/hertzmann_aaron.pdf) (2001).
- Golan Levin - [Painterly Interfaces for Audiovisual Performance](https://acg.media.mit.edu/people/golan/thesis/thesis300.pdf) (2000).
- Rebecca Allen - [Computer Rotoscoping with the Aid of Color Recognition](https://dspace.mit.edu/handle/1721.1/71031?show=full) (1980).
- Ronald Baecker - [Interactive Computer-Mediated Animation](https://publications.csail.mit.edu/lcs/pubs/pdf/MIT-LCS-TR-061.pdf) (1969). 
- Thomas A. DeFanti - [The Graphics Symbiosis System](https://etd.ohiolink.edu/acprod/odb_etd/r/etd/search/10?p10_accession_num=osu1486740394721916) (1973).
- Ivan Sutherland - [Sketchpad: A Man-Machine Graphical Communication System](https://dl.acm.org/doi/10.1145/1461551.1461591) (1963).

### Related Graphics History
- Amanda Long - [The Media Archaeology of the Sandin Image Processor](https://www.isea-symposium-archives.org/wp-content/uploads/2024/08/2023_Long_Copy-It-Right_The_Distribution_Religion.pdf) (2023). {[code](https://github.com/amandalong/Sandin-Image-Processor)}
- Richard Shoup - [SuperPaint: An Early Frame Buffer Graphics System](https://www.computer.org/csdl/magazine/an/2001/02/man2001020032/13rRUyft7wz) (2001).
- Brian Knep et al - [Dinosaur Input Device](https://dl.acm.org/doi/10.1145/223904.223943) (1995).
- Carolina Cruz-Neira et al - [The CAVE: Audio Visual Experience Automatic Virtual Environment](https://dl.acm.org/doi/10.1145/129888.129892) (1992).
- Marc Levoy - [A Color Animation System Based on the Multiplane Technique](https://dl.acm.org/doi/10.1145/965141.563871) (1977).
- Nestor Burtnyk and Marceli Wein - [Interactive Skeleton Techniques for Enhancing Motion Dynamics in Key Frame Animation](https://dl.acm.org/doi/10.1145/360349.360357) (1976).

## Datasets
- Nick Fox-Gieg - TiltSet: A Collection of 3D Drawings (2024). {[files](https://doi.org/10.20383/103.0917)}
- Nick Fox-Gieg - ABC-Draco: A GLTF Draco Conversion of the NYU ABC-Dataset (2024). {[files](https://doi.org/10.5683/SP3/QGGXYJ)}
- Laura Downs et al - [Google Scanned Objects: A High-Quality Dataset of 3D Scanned Household Items](https://arxiv.org/abs/2204.11918) (2022). {[files](https://app.gazebosim.org/GoogleResearch/fuel/collections/Scanned%20Objects%20by%20Google%20Research)}
- Ling Luo et al - [Fine-Grained VR Sketching: Dataset and Insights](https://www.computer.org/csdl/proceedings-article/3dv/2021/268800b003/1zWE3NZ5Apq) (2021). {[files](https://cvssp.org/data/VRChairSketch/)}
- Maria Shugrina et al - [Creative Flow+ Dataset](https://www.cs.toronto.edu/creativeflow/files/2596.pdf) (2019). {[files](https://www.cs.toronto.edu/creativeflow/)}
- Sebastian Koch et al - [ABC: A Big CAD Model Dataset for Geometric Deep Learning](https://arxiv.org/abs/1812.06216) (2019). {[files](https://deep-geometry.github.io/abc-dataset/)}


