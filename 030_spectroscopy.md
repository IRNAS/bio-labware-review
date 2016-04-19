##Spectroscopy <a id="Spectroscopy"></a>

###Table of contents
- [Overview](000_bio-labware_overview.md)
- [General/wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
- [Spectroscopy](030_spectroscopy.md)
  * [Cell optical density meter](030_spectroscopy.md#OD600)
  * [UV-Vis spectroscope](030_spectroscopy.md#UV-Vis-spect)
  * [IR spectroscope](030_spectroscopy.md#IR-spect)
  * [Fluorescence spectroscope](030_spectroscopy.md#Fluo-spect)
  * [Raman spectroscope](030_spectroscopy.md#raman)
- [Chromatography (separation)](040_chromatography_sep.md)
- [Chromatography (detection)](050_chromatography_det.md)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](070_cell_culture.md)
- [Electrophysiology](080_electrophysiology.md)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)

###Introduction
Spectroscopy is the study of material interaction with waves, which produces specific spectra, that can be detected and analyzed. Typically, spectroscopy is associated with the interaction of matter with electromagnetic radiation, which is either absorbed, reflected or emitted and creates a specific pattern in the spectrum. Measuring the resulting wavelengths and intensity, is what we call spectrophotometry. Since the detected beam of radiation usually contains many different wavelenghts, these are often separated before detection, by means of diffraction (gratings), refraction (optical prisms),...

Spectroscopy is a very broad field of study and includes many disciplines and techniques, which can be classified by either the type of energy, type of interaction, materials, etc. In biology itself, many techniques are used, we will, however, only be discussing a few most commonly used ones.

---

###Cell optical density meter (OD600 meter)<a id="OD600"></a>

####1. Background
A very basic form of spectroscopy, optical density meters measure the light transmittance/absorbance of a sample. Absorbance at 600nm through liquid cell cultures is used to estimate the growth phase of a cell culture. This is extremely useful for cell culture and transformation protocols where using cells in the log growth phase will give better results. Standard 10mm optical cuvettes are used to contain the sample during measurement. 

Keywords: optical density, OD600, turbidity, absorbance, 600nm, cell density

####2. Commercial variants
UV-vis spectroscopes (see [below](#UV-Vis-spect)) are capable of making cell culture density measurements and are often used for this. Cheaper devices that only measure at the 600nm wavelength (only useful for measuring cell culture density), are available and cost around €800.

####3. Available DIY resources
Many of the [DIY UV-vis spectroscopes listed below](#UV-Vis-spect) can be adapted to be capable of reliably measuring 600nm absorbance of cell cultures in 10mm cuvettes, however the [OD/F device](http://2014.igem.org/Team:Aachen/OD/F_device) and [DIλ](http://www.openscienceschool.com/di-lambda/) are built specifically for measuring cell densities and can be built for around €40.

An extremely cheap alternative is to make up a set of [McFarland Turbidity Standards](https://en.wikipedia.org/wiki/McFarland_standards) using barium chloride and sulphuric acid. These can be visually compared to the sample cell suspension to roughly estimate its optical density and thus rough growth phase of the culture. 

####4. Is DIY good enough and reasonable?
The McFarland Turbidity Standards are extremely cheap and easy to make. Although the estimates given by using this method are extremely rough, it is still much better than using timing alone to guess cell density for protocols which require specific growth phase cell. This is recommended for one-offs and DIY labs without any optical density meter or UV-Vis spectroscope.

The affordability and easy construction of reliable and calibratable DIY optical density meters should mean the DIY options are easy for most DIY labs to build and use if they are unable to obtain a commercial unit.

####5. Requirements and plan
The important part of a cell optical density meter is a secure housing for the cuvette and a calibrated light source which emits close to 600nm. This allows calibration to an absolute optical density scale rather than simply giving relative readings. The DIY options listed have been tested and successfully calibrated to give reliable optical density readings in their documentation. Adaptation of existing DIY UV-Vis spectroscopes should be very possible, but proper calibration will be a crucial part of this. 

---

###UV-Vis spectroscope <a id="UV-Vis-spect"></a>

![uv-vis-spectro](https://cloud.githubusercontent.com/assets/17159617/13486725/bd0a48fa-e113-11e5-9e88-2c042e18f6c1.png)

Source: http://www.the-scientist.com/?articles.view/articleNo/18797/title/Across-the-Spectrum--Instrumentation-for-UV-Vis-Spectrophotometry/

####1. Background
Historically the oldest forms of spectroscopy were perfomed with visible light and in principle, that is what we do with our eyes naturally. We could even go so far and trace it back to the first photoreceptors of simple organisms. In research terms, we refer visible light spectroscopy with reflectance or absorbance of light in the visible spectrum. More often than not, in combination with the ultraviolet (UV) spectrum. A beam of light is projected throguh a sample (mostly solutions, but also solids and gases), a diffraction grating (sometimes before a sample) and the resulting spectrum is analyzed. For some applications, only certaing wavelenghts are interesting, which can be preset in the photometer. To obtain meaningful results, it is important, that the device is properly calibrated and the samples are compared with adequate reference samples (negative/positive controls, etc.). 

UV-Vis spectrometers are most often used for quantitative determination of various substances, such as organic compounds, biological macromolecules, metalic ions, etc. According to the Beer-Lambert law, the absorbance of a solution for example, is directly proportional with the concentration of the absorbing molecule in the solution.

Keywords: spectroscopy, spectrometry, spectrophotometry, ultra violet, UV, visible, light

####2. Commercial variants
The cheapest, used devices, can be obtained for a few hundred €, while completely new equipment is sold for a few thousand €. Most devices have a spectral range from 200 to 1000nm, which includes the UV spectrum, the complete visible spectrum and a very short band of the near infrared (IR) spectrum. The key to a good spectrometer is a reliable and even wavelength intensity distribution over its spectrum, which should be as wide as possible. The grating in combination with the detector, should in addition allow a good resolution, at least in the 1-10nm scale (many, especially commercial ones are much better however). For applications, where only a short band of wavelength is used, every sample is compared with references and should (according to Beer and Lambert) yield a linear correlation (with a constant slope, regardless of how steep the slope actually is) between sample concentration and light absorption.

####3. Available DIY resources
Open source spectrometers sem fairly developed, especially for the visible light spectrum. There are currently two projects, which offer kits for sale. One is the [Public lab spectrometer](https://publiclab.org/wiki/desktop-spectrometry-kit-3-0) with its 3rd version, available for 45$ and with a spectral range of 390-900nm and a resolution smaller than 3nm. It offers free software for all platforms and a web-based app for analysis. The other one is the arduino based [Myspectral spectrometer](http://myspectral.com/index.html), which is more compact and robust in design, but is also substantially more costly, for 300-500€ with a 9nm resolution. It has a spectral range of 380-750nm. In addition to these, there are also other great DIY projects, such as the [3D printable mini spectrometer](http://www.tricorderproject.org/blog/sneak-peek-3d-printable-mini-spectrometer/) with a range from 400-700nm and a 2-4nm resolution, and the [creative technology spectrometer](http://www.creative-technology.net/MAKE.html) which can identify a few substances, based on their spectrum. Another design was published in the [Journal of chemical education](http://hackteria.org/wiki/images/e/ec/Inexpensive_spectrometer_2013.pdf), which has the full visible spectrum and a resolution below 1nm.

####4. Is DIY good enough and reasonable?
THe existing open spectrometers offer a reasonable light spectrum with a reasonable resolution. Due to the built-in camera filters for UV and IR, which most devices use, the spectrum is limited to visible light. That however, partially for an outstanding price, even for kits with additional software and service, such as the Public lab spectrometer.

####5. Requirements and plans
As mentioned above, the evaluation criteria for a good spectrometer are: its spectral bandwidth (200-1000nm would be optimal), with an even intensity distribution of the light source and a high spectral resolution (optimal 1-5nm). While the last two are already good enough in existing DIY projects, widening the spectrum would be a great goal for future development.

---

###IR spectroscope <a id="IR-spect"></a>

![dichloromethane_near_ir_spectrum](https://cloud.githubusercontent.com/assets/17159617/13486867/15726aa8-e115-11e5-9eac-21eb59cf24bc.png)

Source: https://commons.wikimedia.org/wiki/File:Dichloromethane_near_IR_spectrum.png

####1. Background
Similar to UV-Vis, IR spectroscopy is also mostly based on absorbance (but also transmittance) spectra of materials, but in a different part of the electro magnetic spectrum. We distinguish 3 parts of the IR spectrum, depending on how far away they are from the visible spectrum: 
- near IR (or NIR, 0.8-2.5μm) - harmonic frequencies
- mid IR (or MIR, 2.5-25μm) - rotational-vibrational frequencies
- far IR (or FIR, 25-1000μm) - vibrational frequencies

While IR light is invisible to the eye, most molecules absorb and resonate to some part of it, creating a very specific "fingerprint" in the transmitted light. IR spectroscopy is therefore very usefull for chemical identification. The IR transmission spectrum is often analyzed using Fourier transformation (FT), to find the basic frequencies. Devices which are capable of this function are called Fourier transform infrared spectromerters or FTIRs.

Keywords: infrared, near, mid, far, resonance, spectroscopy, fourier, transform

####2. Commercial variants
Commercial IR spectrometers cost several thousand €, even the second hand ones. They are usually restricted to a part of the spectrum (which is still wide, compared to visible light), therefore, there are no devices, which could measure the full IR width. As many devices also perform a fourier transform, they contain a complex set of optics - beam splitters, mirrors, interferometers, etc. in addition to the standard parts, also seen in the UV-Vis detectors.
An interesting device is the kickstarter funded [Scio](https://www.kickstarter.com/projects/903107259/scio-your-sixth-sense-a-pocket-molecular-sensor-fo/description) - a pocket sized NIR spectrometer. It is low cost, very compact and supposedly capable of identifying many organic substances, the IR light of which is reflected off the surface. Due to the size and known characteristics of professional devices, which are required for high quality detection, its performance is, however, questionable.

####3. Available DIY resources
There aren't many, well documented, or simple to to reconstruct DIY IR spectrometers out there at the moment. There is one project, describing the construction of a [NIR based brainactivity monitor](http://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/s2012/pmd68_mab448/pmd68_mab448/index.html), which is based on a [paper](http://iopscience.iop.org/article/10.1088/1741-2560/4/3/007/meta;jsessionid=D6E3E82545F7D227F102B00DC810C58E.c4.iopscience.cld.iop.org) published in the Journal of Neural Engineering. Another project describes the optics, for a functioning [Fourier transform system](https://translate.google.com/translate?hl=en&sl=ru&tl=en&u=http%3A%2F%2Fhabrahabr.ru%2Fpost%2F253947%2F). The source material is written in Russian, and the translation is very poor (If you have a better translation, please let us know!). Finally, there is one well documented project on github, describing the construction of an [FTIR spectrometer](https://github.com/Bioreactor/FTIR-Spectro), which can be built for about 1000€. Unfortunatelly, the performance of this device is unknown.

####4. Is DIY good enough and reasonable?
Due to a very small amount of available information about the specifications, the existing projects cannot be evaluated very well at this point. They do, however, create a good starting point for further development.

####5. Requirements and plans
What device to build, depends on the experimental reqirements one has. A great comparison of NIR and MIR devices can be found [here](http://www.spectroscopyonline.com/nir-versus-mid-ir-how-choose). In short, NIR, especially reflection spectra, are more widely used today, they are generally cheaper and allow the analysis of samples in water and glass containers, which are mostly transparent to the spectrum. Also, highly sensitive detectors are more common for this part of the spectrum. On the other hand, NIR spectra often show the overtones of MIR vibrations (which contain more information about the composition) and are often weak and poorly delineated, which makes MIR the better choice for more detailed and precise analyses. For DIY applications, a NIR spectrometer should be simpler to build, while still good enough for basic material analysis.


---


###Fluorescence spectroscope <a id="Fluo-spect"></a>

![maxresdefault](https://cloud.githubusercontent.com/assets/17159617/13486910/9ad43ae6-e115-11e5-91ec-2c919192a6f6.jpg)

Source: http://www.psfk.com/2014/10/public-lab-store-spectrophotometry.html

####1. Background
Instead of exploiting absorbed/transmitted or reflected light, as described above, fluorescence spectroscopy analyses the EMITTED light from matter, which has beforehand absorbed other light, as described by [A. Jablonski](http://www.nature.com/nature/journal/v131/n3319/pdf/131839b0.pdf) in 1933. Fluorescent spectroscopy is perhaps most widely used in biochemistry or medicine, for the analysis and tracking of cells or organic compounds. It can also be adapted to the microscopic level (see [Fluorescence microscopy](#Fluorescence-microscope)).

Keywords: fluorescence, spectrometry, fluorometry, jablonski, diagram

####2. Commercial variants
New fluorometers can be obtained for a few thousand €, used devices come for a few hundred. In principle the construction is similar to UV-Vis devices, however, the transmitted light is ignored and only fluorescent light is measured. For this use, it is better the exciting light have a very narrow spectrum, adjusted for the samples. This could be achieved either by using diodes or monochromators.

####3. Available DIY resources
DIY fluorometers are already available, which are developed to a different degree. [Here](http://www.prizmatix.com/dev/fluorometer.htm) are two examples, showing an LED and a multi wavelength device. These seem to be most developed. There is also an [arduino based](http://biodesign.cc/2014/09/18/fluorometer-v1-0/) design, which is still in the development phase. The only one also available as a kit, is the [Public Labs oil testing fluorometer](http://www.instructables.com/id/DIY-Oil-Pollution-Testing/), which uses an UV laser as its lightsource.

####4. Is DIY good enough and reasonable?
DIY fluorometer seem reasonable, especially if one is also developin UV-Vis spectrometers (the technology will be similar). However, the performance of the above mentioned devices is unknown and will have to be tested.

####5. Requirements and plans
Providing, a UV lightsource can be assured, a fluorescence spectrometer could, in principle, be built in combination with a standard UV-Vis spectrometer. This could be achieved simply, by adding a second detector parallel to the sample, next to the produced light beam. For this however, a monochromatic lightsource would be beneficial. For fluorescent excitation in biological molecules, only a few wavelengths are required for good analysis (depending on other experimental materials, such as dyes), which could be produced by LEDs.

---


###Raman spectroscope <a id="raman"></a>

![spectra_raman](https://cloud.githubusercontent.com/assets/17159617/13487305/2b79db52-e119-11e5-985f-a611cc8838a6.png)

Sources: https://www.semrock.com/high-performance-raman-spectroscopy.aspx
http://www.laboratoryequipment.com/articles/2013/03/raman-spectroscopy-tackles-pharmaceutical-raw-materials


####1. Background
Raman spectroscopy is a technique, used to identify molecular bonds in a material, by observing their low-frequency vibrations. These are produced by Raman scattering of usually very intense monochromatic light. A laser beam is projected on a sample and the light from the illuminated spot is collected, filtered (reflected laser light is removed), difracted on a grating and the spectrum is recorded and analyzed. The so called "fingerprint" spectrum, which can be used for the identification of most bonds, lies between 400-1500 wavenumbers (<sup>-1</sup>), which reflects wavelengths in the IR spectrum. A great resource on Raman spectroscopy with much more information can be found [here](http://www.omegafilters.com/applications/raman-spectroscopy/).

Keywords: raman, spectroscopy, wavenumber, molecular, identification

####2. Commercial variants
Commercial Raman spectrometers can cost several 100k€, even used devices cost several 10k€.

####3. Available DIY resources
There have been some projects dealing with DIY Raman spectroscopy. [Ben Krasnow](http://benkrasnow.blogspot.si/2013/05/intro-to-diy-raman-spectroscopy.html), author of a [DIY SEM](#SEM) provides a well documented video on a simple DIY system, which is however limited to the CCD range of a digital camera, that doesn't overlap with the "fingerprint" region of most materials, would however still prove usefull in material characterization. A great, 3D printable and more sophisticated device is the [ramanPi](https://hackaday.io/project/1279-ramanpi-raman-spectrometer), which is well documented in made from printable or off the shelf parts. In addition, there is also an [open paper](http://www.sciencemadness.org/scipics/ed800081t.pdf), on how to build a cheap Raman spectrometer, which uses a simple laser pointer, but is supposedly still suitable for research purposes.

####4. Is DIY good enough and reasonable?
Due to the high costs, making your own Raman spectrometer seems a good idea. The performance of the current devices is questionable however. Surely, some analysis can be done, but most of it in the visible-NIR spectrum, providin information, which can possibly be acquired by other methods. However, if already building other spectrometers, especially IR devices, many possibilities for combination occur.

####5. Requirements and plans
A good Raman spectrometer requires a strong light source with a narrow spectrum (laser), sufficient optics for focusing and redirecting light to and from a sample, a filter which removes the laser light from the measurement, suitable scattering and detection of the measured Raman scattering.

---



