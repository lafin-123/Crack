# Crack

**The Crack dataset will be made publicly available after the associated paper is accepted for publication.** Download links, file descriptions, and citation information will be posted here when the dataset is released.

Crack is a collection of annotated 3D point clouds for point-level pavement crack segmentation. The data were collected by scanning real asphalt roads in two settings with different surface conditions and crack morphologies.

## Acquisition conditions

| Setting | Pavement and crack characteristics | 3D laser scanner | Nominal scanner accuracy |
| --- | --- | --- | --- |
| Campus roads at Chongqing Jiaotong University | Relatively flat asphalt surfaces with distinct boundaries around individual cracks. | KSCAN-Magic | 0.020 mm |
| Industrial-area roads in Chongqing | Asphalt roads used by heavy trucks, with greater surface wear, more exposed aggregate, and both individual and intersecting cracks. Some scans contain gaps. | Creaform HandySCAN 3D BLACK | 0.025 mm |

The accuracy values are scanner specifications. Actual point spacing and crack-depth measurement error depend on the scan and processing conditions.

## Point clouds and annotations

The scans cover each target crack and the surrounding pavement. The point clouds were cropped into samples and annotated at the point level. Each point is represented by its 3D coordinates and surface normal and is labeled as either **crack** or **background**.

The campus benchmark contains 114 cropped samples with 10,000 points per sample, derived from scans of 39 individual cracks. The industrial-road collection uses variable-size samples and includes both individual and intersecting cracks.

## 中文说明

**Crack 数据集将在相关论文录用后公开。** 正式发布时，本页将更新下载链接、文件说明和引用信息。

本数据集面向沥青路面裂缝的三维点云逐点分割。采集场景包括重庆交通大学校园沥青道路和重庆工业区重载沥青道路。校园道路表面相对平整，单条裂缝边界较清晰，使用 KSCAN-Magic 扫描。工业区道路长期承受重型货车荷载，路面磨损和骨料外露更明显，包含单条和交叉裂缝，使用 Creaform HandySCAN 3D BLACK 扫描。

数据包含裂缝及其周边路面的三维坐标、表面法向量和逐点类别标签，类别为裂缝和背景。校园道路的实验数据由 39 条裂缝的扫描点云裁剪整理得到，共 114 个样本，每个样本包含 10,000 个点。工业区道路的样本点数随扫描和裁剪范围而变化。
