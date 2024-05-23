${\LARGE\textsf{\color{red}Stay tuned: Releases and Source Code will be published on this repository soon!}}$


# BeamBCI
## The Berlin adaptable modular brain-computer interface software

Authors: Niels Peekhaus, Marius Nann, Elisa Brauße, Jan Zerfowski, Annalisa Colucci, Mareike Vermehren, Surjo R. Soekadar

Clinical Neurotechnology Laboratory, Department of Psychiatry and Neurosciences, Charité Campus Mitte (CCM), Charité – Universitätsmedizin Berlin, Germany

**Introduction**\
Brain-computer interfaces (BCIs) can translate brain activity into control signals of wearable actuators, such as exoskeletons, and enable the execution of movements despite impaired motor function, e.g., after stroke. Repeated use of such devices can trigger motor recovery even in chronic paralysis and thus makes BCI-driven treatments a promising tool for neurorehabilitation. However, any BCI experiment requires a technically demanding experimental setup and software capable of recording, processing, classifying, and translating brain activity into feedback in near real-time. While general-purpose BCI software exists (e.g., BCI2000), we focus on flexibility and accessibility to enable easy adaptation to a wide range of experimental setups and clinical applications.

**Objectives**\
With the BeamBCI software, we aim to facilitate research on BCIs by providing a streamlined data processing platform that serves as the foundation of various BCI applications while being flexible, accessible, and effective.

**Methods**\
The BeamBCI is a highly modular software that is built on standard tools for scientific programming: Python, Numpy, Scipy, and Labstreaminglayer (LSL). To set up an experiment, the user selects a set of modules for, e.g., data acquisition, signal classification, and control of an actuator. The modules interconnect automatically via LSL. All data recorded and generated during the experiment (e.g., raw, and processed brain signals, classification results, etc.) are available in the form of LSL streams which are automatically synchronized and stored along with all relevant settings and parameters. The processing is performed in near real-time, resulting in a processing delay of 5 to 10 ms.

**Results**\
The BeamBCI showed a stable performance during more than 300 sessions involving healthy participants, stroke survivors, and tetraplegics using a BCI to control a virtual actuator, motorized orthosis, or domestic appliances.

**Conclusion**\
The BeamBCI is a reliable and performant basis for various BCI experiments and greatly facilitates implementation, execution, and documentation of BCI studies.

