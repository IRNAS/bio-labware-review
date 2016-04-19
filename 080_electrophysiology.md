##Electrophysiology

###Table of contents

- [Overview](000_bio-labware_overview.md)
- [Wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
- [Spectroscopy](030_spectroscopy.md)
- [Chromatography (Separation)](040_chromatography_sep.md)
- [Chromatography (detection)](050_chromatography_det.md)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](070_cell_culture.md)
- [Electrophysiology](#ephys)
  * [simple measurement and control systems](#ephys-electrode)
  * [Patch clamping](#patch-clamp)
  * [Electroenchephalograms (EEGs) and brain computer interfaces (BCIs)](#EEG-BCI)
  * [Magnetic resonance imaging (MRI)](#MRI)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)


Electrophysiology is a general term for all methods, that are used for measuring electrical properties of cells, such as conductivity and the reaction and translation of electrical impulses. In recent years, with the rapid growth of Neuroscience, it is often associated with the measurement of neurons (nerve cells), their parts (such as ion channels) or larger neuronal systems. Electrophysiology more often than not takes place on animals or their (still functional) tissues. Such experimentation therefore always has to be considered from an ethical perspective, as already described in the chapter on [Cell culture](070_cell_culture.md).

---

###simple measurement and control systems <a id="ephys-electrode"></a>

![EKG](https://upload.wikimedia.org/wikipedia/commons/b/bd/12leadECG.jpg)

Source: By MoodyGroove - 2007-01-24 Public Domain, https://commons.wikimedia.org/w/index.php?curid=5266589

####1. Background
A simple electrophysiological setup can be imagined as a set of electrodes placed either on the surface or skewered into a piece of tissue. On one electrode a simple pulse is produced, which is measured (if possible) on the other electrode. Depending on the tissue the resulting signal can vary in form, produce movement (muscles tissue) and the speed of translation. Many other experiments are also possible. In neurons for example, spontaneous firing activity can be measured or in combination with sensory organs and their stimulation.

Keywords: electrophysiology, electrodes, action, potential, spike

####2. Commercial variants
For general electrophysiological experiments one typically requires a set of electrodes (basically needles), a signal generator and an oscilloscope. These devices have a broad price range (usually several hundred €), since they can be standalone devices, or need to be coupled with PCs or nowadays smartphones. A modern example, with a broader functionality is the [red pitaya](http://redpitaya.com/).

####3. Available DIY resources
In the DIY compartment, there are also a few very well developed designs for this purpose. The one most focused on electrophysiology is the [Spikerbox](https://backyardbrains.com/products/spikerbox) from Backyard Brains, which is suitable for educational purposes and basic neurophysiolgy experiments. It also allows signal recordings via smartphone. More advanced designs, suitable for more research and medical monitoring are the [Bitalino](http://bitalino.com/index.php/hardware) and the [e-health biometric sensor](https://www.cooking-hacks.com/documentation/tutorials/ehealth-biometric-sensor-platform-arduino-raspberry-pi-medical).

####4. Is DIY good enough and reasonable?
Electrophysiology has always been and remains DIY to some extent, as every experiment requires a somewhat different set-up. The measurement and signal generating circuits are also becoming more available and are now compatible with most "smart" home electronics. In any case, the available DIY circuits seem well suitable for handling the these kind of experiments.

####5. Requirements and plans
The setup typically requires a method of measuring signals, which is accomplished by electrodes made from stainless stell or silver chloride, but in principle, any conductive noncorrosive material will do. In addition, some method of signal generation and measurement is required, with appropriate resolution. For the precise measurement of action potentials, microsecond resolution is convenient.


---


###Patch clamping <a id="patch-clamp"></a>

![wholecellpatchclamp-03](https://cloud.githubusercontent.com/assets/17159617/14496918/34b87128-0195-11e6-9e7e-183a9aa7b354.jpg)

Source: By derivative work: Rosentod (talk) WholeCellPatchClamp.jpg: レイキャビク 22:10, 6 April 2007 Public Domain, https://commons.wikimedia.org/w/index.php?curid=4830144

####1. Background
Patch clamping is a method in electrophysiology which allows the measurement of single cells or even their parts, like ion channels. To achieve this, extremely fine, hollow, glass pipettes - filled with electrolyte and an electrode are brought in contact with a cell, which is either penetrated, or small piece of membrane removed. This way cell/channel responses to electrical stimulation, substance addition/removal/etc. can be measured. This method allows extraordinary precision in cell measurement, not only from a electrophysiological prespective, but a molecular one as well.

Keywords: patch, clamp, ion, channel, glass, pipette

####2. Commercial variants
the glass pipettes used for patch clamping need to be prepared right before the measurement, since their tips could not survive any form of longterm storage or transport. Thin glass cylinders are heated in the middle and then stretched with a defined force to achieve the appropriate form. This is done by an electrode puller.

To actually make suitable contact with a cell, a few conditions have to be met. First, one requires an optical microscope with adequate optics for focusing in thick samples and the pipette (wide depth of field). Second, one requires a micromanipulator, to finely control the position of the patch clamp pipette. To assure the tissue is not accidentaly damaged in the process, the set-up needs to be built on a vibration reducing air table. 

The signals from single cells or even smaller samples are extremenly weak and can be lost in any ambient noise. Therefore the a faraday cage needs to be built around the set-up and the experimenter needs to be grounded as well. In addition, the signals need to be amplified.

Due to the complexity and many contained components, complete systems cost several 10 thousand €, usually 50-70k€. However, combining the single components alone may reduce costs drastically, making some of them DIY possibly even more. A price calculator for patch-clamp systems can be found [here](http://www.autom8.com/rig/
).

####3. Available DIY resources
Due to it's popularity for electrophysiological, neuro- and molecular Biology research, patch clamping has recieved much attention. There are quite a few different approaches to make the system cheaper and more compact. A good example is the [Autopatcher](http://autopatcher.org/), an automated patch-clamping robot. Also completely different methods were shown to work, which simplify the system even more. Examples of this are the [Patch-clamp on a chip](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2978236/) or the [Microfluidic patch-clamp](http://pubs.rsc.org/en/Content/ArticleLanding/2006/LC/b608439g#!divAbstract).

####4. Is DIY good enough and reasonable?
From shown data, the presented DIY patch-clamps seem well suitable even for professional lab work, considering measurement performance. Possibly it is not as versatile as a classical system, but the new devices present a huge step forward not only for DIY Biology, but for patch-clamp technology itself.

####5. Requirements and plans
The requirements for patch-clamp systems are bound by the criteria described above. The purpose of this technology is the measurement and manipulation of single cells and parts of their membrane and produce clear signals.


---


###Electroenchephalograms (EEGs) and brain computer interfaces (BCIs)<a id="EEG-BCI"></a>

![cognigame](https://www.festo.com/group/de/repo/assets/00361-cognigame-1532x900px.jpg)

Source: https://www.festo.com/group/de/cms/10234.htm

####1. Background
Electroencephalography (EEG) is a typically noninvasive method of monitoring brain activity. Usually, several electrodes are brought in conjuncture with the scalp and their signals are recoreded. As the electrodes a re typically much larger than the neurons, the recordings are representations of cumulative activity of several cells. As a result, so called brain waves are observed instead of simple action potentials. 

Electroencephalography is a popular clinical monitoring method, especially for patients experiencing seizures. In addition, EEG is a usefull research tool for studying how the brain works and the most common noninvasive method for brain-computer interface (BCI) experiments. The purpose of the latter is using brain signals to interact and control electronic devices.

Keywords: eeg, bci, noninvasive, brain, monitoring

####2. Commercial variants
Research grade digital EEGs normally cost 4000€ and up, even if used. Due to the general popularity of this technology in recent years, however, a few small companies ([NeuroSky](http://neurosky.com/), [Emotiv](https://emotiv.com/), etc.) have begun producing cheap EEG devices for the everyday user, which are available for a few hundred €. These, however, seem to be more suitable for fun and education, than serious brain activity monitoring. It is possible that this is due to software, rather than hardware limitations, as the electrodes are fairly simple in their compositions.

####3. Available DIY resources
For DIY EEG an open source project exists, where data on construction for all required component was collected - [OpenEEG](http://openeeg.sourceforge.net/doc/index.html). To make the technology more accessible and compatible with modern smartphones, a paper on he construction of such a device was published in PLOS: [The Smartphone Brain Scanner](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0086733). Finally, there is also the [OpenBCI](http://openbci.com/) project which uses 3Dprintable parts and was funded by a kickstarter campaign. 

####4. Is DIY good enough and reasonable?
It is hard do comment on the performance of the DIY designs, since little data is availale. The characteristics on the other hand, seem to be sufficient for measurement.

####5. Requirements and plans
Electroencephalographs in principle have simple requirements. The electrodes need to be sensitive enough to externally measure brain activity without being too susceptive to noise. Each electrode should then be monitored in its own channel such that they can all be compared to each other. Resolutionwise the basic brain-waves should be distinguishable (alpha: 8-15Hz, beta: 16-31Hz, gamma: >32Hz, delta: 4Hz (or less), theta: 4-7Hz).

---

###Magnetic resonance imaging (MRI) <a id="MRI"></a>

![mri](https://upload.wikimedia.org/wikipedia/commons/8/85/Bluthirnschranke_nach_Infarkt_nativ_und_KM.png)

Source: By Hellerhoff - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=10323803

####1. Background
Magnetic resonance imaging or MRI is an analytical method for determining structural properties of biological materials. The magnetic dipole moment or 'spin' of hidrogen protons in water, that is usually very variable is aligned in a strong magnetic field and relaxed. The protons can then be visualized by pulsed radio waves which they absorb and emit their own. Creating gradients in the magnetic field, the position of each proton can be determined and depending on the density of these protons, the tissue can appear differently bright. Usually hidrogen protons are measured, but other elements are also possible. A great source of information on magnetic resonance and imaging is Peter Jansen's application for a [low-field MRI concept](https://hackaday.io/project/5030-low-field-mri/log/15914-concept)..

Keywords: magnetic, resonance, imaging, MRI

####2. Commercial variants
Depending on the strength of their magnetic field, MRI devices have different prices, but most of them are in the range of hundreds of thousand €.

####3. Available DIY resources
Many attempts have been made, to create DIY magnetic resonance systems, such as the [Open core](http://kuchem.kyoto-u.ac.jp/bun/indiv/takezo/opencorenmr2/index.html) or the Conspiracy of light [Home built NMR spectrometer](http://www.conspiracyoflight.com/NMR/NMR.html). Apparently, inducing and measuring nuclear magnetic resonance is very doable in DIY, actual imaging, however, seems to be another matter. One attempt was made by [Peter Jansen](http://www.tricorderproject.org/blog/) - the [low-field MRI](https://hackaday.io/project/5030-low-field-mri). Possibly the first successful prototype of an [affordable DIY MRI](http://www.popsci.com/technology/article/2010-10/diy-mri-shows-how-we-really-breathe) with sufficient imaging capabilities was build at Harvard University by Matthew Rosen, for lung analysis.

####4. Is DIY good enough and reasonable?
Momentarily, DIY MRI devices are far from good enough, however big steps have been taken in the right direction, paving the way for future designs.

####5. Requirements and plans
The requirements on an MRI device are, though vastly complex in practice, relatively simple in theory. The hydrogen protons in a body should be detected, localized and differentiated from its neighbouring ones by its magnetic dipole moment. Ideally, the resolution would be high enough to identify each and every proton, however in practice, this is difficult and for simple measurements, even rough imaging would be gladly accepted in a DIY device.
