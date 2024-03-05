<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">FASTSAM3D-V1</h1>
</p>
<p align="center">
    <em><code>► INSERT-TEXT-HERE</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/skill-diver/FastSAM3D-v1?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/skill-diver/FastSAM3D-v1?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/skill-diver/FastSAM3D-v1?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/skill-diver/FastSAM3D-v1?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

<code>► INSERT-TEXT-HERE</code>

---

##  Features

<code>► INSERT-TEXT-HERE</code>

---

##  Repository Structure

```sh
└── FastSAM3D-v1/
    ├── =0.2.25
    ├── LICENSE
    ├── distillation.py
    ├── distillation.sh
    ├── infer.sh
    ├── infer_med2d.sh
    ├── infer_sam.sh
    ├── prepare_label.sh
    ├── preparelabel.py
    ├── preparelabel1.py
    ├── requirements.txt
    ├── segment_anything
    │   ├── Dockerfile
    │   ├── __init__.py
    │   ├── automatic_mask_generator.py
    │   ├── build_ls_sam3d.py
    │   ├── build_sam.py
    │   ├── build_sam3D.py
    │   ├── build_sam3D_decoder.py
    │   ├── build_sam3D_dilatedattention.py
    │   ├── build_sam3D_flash.py
    │   ├── modeling
    │   ├── predictor.py
    │   └── utils
    ├── sum_result.py
    ├── train.py
    ├── train.sh
    ├── train_unfreeze.py
    ├── train_unfreeze.sh
    ├── utils
    │   ├── click_method.py
    │   ├── data_loader.py
    │   ├── data_paths.py
    │   └── prepare_uunet.py
    ├── val_2d.py
    ├── validation.py
    └── validation_student.py
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                                                   | Summary                         |
| ---                                                                                                    | ---                             |
| [distillation.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/distillation.sh)             | <code>► INSERT-TEXT-HERE</code> |
| [sum_result.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/sum_result.py)                 | <code>► INSERT-TEXT-HERE</code> |
| [train.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/train.py)                           | <code>► INSERT-TEXT-HERE</code> |
| [infer_med2d.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/infer_med2d.sh)               | <code>► INSERT-TEXT-HERE</code> |
| [requirements.txt](https://github.com/skill-diver/FastSAM3D-v1/blob/master/requirements.txt)           | <code>► INSERT-TEXT-HERE</code> |
| [infer_sam.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/infer_sam.sh)                   | <code>► INSERT-TEXT-HERE</code> |
| [prepare_label.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/prepare_label.sh)           | <code>► INSERT-TEXT-HERE</code> |
| [validation_student.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/validation_student.py) | <code>► INSERT-TEXT-HERE</code> |
| [preparelabel.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/preparelabel.py)             | <code>► INSERT-TEXT-HERE</code> |
| [val_2d.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/val_2d.py)                         | <code>► INSERT-TEXT-HERE</code> |
| [train_unfreeze.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/train_unfreeze.sh)         | <code>► INSERT-TEXT-HERE</code> |
| [train_unfreeze.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/train_unfreeze.py)         | <code>► INSERT-TEXT-HERE</code> |
| [validation.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/validation.py)                 | <code>► INSERT-TEXT-HERE</code> |
| [=0.2.25](https://github.com/skill-diver/FastSAM3D-v1/blob/master/=0.2.25)                             | <code>► INSERT-TEXT-HERE</code> |
| [distillation.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/distillation.py)             | <code>► INSERT-TEXT-HERE</code> |
| [preparelabel1.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/preparelabel1.py)           | <code>► INSERT-TEXT-HERE</code> |
| [train.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/train.sh)                           | <code>► INSERT-TEXT-HERE</code> |
| [infer.sh](https://github.com/skill-diver/FastSAM3D-v1/blob/master/infer.sh)                           | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>utils</summary>

| File                                                                                               | Summary                         |
| ---                                                                                                | ---                             |
| [data_loader.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/utils/data_loader.py)     | <code>► INSERT-TEXT-HERE</code> |
| [prepare_uunet.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/utils/prepare_uunet.py) | <code>► INSERT-TEXT-HERE</code> |
| [click_method.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/utils/click_method.py)   | <code>► INSERT-TEXT-HERE</code> |
| [data_paths.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/utils/data_paths.py)       | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>segment_anything</summary>

| File                                                                                                                                        | Summary                         |
| ---                                                                                                                                         | ---                             |
| [automatic_mask_generator.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/automatic_mask_generator.py)         | <code>► INSERT-TEXT-HERE</code> |
| [build_sam.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_sam.py)                                       | <code>► INSERT-TEXT-HERE</code> |
| [build_sam3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_sam3D.py)                                   | <code>► INSERT-TEXT-HERE</code> |
| [predictor.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/predictor.py)                                       | <code>► INSERT-TEXT-HERE</code> |
| [Dockerfile](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/Dockerfile)                                           | <code>► INSERT-TEXT-HERE</code> |
| [build_sam3D_flash.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_sam3D_flash.py)                       | <code>► INSERT-TEXT-HERE</code> |
| [build_sam3D_decoder.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_sam3D_decoder.py)                   | <code>► INSERT-TEXT-HERE</code> |
| [build_sam3D_dilatedattention.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_sam3D_dilatedattention.py) | <code>► INSERT-TEXT-HERE</code> |
| [build_ls_sam3d.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/build_ls_sam3d.py)                             | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>segment_anything.utils</summary>

| File                                                                                                              | Summary                         |
| ---                                                                                                               | ---                             |
| [transforms.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/transforms.py)     | <code>► INSERT-TEXT-HERE</code> |
| [amg.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/amg.py)                   | <code>► INSERT-TEXT-HERE</code> |
| [transforms3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/transforms3D.py) | <code>► INSERT-TEXT-HERE</code> |
| [onnx.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/onnx.py)                 | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>segment_anything.utils.natten</summary>

| File                                                                                                                 | Summary                         |
| ---                                                                                                                  | ---                             |
| [nested.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/nested.py)         | <code>► INSERT-TEXT-HERE</code> |
| [natten1d.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/natten1d.py)     | <code>► INSERT-TEXT-HERE</code> |
| [natten2d.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/natten2d.py)     | <code>► INSERT-TEXT-HERE</code> |
| [functional.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/functional.py) | <code>► INSERT-TEXT-HERE</code> |
| [flops.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/flops.py)           | <code>► INSERT-TEXT-HERE</code> |
| [natten3d.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/natten3d.py)     | <code>► INSERT-TEXT-HERE</code> |
| [ops.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/ops.py)               | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>segment_anything.utils.natten.utils</summary>

| File                                                                                                                 | Summary                         |
| ---                                                                                                                  | ---                             |
| [typing.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/utils/typing.py)   | <code>► INSERT-TEXT-HERE</code> |
| [testing.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/utils/testing.py) | <code>► INSERT-TEXT-HERE</code> |
| [tensor.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/utils/natten/utils/tensor.py)   | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>segment_anything.modeling</summary>

| File                                                                                                                                                         | Summary                         |
| ---                                                                                                                                                          | ---                             |
| [dilated_utils.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/dilated_utils.py)                                       | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder.py)                                       | <code>► INSERT-TEXT-HERE</code> |
| [mask_decoder3D_flash.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/mask_decoder3D_flash.py)                         | <code>► INSERT-TEXT-HERE</code> |
| [mask_decoder.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/mask_decoder.py)                                         | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder3D_c.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder3D_c.py)                               | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder3D_flash.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder3D_flash.py)                       | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder_justdilated.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder_justdilated.py)               | <code>► INSERT-TEXT-HERE</code> |
| [mask_decoder3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/mask_decoder3D.py)                                     | <code>► INSERT-TEXT-HERE</code> |
| [sam.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/sam.py)                                                           | <code>► INSERT-TEXT-HERE</code> |
| [flash_attention.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/flash_attention.py)                                   | <code>► INSERT-TEXT-HERE</code> |
| [transformer.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/transformer.py)                                           | <code>► INSERT-TEXT-HERE</code> |
| [utils.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/utils.py)                                                       | <code>► INSERT-TEXT-HERE</code> |
| [prompt_encoder.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/prompt_encoder.py)                                     | <code>► INSERT-TEXT-HERE</code> |
| [sam3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/sam3D.py)                                                       | <code>► INSERT-TEXT-HERE</code> |
| [prompt_encoder3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/prompt_encoder3D.py)                                 | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder3D_dilated.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder3D_dilated.py)                   | <code>► INSERT-TEXT-HERE</code> |
| [sam_model.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/sam_model.py)                                               | <code>► INSERT-TEXT-HERE</code> |
| [common.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/common.py)                                                     | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder3D.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder3D.py)                                   | <code>► INSERT-TEXT-HERE</code> |
| [image_encoder3D_dilatedattention.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/image_encoder3D_dilatedattention.py) | <code>► INSERT-TEXT-HERE</code> |
| [xpos_relative_position.py](https://github.com/skill-diver/FastSAM3D-v1/blob/master/segment_anything/modeling/xpos_relative_position.py)                     | <code>► INSERT-TEXT-HERE</code> |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the FastSAM3D-v1 repository:
>
> ```console
> $ git clone https://github.com/skill-diver/FastSAM3D-v1
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd FastSAM3D-v1
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run FastSAM3D-v1 using the command below:
> ```console
> $ python main.py
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/skill-diver/FastSAM3D-v1/issues)**: Submit bugs found or log feature requests for the `FastSAM3D-v1` project.
- **[Submit Pull Requests](https://github.com/skill-diver/FastSAM3D-v1/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/skill-diver/FastSAM3D-v1/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/skill-diver/FastSAM3D-v1
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/skill-diver/FastSAM3D-v1/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=skill-diver/FastSAM3D-v1">
   </a>
</p>
</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
