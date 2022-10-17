# Lung mask

Automated lung segmentation in CT under presence of severe pathologies.

Run this model in [Google CoLab](https://colab.research.google.com/drive/1IrIIYVHIuq2oD6gXGNAuAqsYF9TcuhTy).

## meta

|                  |                                      |
| ---------------- |--------------------------------------|
| application_area | U-net                                |
| task             | Segmentation                         |
| task_extended    | U-net lung segmentation              |
| code source      | https://github.com/JoHof/lungmask    |
| data_type        | Image/CT scan                        |


## publication

|                |                                                    |
| -------------- | ----------------------------------------------------- |
| title          | Automatic lung segmentation in routine imaging is primarily a data diversity problem, not a methodology problem |
| source         | European Radiology Experimental |
| url            | https://doi.org/10.1186/s41747-020-00173-2 |
| year           | 2020 |
| authors        | Hofmanninger, J., Prayer, F., Pan, J., Röhrich, S., Prosch, H., & Langs, G. |
| abstract       | Background: Automated segmentation of anatomical structures is a crucial step in image analysis. For lung segmentation in computed tomography, a variety of approaches exists, involving sophisticated pipelines trained and validated on different datasets. However, the clinical applicability of these approaches across diseases remains limited. Methods: We compared four generic deep learning approaches trained on various datasets and two readily available lung segmentation algorithms. We performed evaluation on routine imaging data with more than six different disease patterns and three published data sets. Results: Using different deep learning approaches, mean Dice similarity coefficients (DSCs) on test datasets varied not over 0.02. When trained on a diverse routine dataset (n = 36), a standard approach (U-net) yields a higher DSC (0.97 ± 0.05) compared to training on public datasets such as the Lung Tissue Research Consortium (0.94 ± 0.13, p = 0.024) or Anatomy 3 (0.92 ± 0.15, p = 0.001). Trained on routine data (n = 231) covering multiple diseases, U-net compared to reference methods yields a DSC of 0.98 ± 0.03 versus 0.94 ± 0.12 (p = 0.024). Conclusions: The accuracy and reliability of lung segmentation algorithms on demanding cases primarily relies on the diversity of the training data, highlighting the importance of data diversity compared to model choice. Efforts in developing new datasets and providing trained models to the public are critical. By releasing the trained model under General Public License 3.0, we aim to foster research on lung diseases by providing a readily available tool for segmentation of pathological lungs. |
| google_scholar | https://scholar.google.com/scholar?cites=70004818277158591&as_sdt=40000005&sciodt=0,22&hl=en|
| bibtex         | @article{hofmanninger2020automatic, title={Automatic lung segmentation in routine imaging is primarily a data diversity problem, not a methodology problem}, author={Hofmanninger, Johannes and Prayer, Forian and Pan, Jeanny and R{\"o}hrich, Sebastian and Prosch, Helmut and Langs, Georg}, journal={European Radiology Experimental}, volume={4}, number={1}, pages={1--13}, year={2020}, publisher={SpringerOpen}}|
