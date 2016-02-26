#Bio Labware Review

## Overview
One of our goals at symbiolab is making a complete collection of affordable and DIY laboratory equipment, which is required for common methodology in a biological research lab. To do this, we will begin by making a list of required equipment, describing the hardware, its use, commercial costs and the current DIY status. This list will include links to some DIY examples, it will however not contain actual plans for our designs, this will come later (there will be links though, once available). To make the content more legible, the equipment will be organized into categories, such as preparation, microscopy, chromatography, proteomics,...

Saying this, while we plan to collect as much DIY equipment as possible, it is important to point out, that it doesn’t make sense, to make EVERYTHING DIY. Many tools, which are commonly used in a laboratory, are simply easier and cheaper to buy, than to make from scratch. This includes glassware (beakers, measuring cylinders, petri dishes, glasks,...), basic utensils and consumables (spoons, spatulas, scalpels, tweezers,...) and basic kitchenware (fridge/freezer, dishwasher, microwave oven,...). These tools will therefore not be added to the review list.

As there is an overflow of possibilities and devices for laboratory use, it is not unlikely, we will forget something in our list. If there is something that you miss, feel free to contact us and add suggestions.

- [Wet preparation equipment](#Wet-preparation)
  * [Fine Weighing Scale/ Microbalance](#Microbalance)
  * [Magnetic stirrer](#Magnetic-stirrer)
  * [Centrifuge](#Centrifuge)
  * [Vortex mixer](#Vortex-mixer)
  * [Lab jack](#Lab-jack)
  * [Microliter pipette](#Microliter-pipette)
  * [pH meter](#pH-meter)
  * [Ultrasonic bath](#Ultrasonic-bath)
- [Microscopy](#Microscopy)
  * [Stereo microscope](#Stereo-microscope)
  * [Classical optical microscope](#Optical-microscope)
  * [Fluorescence microscope](#Fluorescence-microscope)
  * [Microtome](#Microtome)
  * [Transmission electron microscope](#TEM)
  * [Scanning electron microscope](#SEM)
  * [Sputter coater](#Sputter-coater)
  * [Scanning tunneling microscope](#STM)
  * [Atomic force microscope](#AFM)
- [Spectroscopy](#Spectroscopy)
- [Chromatography](#Chromatography)
- [Immunohistochemistry](#Immunohistochemistry)
- [Genetics and Proteomics](#Genetics-and-Proteomics)
- [Cell culture](#Cell-culture)
- [Organic 3D printing](#Organic-3D-printing)
- [Various methods](#Various-methods)


##Wet preparation equipment <a id="Wet-preparation"></a>
###Fine Weighing Scale/ Microbalance <a id="Microbalance"></a>
![Homemade_microbalance](http://sci-toys.com/scitoys/scitoys/mathematics/microgram_balance/whole_scale.jpg)

Source: http://sci-toys.com/scitoys/scitoys/mathematics/microgram_balance/

####1. Background
Precise weighing of chemicals in solution preparation, measuring small samples... Essential for any “wet” experiment, containing buffers and other solutions, which need to have a precise composition. Depending on the amounts of source material, the scales require the appropriate precision. For the average laboratory use, a precision of 0,001g or better is favorable.

Keywords: fine, weighing, gram, milli, micro, precision, scale, balance

####2. Commercial variants
The cheapest weighing scales with the appropriate precision, usually cost 100€ or more, higher quality devices around 300€. Scales capable of measuring differences in the microgram scope, can however also cost up to several 1000€ . On the other hand, devices with a 0,01g precision are already available for less than 20€.

####3. Available DIY resources
There are several fine weighing scale/microbalance projects on the internet. Most of them are easy to build, mechanical balances, such as [example 1](http://sci-toys.com/scitoys/scitoys/mathematics/microgram_balance/balance.html). While these can be precise, they are very impractical to work with, since they require balancing of samples against premade weights, which have discrete masses. There are far less DIY projects for digital scales, which could be due a relatively low necessity and the many factors, which can influence the precision and accuracy of such devices (balancing, temperature, nonlinearity...). There are still some available, such as [example 2](http://makezine.com/2008/03/25/diy-digital-balance/), with detailed [instructions](http://www.sci-spot.com/Mechanical/balance.htm), or [example 3](https://www.erowid.org/psychoactives/hardware/hardware_info1.shtml), [example 4](https://www.behance.net/gallery/8021801/Electronic-Weight-Scale-DIY-Kit). While all of these are capable of fine measurements, their precision and accuracy is questionable. An exception could be the [openQCM](http://openqcm.com/), suitable for submicrogram samples, which operates on the principle of measuring sample oscillation at high frequencies. It is fully open source, promises high precision and accuracy and offers support for Windows, Linux and Mac.

![Quartz Crystal Microbalance OpenQCM](images/openQCM.jpg)

_"[Quartz Crystal Microbalance OpenQCM](http://openqcm.com/wp-content/uploads/2015/01/Quartz-Crystal-Microbalance-openQCM-open-1024x575.jpg)" by "[openQCM](http://openqcm.com/)" is licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)_

####4. Is DIY good enough and reasonable?
Whether it is reasonable to build your own weighing scale, strongly depends on the samples you are going to measure. For material in the range of 0.01g or more, low-cost scales are readily available. However, if you need higher precision, making your own could save you a fair amount of money. Fine DIY weighing scales already exist, their main problem, however, is reliability, which is critical.

####5. Requirements and plans
The favoured specifications of a lab grade weighing scale is simple use, a precision of 0.001g, on a range from 0.001 - 500g. Possible improvements are measurement recording (wifi/cable/...), and the possibility of inverse measurement with appropriate adapters for tensile testing.


---



###Magnetic stirrer <a id="Magnetic-stirrer"></a>
![Magnetic_stirrer](https://cloud.githubusercontent.com/assets/17159617/13045381/43cb0eae-d3d3-11e5-96aa-91dd2b6bf4a7.jpg)

Source: http://www.keison.co.uk/bibbyscientific_cr302.shtml


####1. Background
Magnetic stirrers are simple devices, used in combination with small magnetic rods, which are placed in a container and turned externally, to allow mixing of liquids and/or powdery materials. Usually, the top plate of a magnetic stirrer can also function as a heating plate.

Keywords: magnetic, stirrer, heating, plate

####2. Commercial variants
Typically magnetic stirrers cost from 100€ upwards, up to 1000€ for more advanced models with integrated heating plates. They are usually relatively bulky and require an external power supply, which makes them less suitable for stirring in non-standard conditions, like a refrigerator, incubator, in the field,...

####3. Available DIY resources
Since these are very simple to make using everyday objects, there is an overflow of DIY magnetic stirrer projects. In principle they are made from a electromotor with a magnetic top blade, a power supply and housing. [Example 1](http://www.instructables.com/id/How-to-DIY-your-own-Magnetic-Stirrer-V2-better-th/) is in principle, what most DIY projects look like. [Example 2](http://www.instructables.com/id/How-to-Make-a-Cheap-Portable-Magnetic-Stirrer/)is also portable, [example 3](https://github.com/pepaslabs/PCFanMagneticStirrer) has an adjustable rotation speed. Biohack academy's [BHA stirrer](https://github.com/BioHackAcademy/BHA_Stirrer) is the most sophisticated model up to date, with good adjustability, a stable housing and an integrated heating plate.


####4. Is DIY good enough and reasonable?
Magnetic stirrers would definitely go in the category of equipment, where DIY is reasonable, or even beneficial. Commercial devices are unreasonably expensive and are limited to table-top applications. Existing DIY projects have done well to mimic the basic capabilities of commercial devices, for a fraction of the cost. More sophisticated devices also integrate a heating plate, can be portable, etc.

####5. Requirements and plans
Magnetic stirrers are cheap and easy to make, therefore we will try to establish our own model. The goal will be a stirrer, which is portable, yet can be connected to an external power supply. It should have an adjustable stirring speed (1-20Hz), which can, in addition to heating, possibly also be able to cool (0-100°C) and be controlled externally. It would be practical, to have one model without heating/cooling, which is compact and can be placed in climatized chambers (fridge, incubator).


---

###Centrifuge <a id="Centrifuge"></a>

![GoGoFuge](https://diybiology.files.wordpress.com/2012/06/gogofuge-img_2205.jpg?w=600&h=450&crop=1)

Source: https://diybiology.files.wordpress.com/2012/06/gogofuge-img_2205.jpg?w=600&h=450&crop=1

####1. Background
Centrifuges are used for separation of substances in a liquid dispersion, depending on their differences in density. They are used in most “wet” experiments and are adapted for holding laboratory tubes, such as epis (eppendorf tubes), usually in sizes for 0,5, 1,5, or 2ml and falcons (conical centrifuge tubes), 15ml, 50ml,...
The most important thing to be noted when working with centrifuges, is to make sure they are well balanced. The high rotation speeds (4000 rpm and above), can create strong forces, causing an unbalanced centrifuge to break and even endanger their environment.

Keywords: centrifuge, micro, tubes

####2. Commercial variants
There are two basic types of commercial centrifuges, which are used either for epis or for falcons. The simplest types of both sizes begin at approximately 150€ and go into several hundreds. More sophisticated models also allow temperature adjustments (cooling) for delicate samples. Also, some integrate a vacuuming function, for rapid concentrating/drying of samples during centrifugation. These are substantially more expensive, costing several thousand euros.

####3. Available DIY resources
There are several designs available for DIY variants, using [PC fans](https://www.youtube.com/watch?v=eV-EGpJaOB8), [hard drives](https://www.youtube.com/watch?v=uqa1JNLLB78), [drills](http://www.popsci.com/diy/article/2013-07/how-build-your-own-diy-centrifuge), [blenders](http://citsci.blogspot.si/2009/11/centrifuge-revisited.html)..., however, much refinement is still possible in the design. Possibly the best two variants up to date are the [OpenFuge](http://www.instructables.com/id/OpenFuge/), which however costs about 180€ to make (the control board is readily available [here](https://www.tindie.com/products/CopabX/openfuge-control-board/)) and the [GoGoFuge](https://diybio.org/2012/06/12/gogofuge/), which is an improvement on the drill based dremelfuge.


####4. Is DIY good enough and reasonable?
For simple centrifugation (separating heavy particulate from a solution), precise control is not necessary, for which, a simple drill centrifuge (such as DremelFuge) would suffice. For more advanced purposes, typical for a laboratory, it would be advantageous to have control over the centrifugal force and rotation time. It would also be immensely useful, if one could upgrade the device to a vacuum concentrator without too much effort.

####5. Requirements and plans
As there are so many different DIY models available, we will set out, to test a few of them and plan to make an improved design, that will be cheap and meet the requirements of a wet laboratory. A laboratory centrifuge should have an adjustable rotation speed (0-7000 rpm) and time (0-60min). It should also be safe and stable.

---

###Vortex mixer <a id="Vortex-mixer"></a>
![Vortex_mixer](https://cloud.githubusercontent.com/assets/17159617/13046006/a7dbd7a4-d3d6-11e5-8267-cfec64d417f3.jpg)

Source: http://www.keison.co.uk/stuart_sa7.shtml

####1. Background
Opposed to centrifuges, vortex mixers are used to mix samples together, especially those in very small amounts. The construction of a vertical mixer is relatively simple, a small rubber cup (that holds the bottom of a sample vial) is fixed on a rotor slightly of center, so when the rotor is turning, the rubber is oscillating and thus creating a vortex inside the liquid containing vial.

Keywords: Vortex, mixer, vortexer

####2. Commercial variants
Typically, vortexers cost 150 - 250€ and allow adjustment of oscillation speed and are started by applying pressure on the rubber cup.

####3. Available DIY resources
While not many, there are exising and for the purpose good-enough DIY vortex mixers available, such as [example 1](https://www.youtube.com/watch?v=C-Tar7pmDWU) and [example 2](https://github.com/jdkizer/OS-Vortex-Mixer). The latter also has available plans for construction and is estimated to cost about 20€ when built at home.

####4. Is DIY good enough and reasonable?
For simple mixing, the existing DIY variants are absolutely sufficient and come for a fraction of the commercial cost. That said, there are still many possibilities to improve the device. It is beneficial, that the vortex is relatively heavy, to remain stable while rotating samples in an asymetrical manner. What commercial variants offer as a standard, is the regulation of the rotation speed and activation upon applied pressure to the cup.
What would improve the device even more, would be exchangable mounts (for example a flat table), which would add the functionality of shaking samples in different containers, a time counter and optional portability.

####5. Requirements and plans
A vortex mixer should have an adjustable rotation speed (0-20Hz), on a small oscillation radius (~1cm). An improvement would be, the rotation starting at applied pressure and a time counter (seconds).

---

###Lab jack <a id="Lab-jack"></a>
![Lab_jack](https://cloud.githubusercontent.com/assets/17159617/13046343/827edd74-d3d8-11e5-84f0-1263bbbe179a.jpg)

Source: http://www.thingiverse.com/thing:925556

####1. Background
A lab jack is an adjustable lifting stage, for elevating other tools in the laboratory, such as bottles, stirrers, etc.

Keywords: lab, laboratory, scissor, jack, stand, adjustable, platform, lifting, stage

####2. Commercial variants
Depending on the size, weight capacity and maximum elevation, lab jacks come at different prices. A small 10x10 cm platform with a working elevation of 5-15cm, that can carry somewhat above 10kg, costs 50€ or more.

####3. Available DIY resources
There aren’t many DIY designs available, but the existing ones are perfectly fine for general laboratory use. As they are made of printable plastic, their weight carrying capacity may not be as high as for their commercial steel counterparts, but this also isn’t necessary most of the time. Here are [example 1](http://www.thingiverse.com/thing:28298), which can be upgraded with a stepper motor and automated for fine adjustment, and [example 2](http://www.thingiverse.com/thing:925556), which is 100% printable.

####4. Is DIY good enough and reasonable?
This piece of equipment already seems to be as good as it gets in its DIY form, optimization doesn’t seem necessary.

---


###Microliter pipette <a id="Microliter-pipette"></a>
![Pipette](https://cloud.githubusercontent.com/assets/17159617/13046467/4217254c-d3d9-11e5-814e-ab544e4bce91.jpg)

Source: http://www.gilsonuk.com/catalogue/product/itemNo/F123784

####1. Background
Pipettes are lab tools, capable of transfering precise volumes of liquids from one container to another. In biological and biochemical work, automatic microliter pipettes are most widely used, due to their high precision and the the range of general sample size.

Keywords: microliter, pipette, automatic, adjustable

####2. Commercial variants
The average “wetlab” user requires at least 3 microliter pipettes, one for each range of 1-10μl, 10-100μl and 100-1000μl. A single, cheap pipette costs 50€ or more, typically 200-300€ for popular brands. They allow an accuracy and precision of 0.1-1μl. Most models of different brands use the same standard sized tips, which are consumables and can be acquired cheaply.
In recent years, more electronic pipettes are also being developed, with programmable pipetting, which are however appropriately expensive.

####3. Available DIY resources
There are two designs for DIY pipettes available at the moment, [the adjustable volume pipette](http://www.instructables.com/id/3D-Printable-Adjustable-Volume-Pipette/?ALLSTEPS), [Biropette](http://www.thingiverse.com/thing:255519), both are 3D printable to a large part. Both seem to handle pipetting well, however, precision and accuracy can still be improved.

####4. Is DIY good enough and reasonable?
The Biropette seems quite precise and acurate already, however, both can be improved, also a wider range of adjustability should be introduced, possibly in the 3 stages common for commercial devices.

####5. Plan
For laboratory use, we suggest commercial pipettes, however, we will work on a reliable, precise and accurate design, that will remain 3D printable to the most part.

---

###pH meter <a id="pH-meter"></a>
![pH_meter](https://cloud.githubusercontent.com/assets/17159617/13046581/db39d5b2-d3d9-11e5-87e5-f2efafa7b4a1.jpg)
Source: http://www.wisegeek.org/what-is-the-ph-scale.htm

####1. Background
From all liquid analysis methods, pH-metry is probably the most widely used in biology and biochemistry. For preparational purposes, it is used for adjusting the pH of buffers and other solutions, which require specific properties, for biochemical reactions to take place.
Most commonly, the pH of a buffer, is adjusted by adding HCl or NaOH to a constantly stirred solution, while the pH value is measured.

Keywords: pH, meter, oxonium, hydrogen, ions, concentration

####2. Commercial variants
pH meters come in different forms, with various resolutions and accuracies. The cheapest variants are available for as little as 10€ (accuracy of pH 0,2), while lab-grade devices cost 300€ or more (accuracy of pH 0,01). The low-cost variants may just be sufficient for pools, or aquariums, they are probably not suitable for your laboratory. All devices require calibration solutions, which are used regularly and the process is all manual. A great chunk of the price is due to the quality of the sensor electrode.

While the devices contain sensing electrodes in the package, these can be bought separately and exchanged. They are available for 20-100€ and require care and maintenance to work properly.

####3. Available DIY resources
Many DIY projects can be found, ranging from those concentrating only on electronics, or complete devices, with various complexities and performances. In general, the devices are supposed to perform well, here are a few examples: The [Tiny pH meter](http://damien.douxchamps.net/elec/ph_meter/) is very accurate and has a good resolution, however, requires an additional (commercial/DIY) pH electrode. The same goes for the [simple pH meter](http://www.66pacific.com/ph/simplest_ph.aspx), which also shows good measurement performance and the [phduino](https://github.com/hephesto/phduino), which is an arduino based device. An example of a DIY system with a DIY electrode is found [here](http://www.instructables.com/id/cheap-DIY-electronic-pH-meter/?ALLSTEPS), the performance of the electrode itself is unknown. Similar instructions are found [here](https://noisebridge.net/wiki/BioBoard/Documentation/pH).

####4. Is DIY good enough and reasonable?
There are many DIY pH meters, which, at least with commercial electrodes, provide high quality measurements. The DIY electrodes on the other hand, would need to be tested in practice, to evaluate their performance. Nonetheless, even with commercial electrodes, pH meters leave a lot of room for improvement, especially for automation, long-time measurements,...

####5. Requirements and plans
The electronics will be assembled following the existing schematics, while experiments will be performed on the electrodes. Also, improvements for a wider applicability are planned. A pH meter should, with the assistance of calibration liquids, be capable of sensing the full pH range (1-14) of a solution, with a precision of 0,01.

---

###Ultrasonic bath <a id="Ultrasonic-bath"></a>
![ultrasonic_bath](https://cloud.githubusercontent.com/assets/17159617/13046696/aa958388-d3da-11e5-82e1-229f59757a1a.jpg)
Source: http://www.progensci.co.uk/page682/Laboratory-Equipment/Water-Baths/Ultrasonic-Baths/Clifton-Ultrasonic-Baths

####1. Background
Ultrasound baths are devices made for cleaning certain objects, such as jewlery, optical and surgical devices, etc. They have large transducer areas, which vibrate at ultrasonic frequencies (20-50kHz), that are transferred to a liquid and the contained samples and can break down brittle materials, but can also be used to degass liquids, mixing, etc.

Keywords: ultrasound, sonication, bath, cleaning

####2. Commercial variants
Commercial lab-grade ultrasonic baths, can cost from around 300, up to 1000€ for more sophisticated devices with heating.... They usualy contain a plastic basket, which protects the bath surface from damage, and have an adjustable sonication time, the frequency is however mostly fixed. Cheaper devices for the everyday consumer, with arguably the same performance, are however already available for 30-100€.

####3. Available DIY resources
There are a few DIY ultrasonic bath project plans available, [example 1](http://www.instructables.com/id/Home-Made-Ultrasonic-Cleaning-Tank/) and [example 2](http://archive.siliconchip.com.au/cms/A_112072/article.html), made from cooking pots. While these devices probably deliver satisfactory results, operatin at about 40kHz, same as the commercial devices.

####4. Is DIY good enough and reasonable?

It is questionable, whether it is reasonable to build a DIY ultrasound bath, since construction costs will be about the same as buying a cheap commercial device. This would probably depend on the experimental requirements, such as precise frequency, continer size and form,...

####5. Requirements and plans

For simple cleaning of glassware or utensils and degassing of liquids, cheap commercial devices are sufficient and would be our first choice, however, some experimentation on the DIY devices would be interesting, especially if these can be made cheaper, while more versatile. The important issue is the frequency (20-40kHz) and adjustable sonication time.

---


##Microscopy <a id="Microscopy"></a>
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
There are a few DIY microscopes available at the moment, which use the optics of available devices, such as web-cams ([example 1](http://hackteria.org/wiki/DIY_microscopy), [example 2](http://www.instructables.com/id/Save-money-on-your-DIY-laboratory-robust-easy-to-f/)), [smartphones](http://www.instructables.com/id/10-Smartphone-to-digital-microscope-conversion/), etc. These can come very cheap (if you already have a smartphone) and are suitable for simple microscopy, but it depends, whether, they will suit your needs.

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

---

##Spectroscopy <a id="Spectroscopy"></a>
work in progress...

<!---
###Title_name <a id="Title-name-no-spaces"></a>

####1. Background

Keywords: 

####2. Commercial variants

####3. Available DIY resources

![Name-of-displayed-image](images/image.jpg)

_"[Image title](http://..) by "[Image owner](http://..)" is licensed under [CC BY-NC-SA 4.0](http://openqcm.com/)_

####4. Is DIY good enough and reasonable?

####5. Plan
-->
