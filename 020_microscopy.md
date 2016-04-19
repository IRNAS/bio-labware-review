##Microscopy <a id="Microscopy"></a>

###Table of contents

- [Overview](000_bio-labware_overview.md)
- [General/wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
  * [Stereo microscope](020_microscopy.md#Stereo-microscope)
  * [Classical optical microscope](020_microscopy.md#Optical-microscope)
  * [Fluorescence microscope](020_microscopy.md#Fluorescence-microscope)
  * [Two-photon laser microscope (link)](https://openwiki.janelia.org/wiki/display/shareddesigns/Shared+Two-photon+Microscope+Designs)
  * [Microtome](020_microscopy.md#Microtome)
  * [Transmission electron microscope](020_microscopy.md#TEM)
  * [Scanning electron microscope](020_microscopy.md#SEM)
  * [Sputter coater](020_microscopy.md#Sputter-coater)
  * [Scanning tunneling microscope](020_microscopy.md#STM)
  * [Atomic force microscope](020_microscopy.md#AFM)
- [Spectroscopy](030_spectroscopy.md)
- [Chromatography (separation)](040_chromatography_sep.md)
- [Chromatography (detection)](050_chromatography_det.md)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](070_cell_culture.md)
- [Electrophysiology](080_electrophysiology.md)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)


###Introduction
The focus in this chapter lies in creating an overview of the more basic and general types of microscopy, for example optical microscopy, however, we DO NOT go into detail of more specialized and advanced techniques at this point (like confocal, phase contrast, interference microscopy, etc.). Hopefully, we will be able to fill in such gaps in the future. A fantastic resource on microscopes, how they work, advantages/dissadvantages, etc., can be found [here](http://www.microscopemaster.com/).

###Stero microscope <a id="Stereo-microscope"></a>
![stereo_microscope](https://cloud.githubusercontent.com/assets/17159617/13277752/8a57ddbc-dacb-11e5-83f2-5157752dbe4a.jpg)

Source: http://www.amscope.com/7x-45x-inspection-dissecting-zoom-power-stereo-microscope-with-64-led-light.html

####1. Background
Stereo microscopes are optical devices, designed for lower magnifications (usually up to 100x) and the observation of small to medium sized samples. Illumination is reflected from the sample and can come from an external source. The light travels through 2 optical paths, which improves the 3-dimensional visualization. Due to the available space between the sample and the optical parts, the set-up also allows for sample manipulation and further preparation for other methods.

Keywords: stereo, binocular, microscope

####2. Commercial variants
Commercial stereo microscopes cost from 150€ upwards, very fancy ones up to 1000€. The most expensive part of the device is probably the optics, which is hardly compensated by DIY devices, since quality lenses are extremely hard to produce DIY. In addition to the classical devices, there are also [digital microscopes](http://www.amazon.de/XCSOURCE%C2%AE-Magnifier-Digital-mikroskop-Endoskop-TE071/dp/B00N4K22OA/ref=sr_1_1?ie=UTF8&qid=1455540890&sr=8-1&keywords=digital+microscope) on the market, which are monocular, very cheap (25 - 60€) and have a similar constitution to the classical stereo microscopes and could serve the same function. They also offer very high magnification, although the resolution and focusing are questionable.

####3. Available DIY resources
As mentioned, it is irrational to make lenses and other optics from scratch, however, if there are resources for these, which are relatively cheap, it could make sense. There is just [one DIY design](http://www.funsci.com/fun3_en/uster2/uster2.htm) available at the moment, which uses a combination of different cheap binoculars. Binoculars are already available at amazon for a little more than 10€, so the construction seems worth-while.

####4. Is DIY good enough and reasonable?
It is difficult to comment on the DIY soultions at this point, since not many are available. The requirements for a stero microscope are, however, relatively low, so a low cost device, as mentioned above, seems reasonable.

####5. Requirements and plans
The magnification and the focus, need to be gradually adjustable by hand. A minimum satisfactory maginifcation is probably about 50x, however, the device needs to have enough space between smaple and the lenses, to allow manipulation.

---


###Classical optical microscope <a id="Optical-microscope"></a>
![normal_gastric_mucosa_low_mag](https://cloud.githubusercontent.com/assets/17159617/13277844/1eab62cc-dacc-11e5-96b5-64680ee06b7d.jpg)

Source: https://en.wikipedia.org/wiki/Anatomy

####1. Background
Microscopes were developed for observation of very small samples. Traditionally, the first encounter with microscopy comes via a classical optical microscope. In what we call "bright field" microscopy, light from a source is transmitted through a very thin sample, the image is then focused and magnified, through a system of lenses. To improve resolution and observability of the sample, this can be prepared in advance, by fixating, very thin sectioning, staining,... Commonly, optical microscopes enable magnifications of up to 1000x. Due to the limitations of visible light, highest magnifications mostly require immersion oils, for focus improvement.

Keywords: Optical, bright, field, microscope

####2. Commercial variants
Hobby microscopes can often be acquired for 150€ or less, these, however, typically have very poor optics, with low resolutions, depth of field, focus, etc. and consequently aren't really suitable for research. The simplest lab-grade microscopes are availabe from 300€ upwards, with a limit in the thousands of €. High prices are due to the optical requirements, however, new microscopes also have expensive features, which aren't always neccessary.

####3. Available DIY resources
There are a few DIY microscopes available at the moment, which use the optics of available devices, such as web-cams ([example 1](http://hackteria.org/wiki/DIY_microscopy), [example 2](http://www.instructables.com/id/Save-money-on-your-DIY-laboratory-robust-easy-to-f/)), [smartphones](http://www.instructables.com/id/10-Smartphone-to-digital-microscope-conversion/), etc. These can come very cheap (if you already have a smartphone) and are suitable for simple microscopy, but it depends, whether, they will suit your needs. A very important aspect of microscopy is also the precise control of the sample, relative to the objective. The [OpenFlexure](http://docubricks.com/projects/openflexure-microscope) design, allows the precise manipulation, presumably below 100nm, which is a powerful tool to integrate with other solutions.

####4. Is DIY good enough and reasonable?
The important issues in microscopy are, as mentioned, sufficient lighting, focus and magnification. Lighting can be controlled with a light source, and the condenser (which also determines the angle and focus, at which light hits the sample), focus and magnification are typically determined by the objective lenses and the ocular. There are usually other issues as well. Microscopes usually have a very near depth of field, it is therefore crucial, that the samples are very thin. Also, since the light normally passes through different media before it hits the objective, it can diffract and distort the image. Therefore, at higher magnifications immersion oils are used to place between the objective and a cover slip, on top of the sample. With the available DIY resources, all of these factors are difficult to control, it is therefore questionable if they are good enough.

####5. Requirements and plans
A good microscope should have an adjustable light source (adjustable intensity, however, providing a very even ilumination), and the capabilities to focus light with a condenser. The microscopy optics should also enable good magnification, while retaining resolution. An optical microscope can be purely digital and based, for example, on a web-cam, however, we feel that improvements can be done on the existing models.

---


###Fluorescence microscope <a id="Fluorescence-microscope"></a>
![fluorescent](https://cloud.githubusercontent.com/assets/17159617/13277949/c68c98e4-dacc-11e5-8420-79d6c14e8540.jpg)

Source: http://www.scopem.ethz.ch/gallery/01.html

####1. Background
A fluorescence microscope can be used for samples with luminescent (self-light-emitting) properties, like fluorescence, or photophorescence, where instead of transmitted or reflected light, the emitting light from the samples themselves is observed. In principle, its build-up is similar to a classical optical microscope, but in addition, it has a second light source with appropriate wavelengths, to excite the sample and cause it to emit its own light (with slightly longer wavelengths). Typically the excitatory light is reflected of a dichronic mirror (transmits some wavelenghts and reflects others), then travells through the objective, where it focuses on the visible part of the sample. The fluorescent light then travels back through the objective, but also through the dichronic mirror, towards the ocular.

Keywords: fluorescence, photophorescence, luminescence, optical, microscope

####2. Commercial variants
While it seems that the modification is a small one, fluorescent microscopes are substantially more expensive, compared to the classical optical ones, costing several thousand €, the cheaper ones around 3000€. The dichronic filters (mirrors) alone can cost 500-1000€, depending on their wavelength specificity. Also, the second light source will contribute to the expensiveness.

####3. Available DIY resources
DIY fluorescence microscopes typically use existing bright field microscopes as a base and integrate additional lighting and filters. Great examples are [example 1](http://makezine.com/2011/03/04/cheap-diy-gfp-green-fluorescent-protein-illuminator/) suitable for GFP and DsRED, and the more sophisticated [example 2](http://dm516.user.srcf.net/?p=107), also suitble for GFPs. The most advanced is probably the portable, bright field and fluorescence microscope - [The Global Focus microscope](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0011890), which is built from scratch for 240$, uses a simple flashlight for the light source and reaches a resolution of 0.8μm at a 1000x magnification.

####4. Is DIY good enough and reasonable?
Maybe a bit surprising, though more difficult to make, DIY fluorescence microscopes seem to be more advanced than their classical bright-field counterparts. The Global Focus microscope project, seems to fulfill the expectations of a laboratory microscope. It could be even improved upon by integrating a steady, adjustable light source and a condensor lense for an improved signal. Also an additional digital camera would allow the capturing of images directly on a computer, which is important for recordings.

####5. Requirements and plans
A fluorescent microscope should in principle have the same optical capabilities as a bright-field microscope, with the addition of creating and detecting fluorescence. The latter is strongly depends on the light source and filters, and needs to be adjusted to the fluorescent material. When performing immunohistochemical analysis, the fluorophores/antibodies need to be acquired in accordance with the capabilities of the microscope.

---


###Microtome <a id="Microtome"></a>
![microtome](http://www.medequipsource.com/wp-content/uploads/Microtome-Ribbon-on-Leica-Microtome-Medical-Equipment-Source3.jpg)

Source: http://www.medequipsource.com/microtome-cutting-tips-microtome-cutting-thick-and-think-sections-are-irregular-skipped/


####1. Background
Microtomes are the main tool of sample preparation for optical microscopy. They mainly consist of a sample holder, containing the sample (which is fixed in somekind of solid medium like parafin, epoxi resins,...), a knife and a cyclic mechanism to cut the sample into thin slices. Typical "semi-thin" sections, suitble for optical microscopy are around 1μm thin, but for different purposes also sections of up to 100μm are used. There are a few methods of microtomy, like cryosection (rapid freezing of samples, allows the sectioning and analysis of a sample, while the rest of the tissue is kept intact), or ultramicrosection (creating very thin, ~70nm thick sections, suitable for electron microscopy), all using the same basic principle.

Keywords: microtome, sectioning, semi, thin

####2. Commercial variants
There are different forms of microtomes on the market, most common are rotary microtomes, which still have many variants. Manual to automatic, using steel, glass, or even diamond knives, appropriate for parafin, epoxy, or frozen samples. The most common semi-automated microtomes are fairly expensive, costing from 2000 - 10000€. It is crucial, that the sections are as thin as adjusted and cut evenly (up to 20nm thin), which requires very precise mechanics, thus the high price.

####3. Available DIY resources
DIY projects are a rarity at the moment, the reason for which is unknown. It is possible, that this is due to a high discrepancy between the research standards, compared to hobby requirements. Most DIY methods ([example 1](https://www.shroomery.org/forums/showflat.php/Number/15817715), [example 2](http://microgigapan.blogspot.si/2010/10/diy-microtome.html), [example 3](http://micro.sci-toys.com/microtome)) use a manual system, where the sample is placed on top of a bolt and the section thickness is set with a nut. Sections are prepared manually, by sliding over the nut with a blade. The most sophisticated DIY microtome at the moment is actually built from [LEGOs](http://www.instructables.com/id/Lego-Microtome/?ALLSTEPS) and can reach an estimated section thinness of 250μm.

####4. Is DIY good enough and reasonable?
The current DIY status of microtomes is far from sufficient for serious microscopy. In any case, it should be possible build a DIY, maybe 3D prinatlbe microtome, producing even slices, the greater challenge would be achieving the required 1μm section range, or even go beyond, to ultrathin sections. For this endeavor, possibly a combination of mechanics and alternative processes can be used (for example temperature dependent expansion).

####5. Requirements and plans
As it is currently lacking, we will set out to develop a DIY microtome, which can be made from 3D printable parts, assebled easily, but will meet the requirements (or come very close at least) of commercial devices.

---

###Transmission electron microscope <a id="TEM"></a>
![cell_tem](https://cloud.githubusercontent.com/assets/17159617/13278119/287da362-dace-11e5-8ea8-ed00e47dab7d.jpg)

Source: http://www.wormbook.org/chapters/www_intromethodscellbiology/intromethodscellbiology.html

####1. Background
The resolution of an optical system has its physical limitations. Due to diffractional properties of electromagnetic radiation, an important one is the wavelength. As a consequence, we cannot look far into the sub-micrometer scale with only visible light. However, this is not always neccessary. Electrons can have a significantly shorter wavelength than visible light, which allows the observation of even smaller objects, sophisticated devices can reach a sub Ångström resolution. A transmission electron microscope (TEM) uses a focused electron beam, which is projected through a very thin (~70nm), contrasted sample (some structures absorb the electrons, others don't), on a CCD, which is then used to produce a visible grey-scale image. 

Keywords: transmission, electron, microscope, tem, wavelenght, resolution.

####2. Commercial variants
Commercial TEMs are very expensive, costing several 10k€, up to a few 100k€ or even 1M€, depending on their capabilities. These are determined by the quality of the lens system (magnetic lenses), the range of electron acceleration,... To prevent the electrons to interact with gases, the procedure needs to take place in a vacuum, which is also required for preventing an arc between the high voltage cathode and the ground. The system also requires cooling, a stable power supply and a vibration free ground, to create good quality, sharp images.
In addition, TEM imaging requires the adequade sample preparation, using an ultramicrotome for sectioning, usually in combination with glass and diamond knives.

####3. Available DIY resources
There seems to be only [one resource](http://www.microscopy-uk.org.uk/mag/indexmag.html?http://www.microscopy-uk.org.uk/mag/artapr01/rhtem.html) of someone building a home-made transmission electron microscope, sadly, no documentation is available.

####4. Is DIY good enough and reasonable?
The images produces with the mentioned system are of reasonalbe quality, possibly allowing the inspection of cell ultrastructure (with appropriate samples of course), which is good enough for general use!

####5. Requirements and plans
As there are no resources on DIY TEMs available, they will have to be made from scratch. Luckily, there is one more documented project on scanning electron microscopy, which could maybe be used as a basis.

---

###Scanning electron microscope (SEM) <a id="SEM"></a>
![sem_peacock](https://cloud.githubusercontent.com/assets/17159617/13278180/a4b597dc-dace-11e5-964b-7d6fd630a346.JPG)

Source: https://en.wikipedia.org/wiki/Lepidoptera

####1. Background
In contrast to a TEM, a scanning electron microscope (SEM) does not project electrons through a sample. Rather, the beam is focused on the surface, which absorbs the electrons and emits secondary ones, which are then projected to CCD. For this to work, the sample surface needs to be conductive, which is why nonmetalic samples are coated with a metallic thin film (gold, silver), usually by sputtering, or phisical vapor deposition.

In addition to emitting secondary electrons after primary electron absorption, matter usually also emitts other electromagnetic radiation, in the x-ray spectrum. these are element specific and can be used to determine the chemical composition of a sample, using energy-dispersive x-ray spectroscopy (EDX). The sensors are mostly very sensitive and require to be cooled with liquid nitrogen.

Keywords: scanning, electron, microscope, sputter, coating, edx, ex-ray

####2. Commercial variants
As TEMs, SEMs are very expensive devices, they do, however use lower voltages and typically have shorter cathode tubes. Used devices cost 10k to several 10k€, new SEMs go into 100k€ or into the million € range, for devices with additional EDX or STEM (a limited form of TEM using a SEM) capabilities.

####3. Available DIY resources
There is one "fairly" documented DIY SEM project available, made by [Ben Krasnow](http://benkrasnow.blogspot.si/2011/03/diy-scanning-electron-microscope.html), who also made a few videos showing the capabilities of his, very imperssive device.

####4. Is DIY good enough and reasonable?
The images provided by Krasnow show good-enough quality of his DIY-SEM. The magnification is the major limiting factor and whether it suffices is dependent on the samples. For the average DIY enthusiast it is surely good enough.

####5. Requirements and plans
A good-enough SEM should be capable of providing a sharp image at magnifications of a few thousand-folds.

---

###Sputter coater <a id="Sputter-coater"></a>

![sputter](https://cloud.githubusercontent.com/assets/17159617/13278196/e928d032-dace-11e5-90ca-c4ec0726cd6b.jpg)

Source: http://blogs.evergreen.edu/fiseva21/?p=632

####1. Background
Sputter coaters are used for depositing of metals on nonconductive samples for scanning electron microscopy. Usually, an inert (so it does not react with the wafer material) gas at low pressures is accelerated and ionized in a strong electric field, to very high speeds, at which it can remove molecules from a "wafer" it hits. Those molecules are then dispersed and can condense nearby surfaces. If the wafer is made from a metal, like Gold or Palladium (often used for SEM sputtering), the coated surfaces become conductive and thus suitable for SEM.

Keywords: sputter, coating, metal, deposition

####2. Commercial variants
Commercial sputter coaters cost a few thousand €, even second-hand ones. The cheapest used variants with broken parts come for around 500€.

####3. Available DIY resources
Interestingly, there seem to be more DIY sputter coater projects circulating the internet, than DIY SEMs. [Example 1](https://www.youtube.com/watch?v=N-Um1_Eo0sI), [example 2](https://www.youtube.com/watch?v=PnoLNAmQLp8), [example 3](https://www.youtube.com/watch?v=9OEz_e9C4KM). Most use a simple vacuum chamber and many don't even use a noble gas, a simple magnet composition and a high voltage generator. Sputter coating is probably the most widely used method for SEM sample preparation, however, there are other alternatives as well, like physical vapor deposition by evaporation at very high temperatures, or even chemical methods like silver coating with silver nitrate. Whether a method is suitable, depends on the sample and the wished results.

####4. Is DIY good enough and reasonable?
Existing DIY projects do seem good enough, however, most of them are poorly documented.

####5. Requirements and plans
The pressure in the chamber needs to be low enough, to sustain a small amount of ionized gas particles, thus allowing high voltages without short-circuiting. An inert gas, like Argon is required, which does not react with the sputtering metal and controlled magnetic and electric fields are required to accelerate the gas towards the metal.

---


###Scanning tunneling microscope <a id="STM"></a>

![stm](https://cloud.githubusercontent.com/assets/17159617/13278229/4156d1fa-dacf-11e5-992a-317cf764449f.jpg)

Source: http://nanotribology.mse.ufl.edu/research.html

####1. Background
A scanning tunneling microscope (STM) is a device for imaging surfaces at scales of the atomic level. It uses a concept known as quantum tunneling, where a fine, conducting tip (under a small voltge) is placed near a sample. When the distance is short enough, electrons can "tunnel" through the empty space between them, whereas the measured current depends on the tip position relative to the sample, the voltage and the density of space of the sample. Using this technique, extremely precise surface profiles of a sample can be measured, even single atoms can be made visible.

Keywords: scanning, tunneling, microscope, atomic, scale, surface

####2. Commercial variants
"Cheap" commercial STMs can be acquired for about 10 000€, however more high-end devices can cost from 30k to 150k€.

####3. Available DIY resources
A few DIY STMs with good documentation are currently available, which can be assembled for less than a 1000€, but can still reach the atomic scale. Best described are [example 1](http://dberard.com/home-built-stm/), [example 2](http://www.formatex.info/microscopy4/1280-1286.pdf) and [example 3](http://www.popsci.com/diy/article/2010-07/homemade-open-source-scanning-tunneling-electron-microscope).

####4. Is DIY good enough and reasonable?
The current DIY STMs seem to be a serious competition to the commercial devices, at least for measuring conductive materials. The control and precision may not be quite as high, but seems to be more than sufficient to determine the crystal structure of metals for example.

####5. Requirements and plans
Due to the small scale, possibly the most important issue to tackle is vibration isolation. There are different methods, how to achieve this, in general, the measurement device (containing the sample) requires a large inertia (needs to be relatively heavy), while resting on some sort of spring or pillow. Another important characteristic is tip size, which needs to be appropriately small and narrow, to achieve a good spatial resolution and finally, motion control of the sensor needs to be sufficient, which can be achieved for example, by controling the thermal expansion of the mount, or using a piezoelectric crystal, etc.

---

###Atomic force microscope <a id="AFM"></a>

![afm_sample](https://cloud.githubusercontent.com/assets/17159617/13278286/acd4c888-dacf-11e5-9993-9fe06ad80e1c.gif)

Source: https://you.stonybrook.edu/nanoraman/bruker-innova-atomic-force-microscope/

####1. Background
Similar to the STM, an atomic force microscope (AFM) uses a very fine tip (on a cantilever), which can be (but doesn't have to) brought in contact with the sample surface and is then used to scan across it, while the cantilever displacement is measured. In addition to measuring the height profile, an AFM can also be used to measure other characteristics, such as mechanical or surface interaction properties of a sample. The cantilever deflection is often measured by a laserbeam, which is reflected of the cantilever and redirected by a displacement.

Keywords: atomic, force, microscope, surface, properties

####2. Commercial variants
Commercial AFMs usually cost several 10k€ and up to a few 100k€. They come in many different forms, for a wide range of applicability (different sizes, mounted on a microscope, adjusted for wet samples, automated to different degrees, etc.).

####3. Available DIY resources
In 2015, [a DIY AFM project](https://www.google.si/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjfp-TZtY7LAhWjCpoKHUZTAWgQFggmMAA&url=http%3A%2F%2Fwww.instructables.com%2Fid%2FA-Low-Cost-Atomic-Force-Microscope-%25E4%25BD%258E%25E6%2588%2590%25E6%259C%25AC%25E5%258E%259F%25E5%25AD%2590%25E5%258A%259B%25E9%25A1%25AF%25E5%25BE%25AE%25E9%258F%25A1%2F&usg=AFQjCNFu3gbfBGyaauqW24wfUmQ74zIzgA&sig2=Jc4-I4_iWZA_VJJw0O-Vww) was published in Nature Nanotechnology, which can be built by school children in a few hours and can successfully measure particles with a size of 2,5μm. This was part of the [OpenAFM](http://openafm.com/) project, supported by the LEGO foundation. One of the more advanced spin-offs for example, is the [Strømlingo nano](http://www.stromlinet-nano.com/), which is also available commercially for 2999$.

####4. Is DIY good enough and reasonable?
The available DIY resources were actually created for educational purposes, however, they do achieve respectable specifications for a very low price. Whether they suffice for high end research is questionable. However, it should be noted, that open source devices can generally be easily modified for specific purposes, which is especially useful for AFMs, with their wide range of (typically very costly) forms and adaptations.

####5. Requirements and plans
Due to the mechanical interaction of the AFM tip with the samples, it is easily damaged and needs to be replaced over time. For this reason it is imporant for an AFMs construction to allow simple and fast cantilever exchange. It is also beneficial, if it allows the installation of several types of cantilevers, which bring additional functionality to the device (different geometries, materials, tip coatings, etc.). The scannig process requires fine control over cantilever movement, and a precise displacement detection! Similar to the STM, an AFM also needs some form of vibration reduction.
