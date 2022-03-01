#  Preview: Vasculature CCF Visualization

HuBMAP Atlas Previews demonstrate functionality and resources that will become available in future releases. Previews may rely on externally hosted data or analysis results that were generated with processing pipelines that are not yet integrated into the HuBMAP Data Portal infrastructure.


### Description

This preview showcases a novel visualization in support of a vasculature-based common coordinate system (VCCF), [see paper](https://doi.org/10.3389/fcvm.2020.00029) on “Considerations for Using the Vasculature as a Coordinate System to Map All the Cells in the Human Body”.

Experimental data from the “Human Digital Twin: Automated Cell Type Distance Computation and 3D Atlas Construction in Multiplexed Skin Biopsies” paper, bioarxiv #, is used to compute distances of different cell types to the nearest blood vessel using 3D volumes of digital skin biopsy data generated using multiplexed imaging of sequential skin sections from younger and older patients (n=12; 22-72 years). Skin biopsies were collected from patients from different anatomical regions and different sun exposure effects (mild, moderate and marked). Samples underwent multiplexed imaging with 18 biomarkers covering nine cell types (epithelial, fibroblast, immune cells (macrophage, T-helper, T-killer, T-reg), endothelial, myoepithelial and nerve) markers of UV damage (p53, DDB2) and proliferation (Ki67). Following classification of cells into epithelial, endothelial, immune and markers of damage, the tissue data was reconstructed into 3D volumes. The reconstructed 3D cell data was used to compute distance distributions and network layouts of major immune cells to the nearest blood vessel in support of a vasculature based common coordinate framework and compared across age groups. Further, analysis of cell damage and proliferation markers (p53, Ki67 and DDB2) in the epithelial layer and their distance provided new insights into the effects of aging on skin.


### Atlas Details

Vascular pathways in human have been studied in much detail. Constructing a vasculature-based coordinate system (doi: 10.3389/fcvm.2020.00029) makes sense biologically as almost every living cell must be within a small distance to a blood vessel (100µm to 1mm, depending on the tissue) in order to receive oxygen. This Preview showcases a 3D interactive visualization of distances from cell nuclei of different cell types different cell types (T-regulatory, T-helper, and macrophages/CD68) to vasculature and skin surface tissue cells and compute violin plot comparisons across donor groups. 

The 3D visualization shows Region 5 for an UV exposed sample from the neck of a 33-year-old female (HuBMAP sample ID: HBM499.VJVR.265). Segmented blood vessels are rendered in red, T-regulatory cells in cyan, T-helper cells in blue, T-killer cells in dark red, and macrophages in yellow. The closest distance between an immune cell and a blood vessel is indicated by a gray line. The 3D visualization is interactive and available for all 10 tissue blocks used in the paper. Distance distributions for all three cell types are given below the 3D visualization.  


### Experimental Data Details

The experimental skin data used here is detailed in “Human Digital Twin: Automated Cell Type Distance Computation and 3D Atlas Construction in Multiplexed Skin Biopsies” **bioarxiv #.**

### Contributors
**Skin Data:** Soumya Ghose, Chrystal Chadwick, Elizabeth McDonough, Sanghee Cho, Johnhan Ho, Arivarasan Karunamurthy, Anup Sood, Yousef Al-Kofahi, Louis Falo & Fiona Ginty

**Vasculature CCF Visualization:** Yingnan Ju & Katy Börner


### Attribution

| Group  | Creater                          |
|--------|----------------------------------|
| RTI-GE | Fiona Ginty (fiona.ginty@ge.com) |
| MC-IU  | Katy Börner (katy@indiana.edu)   |


### Visualization

<div class="video-container">
    <iframe src="https://juyingnan.github.io/vccf_visualization.io/html/region_5.html" height="450" width="100%" allowfullscreen="" frameborder="0">
    </iframe>
</div>

<div class="video-container">
    <iframe src="https://juyingnan.github.io/vccf_visualization.io/html/violin_cell.html" height="450" width="100%" allowfullscreen="" frameborder="0">
    </iframe>
</div>

Try all the 10 skin samples [here](https://juyingnan.github.io/vccf_visualization.io).