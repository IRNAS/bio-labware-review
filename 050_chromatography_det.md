##Chromatography (detection) <a id="chrom-det"></a>

###Table of contents
- [Overview](000_bio-labware_overview.md)
- [General/wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
- [Spectroscopy](030_spectroscopy.md)
- [Chromatography (separation)](040_chromatography_sep.md)
- [Chromatography (detection)](#chrom-det)
  * [UV-Vis and fluorescence detection](#uv-vis-fluo)
  * [Refractive Index detection (RI)](#RI)
  * [Mass spectroscopy (MS)](#MS)
  * [Evaporative light scattering detection (ELSD)](#ELSD)
  * [Electrochemical detection](#ED)
  * [Flame ionization detection (FID)](#FID)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](070_cell_culture.md)
- [Electrophysiology](080_electrophysiology.md)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)


Sometimes substances, which were separated by chromatography, are already observable/identifiable (for example by color), which makes them relatively simple to process and analyze further. More often than not this is, however, not the case.

Therefore, a proper form of detection is required. Many techniques have been developed over the years and quite a few (especially mild-nondestructive procedures) are based on methods also used for other endeavors, especially spectroscopy. In circumstances where this is not possible, harsh or destructive methods are required for detection. With such detection methods, especially if they are very sensitive, the eluent is often split in two, to preserve a large part of the sample, while destroying the small one.

---


###UV-Vis and fluorescence detection <a id="uv-vis-fluo"></a>
![uv-vis-det](http://images.alfresco.advanstar.com/alfresco_images/pharma/2014/11/25/c0888f58-7bee-485d-9292-298431913b05/Fig1.jpg)

Source: http://www.chromatographyonline.com/lcgc-blog-so-just-how-well-set-your-uv-detector

####1. Background
UV-Vis or fluorescence spectroscopy, already described in a [previous chapter](030_spectroscopy.md), is with its broad applicability and non-destructive nature a great resource for detection. It is therefore also used for different forms chromatography, from high performance liquid chromatography, to gel electrophoresis. As usually a specific type of compound is the point of interest, the lightsource is set to a fixed wavelength, for which either absorption or fluorescence is measured. In liquid chromatography sistems, which use columns and a steady flow of mobile phase, basically any UV-Vis or fluorescence spectroscopy system can be used, however, if the samples are to be further analyzed, the spectrometer should be synched with the rest of the system, to enable precise fraction collection.
In gel electrophoresis, especially DNA/RNA analysis, the samples are visualized with so called gel-documentation devices, which usually excite a fluorescent glow of DNA fragments, which were stained beforehand. Traditionally the staining was performed using ethidium bromide, which is very toxic and is nowadays being replaced by other stains, such as sybr-green, crystal violet, etc. The gel documentations themselves are typically composed of a flat transparent surface, an underlying light source, a top filter for UV light and a form of sample recording (eg digital camera). Protein gels (eg SDS-PAGE) are normally stained with coomassie's blue staining (which makes all proteins visible) or are transferred to a membrane (often nitrocellulose) and further processed by means of immunohistochemistry, which will be discussed in another chapter.

Keywords: ultra violet, UV, visible, light, fluorescence, detection, gel, documentation

####2. Commercial variants
Commercial HPLC detectors with UV-Vis or fluorescence capabilities, usually cost a few thousand € and can only be used for the purpose of analyzing a samples, which enter and leave the detector through a narrow tube. Gel documentations are typically in the few hundred € range, but can also cost a few thousand €, if they have "fancy" capabilities, such as wifi control, etc.

####3. Available DIY resources
DIY spectrometers in general, were already covered in the [spectroscopy chapter](030_spectroscopy.md). In principle, LC functionality would be easily achieved with standard devices, with the addition of a simple cell with an integrated tube, which is connected to the pumping system.
For gel documentations, there quite a few DIY designs, [example 1](http://bitesizebio.com/26/low-cost-dna-gel-photography/), [example 2](http://blog.genefoo.com/), [example 3](http://www.huettlab.co.uk/blog/2011/12/16/cheap-led-gel-doc-using-a-webcam-updated.html), [example 3](http://www.labtimes.org/labtimes/issues/lt2011/lt02/lt_2011_02_64_65.pdf) and even "off-the-shelf" finished components and kits, such as provided bi [iorodeo](http://iorodeo.com/collections).

####4. Is DIY good enough and reasonable?
As they are fairly simple in their build-up, it actually seems unreasonable, to buy commercial gel documentations over the DIY devices, or make one yourself. For LC detectors on the other hand, this depends on the range and precision your require for detection, as the fabrication of high quality optical components can be expensive by itself.

####5. Requirements and plans
UV-Vis-fluorescence detectors for HPLC in principle have the same requirements, as in general spectroscopy. In addition, they should also have the capability of setting a specific wavelength and to continiuously measure samples in a thin tube with constant flow.



---



###Refractive Index detection (RI) <a id="RI"></a>

![ref-ind](https://upload.wikimedia.org/wikipedia/commons/8/85/Refraction_photo.png)

Source: By ajizai - http://www.docstoc.com/docs/130534946/Chapter-7-Refractive-index, Public Domain, https://commons.wikimedia.org/w/index.php?curid=30455241

####1. Background
While some substances don't necessarily absorb light of these spectra differently than their solvent, they can still contribute to the cumulative  optical density. As a result, light passing through the mixture under an angle, will be refracted to a different degree, depending on the concentration of the solute. That is why for substances, which are invisible in the UV-Vis spectrum (when dissolved), refractive index (RI) detectors can be used. While having this obvious upside, a problem with RI detectors is their relatively low sensitivity to concentration change. Also, they are less suitable for chromatography, where a mixture of different solvents in a gradient is used. In addition, the detection can be impacted by other factors, such as the change in flow rate or temperature of the solvent.

Sometimes, RI detectors are referred to as refractometers, however, these are typically simple, handheld devices, designed to determine the sugar content in beverages, salinity of aquariums, etc.

Keywords: refractive, index, detection, RI

####2. Commercial variants
digital RI detectors for laboratory analysis, are in the 1-10k€ range, depending on their functionality, brand, etc.

####3. Available DIY resources
While there are many fun experiments with refraction you can try at home, and are described in detail online (like [this one](http://www.yoctopuce.com/EN/article/how-to-build-a-rain-sensor)), DIY refraction index detectors do not seem to be present at all! While RID may be used less than other methods, it is still a powerfull tool, which should be relatively easy to make DIY.

####4. Is DIY good enough and reasonable?
As there are no DIY projects available at the moment, it is pointless to comment on the quality.

####5. Requirements and plans
As for most other detectors, it is beneficiall, to have a wide range of detection with a good precision and reliability of the signal.


---



###Mass spectroscopy (MS) <a id="MS"></a>

![MS](http://www.mhhe.com/physsci/chemistry/carey/student/olc/graphics/carey04oc/ch13/figures/1334.gif)

Source: http://www.mhhe.com/physsci/chemistry/carey/student/olc/ch13ms.html

####1. Background
Mass spectroscopy, or MS, is used in biochemical analysis, to determine the precise size of a sample. Molecules are typically ionized (charged) and then accelerated through an electric and magnetic fields, which change their course and velocity, depending on the particles mass-to-charge ratio (s/z). There are many different types of sample ionization (matrix-assisted laser desorption ionization - MALDI, electrospray ionization - ESI, coupled plasma, chemical ionization, etc.), with all being advantageous for some type of use. Similarly, there are many different methods of ion separation and detection (time of flight - TOF, quadrupole mass analyzers,...). Many devices are also coupled with a chromatographic system, such as [HPLC](#HPLC), [GC](#GC), etc. A good source of information on MS is actually its [Wikipedia page](https://en.wikipedia.org/wiki/Mass_spectrometry).

Mass spectrometers are typically used after liquid chromatography such as HPLC. This can substantially improve the signal, since already very "pure" samples of only a few different molecules are used.

Keywords: mass, spectroscopy, MS, mass-to-charge, ratio, time-of-flight, TOF

####2. Commercial variants
Depending on the method they use for ionization and analysis, and the combination with a chromatography unit, mass spectrometers cost several 10k€. Even used devices begin above 20000€.

####3. Available DIY resources
There is in fact a scientific paper on the construction of a [homemade time-of-flight MS](http://dx.doi.org/10.1063/1.2832334), which was published in the Review of Scientific Instruments in 2008. The construction plans are not very detailed, but the testing results of the device are very promising. Supposedly, the device has a detection range from 45 to 8000Da and can detect samples in very small quantities, as low as 2.5fmol. 

####4. Is DIY good enough and reasonable?
Unfortunately, this was the only design, so it is not possible to make comparisons. From the described capabilities, however, it seems well suited for serious research.

####5. Requirements and plans
A good enough MS should be capable to separate similar, small organic substances based on their mass-to-charge ratio. It should have a reasonable range of detection, the above mentioned 45 to 8000 seems reasonable, a good resolution and sensitivity. 


---



###Evaporative light scattering detection (ELSD) <a id="ELSD"></a>

![elsd](http://www.chromacademy.com/essential-guide/Jan-2014/figure-23.jpg)

Source: http://www.chromacademy.com/HPLC-detectors.html

####1. Background
Evaporative light scattering detectors or ELSDs are one of the most powerfull techniques in chromatographic detection. The solvent containing the sample is evaporated after separation, and passes through a light, which scatters if particles (of sample without solvent) of any kind are present. This eliminates the problem of particle "invisibility" in the solvet, which appears in UV-Vis-fluo systems. While being very versatile, these detectors do have their limitations. Crystal formation on the detector can block and damage it, therefore salts in the solvent need to be reduced to a minimum, best not used at all.
As this is a destructive detection method, flow splitters can be placed before the detector, thus only a fraction of the sample is destroyed. 

Keywords: evaporative, light, scattering, detection, ELSD

####2. Commercial variants
ELSDs cost from 10k to several 10k€, used devices are available for 1-10k€.

####3. Available DIY resources
Unfortunately, there seem to be no resources on DIY/homemade ELSD detectors. In comparison to some other DIY research projects, this actually seems fairly simple, so it is likely, it hasn't found use in the DIY/open hardware and science community yet.

####4. Is DIY good enough and reasonable?
/

####5. Requirements and plans
The mobile phase, containing the solutes needs to be evaporated in a way, only the solutes remain and are then projected through a light source, which is scattered in the process, producing a signal on the detector.



---



###Electrochemical/amperometric detection (ED) <a id="ED"></a>

![ED-PAD](http://chemwiki.ucdavis.edu/@api/deki/files/12425/=Figure12.49.jpg)

Source: http://chemwiki.ucdavis.edu/Core/Analytical_Chemistry/Analytical_Chemistry_2.0/12_Chromatographic_and_Electrophoretic_Methods/12E%3A_High-Performance_Liquid_Chromatography

####1. Background
This set of methods is used to measure the change of electric current or conductivity in solutions (by passing ions). Typically a voltage is set between two electrodes, through which a conductive solvent is flowing, producing a current. If a sample molecule si oxidized or reduced at the electrodes, this results in a current change. This is typically destructive, but also, sample residue can adhere and build up on the electrodes, reducing the performance. Therefore, electric pulses can be used, to gradually clean the electrodes. This is called pulsed amperometric detection or PAD.

Keywords: electrochemical, amperometric, detector, ED, PAD

####2. Commercial variants
Used EDs are available for a few hundred €, new devices can cost a few thousand and above 10k€.

####3. Available DIY resources
A project, already mentioned in the previous chapter, is describing the construction of a [portable HPLC system](http://www.rsc.org/images/loc/2012/pdf/T.4.111.pdf), using an electrochemical detector, which seems to be a well designed solution. There also other designs for DIY potentiostats, which could be used for this purpose, such as the [microsensor for metal ions](https://www.google.si/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi4vrWUvMfLAhWJkXIKHZyOCfYQFggfMAA&url=http%3A%2F%2Fwww.mdpi.com%2F1424-8220%2F10%2F6%2F5308%2Fpdf&usg=AFQjCNESL6CBzWJbUUq7cstLYxTKn3V5Nw&sig2=nIqa6_V5HJzYGI1bCQgRpQ&bvm=bv.117218890,d.bGQ), or the [CheapStat](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0023783). The latter two are actually very sophisticated and can be used in a broader sense.

####4. Is DIY good enough and reasonable?
In principle, electrochemical detectors are very simple in their build up, therefore building one seems very reasonable.

####5. Requirements and plans
Electrochemical detection is very selective and has huge linear dynamic range. 


---



###Flame ionization detection (FID) <a id="FID"></a>

![fig-2](https://cloud.githubusercontent.com/assets/17159617/13847523/ea73473e-ec4d-11e5-8016-b52c7aa7643c.jpg)

Source: http://www.sepscience.com/Techniques/GC/Articles/208-/GC-Solutions-11-The-Flame-Ionization-Detector

####1. Background
In contrast to the previously described methods, which are typically used in combination with liquid chromatography, flame ionization detectors (FIDs) are used with gas chromatography. FID is used for measuring the concentration of volatile organic compounds, by their combustion in a hydrogen flame, where the plasma (generated ions) are proportional with the concentration of the original substance. The produced ions hit an electrode with the opposite charge of the flame producing nozzle, and thereby create measurable current.

Keywords: flame, ionization, detectio, FID, GC

####2. Commercial variants
Separate detectors are available for a few hundred €, but usually come as a part of the package with gas chromatography systems.

####3. Available DIY resources
There seem to be two FID designs worth mentioning currently on the internet. The first one is a [miniaturized, battery powered FID](https://chromsci.oxfordjournals.org/content/43/7/355.full.pdf) for a portable GC system, published in the Journal of Chromatographic Science in 2005. The second is the [Electrolyzer powered FID (EFID)](http://www.tau.ac.il/~amirav/efid.html). It is not very well documented, however, it was supposed as a research project and less so, as a DIY device. In any case, this design promises improvements, even on the commercial designs and could be interesting for future developments of the method.

####4. Is DIY good enough and reasonable?
Both, the miniaturized FID, as well as the EFID show good detection signals in the first experiments, which is promissing. While more testing is required for a final conclusion, it seems reasonable to use these designs over buying commercial systems.

####5. Requirements and plans
As a very flammable gas is required for the operation, it is first and foremost important to assure safe construction and operation of FIDs (prevent hidrogen gas leakage, secure controlled exhaustion and combustion, etc.). The other important issues are producing good and reliable signals, ideally, such that the compound concentration can be calculated from the flame intensity.
