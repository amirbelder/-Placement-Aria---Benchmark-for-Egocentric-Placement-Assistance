# Placement-Aria: A Benchmark for Egocentric Placement Assistance

Official repository for **Placement-Aria**, a benchmark for virtual object placement and placement assistance in egocentric environments.

The benchmark contains both **manually annotated scenes** and **automatically annotated scenes**, together with placement annotations for multiple placement tasks.

---

## Dataset Structure

The benchmark is divided into two annotation sources:

### 1. Manual Annotations

Manually annotated scenes contain human-verified placement annotations and are organized into:

* `train/`
* `validation/`
* `test/`

Each scene contains:

* Ground-truth placement annotations stored in folders whose names contain `GT`, such as:

  * `GT_PLACING`
  * `GT_SITTING`
  * `GT_TV`

For real scenes, the archive additionally contains:

* Semidense point annotations stored as `.npz` files.

For synthetic scenes, the archive additionally contains:

* Scene language descriptions stored as `.txt` files.

The complete manually annotated benchmark can be downloaded here:

[Manual Annotation Archive (manual_annotation_gt_only.tar.gz)](https://cgmdata.ece.technion.ac.il/public/data/amir/manual_annotation_gt_only.tar.gz?utm_source=chatgpt.com)

---

### 2. Automatic Annotations

Automatically generated annotations were created for a substantially larger collection of synthetic scenes.

The automatic benchmark consists of two archives:

#### Ground-Truth Placement Masks

Contains the placement annotations only:

* `GT_PLACING`
* `GT_SITTING`
* `GT_TV`

Download:

[Automatic GT Masks Archive (aria_placement_gt_masks.tar.gz)](https://cgmdata.ece.technion.ac.il/public/data/amir/aria_placement_gt_masks.tar.gz?utm_source=chatgpt.com)

#### Full Synthetic Scenes

Contains the corresponding full synthetic scene data, including:

* RGB images
* Depth maps
* Instance segmentations
* Semidense reconstructions
* Trajectories
* Scene metadata

Download:

[Synthetic Scene Archive (aria_synt_dataset.tar)](https://cgmdata.ece.technion.ac.il/public/data/amir/aria_synt_dataset.tar?utm_source=chatgpt.com)

---

## Citation

If you use Placement-Aria in your research, please cite the corresponding paper:

**Placement-Aria: A Benchmark for Egocentric Placement Assistance**

Citation information will be added upon publication.
