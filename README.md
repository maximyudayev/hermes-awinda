# HERMES - Awinda IMUs

Support package to interface the [Xsens Awinda](https://www.xsens.com/motion-capture/xsens-mvn-awinda) commercial IMUs in [HERMES](https://github.com/maximyudayev/hermes), to interfaces through the OEM provided PC SDK.

## Installation

### From PyPI
```bash
pip install pysio-hermes-awinda
```

### From source
```bash
git clone https://github.com/maximyudayev/hermes-awinda.git
pip install -e hermes-awinda
```

### Post-installation
After installing HERMES, follow [these instructions](https://wsdocs.movella.com/software-download) to download and install the prerequisite OEM SDK on your Windows/Linux device.

The package will be available under the same indexable HERMES namespace `hermes.awinda` upon installation, as `AwindaProducer`.

## Usage
Using the device follows the standard [configuration file specification](https://yudayev.com/hermes) process of HERMES nodes.

## Citation
When using any parts of this repository outside of its intended use, please cite the parent project [HERMES](https://github.com/maximyudayev/hermes).
