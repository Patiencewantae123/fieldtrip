# FieldTrip

![FieldTrip Logo](https://www.example.com/logo.png)  
The MATLAB software toolbox for MEG and EEG analysis developed at the Donders Institute for Brain, Cognition, and Behaviour in Nijmegen, the Netherlands, along with collaborating institutes.

---

![Stars](https://img.shields.io/github/stars/fieldtrip/fieldtrip?style=social) ![Contributors](https://img.shields.io/github/contributors/fieldtrip/fieldtrip) ![License](https://img.shields.io/badge/License-GPLv3-blue.svg) ![Commit Activity](https://img.shields.io/github/commit-activity/m/fieldtrip/fieldtrip) ![Last Commit](https://img.shields.io/github/last-commit/fieldtrip/fieldtrip?style=plastic)

---

## **Features**

### Advanced Analysis Methods
- **Time-Frequency Analysis**
- **Source Reconstruction** (dipoles, distributed sources, beamformers)
- **Non-parametric Statistical Testing**

### Broad Compatibility
- **MEG Systems**: CTF, Neuromag/Elekta/Megin, BTi/4D, Yokogawa/Ricoh, FieldLine
- **EEG Systems**: Most popular systems supported

### Easy Extendability
- High-level functions for custom analysis protocols
- Seamless integration of new EEG/MEG analysis methods

For more details, visit our [official documentation](http://www.fieldtriptoolbox.org).

---

## **Installation**

Follow these steps to get started:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fieldtrip/fieldtrip.git
   ```
   Or [download the ZIP file](https://github.com/fieldtrip/fieldtrip/archive/refs/heads/master.zip).

2. **Set Up MATLAB**:
   - Add the directory to your MATLAB path.
   - Run:
     ```matlab
     ft_defaults
     ```

3. **Startup File**:
   Add the following to your `startup.m` file:
   ```matlab
   addpath('path/to/fieldtrip');
   ft_defaults;
   ```

> **Note**: Avoid `addpath(genpath(...))` or the "Add with subdirectories" option to prevent unwanted paths. The `ft_defaults` function manages dependencies.

---

## **Quick Links**

- **[Installation Guide](https://www.fieldtriptoolbox.org/faq/installation/)**
- **[Documentation](http://www.fieldtriptoolbox.org/documentation/)**
- **[Tutorials](http://www.fieldtriptoolbox.org/tutorial/)**
- **[FAQs](http://www.fieldtriptoolbox.org/faq/)**

---

## **Copyright**

FieldTrip is free software under the GNU General Public License v3. You are welcome to use, modify, and distribute it under the terms of this license. For details, see the [COPYING](https://www.gnu.org/licenses/gpl-3.0) file.

**Authors and Contributors**:
- Robert Oostenveld
- Jan-Mathijs Schoffelen
- Pascal Fries
- Eric Maris
- Arjen Stolk
- [Full list of contributors](https://github.com/fieldtrip/fieldtrip/graphs/contributors)

Institutions include:
- Donders Institute, Radboud University, Netherlands
- Karolinska Institute, Sweden
- Max Planck Institute for Psycholinguistics, Netherlands
- Wellcome Trust Centre for Neuroimaging, UK

---

## **Join the Community**

:rocket: **Contribute**: Fork us on [GitHub](https://github.com/fieldtrip/fieldtrip)!  
:mega: **Stay Updated**: Watch this repository for updates.  
:question: **Get Help**: Submit issues or browse the [FAQs](http://www.fieldtriptoolbox.org/faq/).

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=fieldtrip/fieldtrip&file=README.md)

