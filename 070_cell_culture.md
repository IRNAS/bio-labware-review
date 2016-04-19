##Cell Culture

###Table of contents

- [Overview](000_bio-labware_overview.md)
- [Wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
- [Spectroscopy](030_spectroscopy.md)
- [Chromatography (Separation)](040_chromatography_sep.md)
- [Chromatography (detection)](050_chromatography_det.md)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](#Cell-culture)
  * [Warm water bath](#warm-water)
  * [Autoclave (sterilization)](#steril)
  * [Laminar flow hood](#lam-flow)
  * [Incubator](#incubator)
- [Electrophysiology](080_electrophysiology.md)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)


Biological research sooner or later leads to investigations on "living stuff". This can mean pure observation in nature, whole organism (multicellular) experiments in the lab, but with the development of molecular and growing techniques, also cell and tissue cultivation. Experimentation, especially on animals, where pain or suffering can be introduced, goes hand in hand with ethics and morality and it is essential to minimize the impact made on the experimental specimen. This is often regarded to as the rule of three Rs - reduction, replacement and refinement. Cell and tissue culture is an essential tool, not only to achieve this goal, but also to make experiments which would otherwise be impossible. Unless some very specific cell type is to be investigated, the cells typically do not require to be extracted separately, since standardized cell lines are already available all over the globe. To work with or modify these, however, a laboratory requires special registration and allowances.


###Warm water bath <a id="warm-water"></a>
![water_bath](http://image.made-in-china.com/45f3j00jTEQBsPlsUzK/Dk-2000-Iil-Thermostatic-Water-Bath-Lab-Water-Bath.jpg)

Source: http://faithful.en.made-in-china.com/product/YqrmWKgcgSpH/China-Dk-2000-Iil-Thermostatic-Water-Bath-Lab-Water-Bath.html

####1. Background
Some cells (especially animal cells) are very sensitive to environmental changes. To keep them well and healthy for cultivation and experimentation, everything needs to be just right. For example, liquids which are exchanged (growth medium) od added to the culture (enzymes or other molecules), need to have the same temperature as the incubated cells. Therefore, they are usually heated to the right temperature in a water bath. This is actually very straight forward, however, the temperature has to be just right, so it does not shock the cells, but also cannot be overcooked, since some of the contained molecules are sensitive to heat.

Keywords: warm, water, bath

####2. Commercial variants
Prices for warm water baths usually vary between 500 and 1000€, depending on the size, precision, etc.

####3. Available DIY resources
Interestingly, the existing "lab-grade" DIY warm water baths, mostly seem to come as adaptations of DIY slow cookers, such as [this one](https://learn.adafruit.com/sous-vide-powered-by-arduino-the-sous-viduino/). Two designs seem to do their job very well, which can be found [here](http://blog.labfab.cc/?p=47) and [here](http://makezine.com/projects/water-bath-thermostat/).

####4. Is DIY good enough and reasonable?
The existing models seem to be capable of setting and holding a constant temperature (+/- 0.5°C), which is good enough.

####5. Requirements and plans
Warm water baths need to finely adjust and hold the temperature of the contained water, which heats other objects inside. For the water to have an even temperature distribution it has to be continuously mixed.

---


###Autoclave (sterilization) <a id="steril"></a>
![autoclave](https://upload.wikimedia.org/wikipedia/commons/6/69/Autoclave_stove_top.jpg)

Source: By William Rafti of the William Rafti Institute, Attribution, https://commons.wikimedia.org/w/index.php?curid=18424292

####1. Background
When working with cells, tissues, the handling equipment, as well as the culture media, need to be sterile. There are many types of sterilization, using irradiation (such as UV, X-ray or gamma radiation), chemical agents (NO₂,Ethylene oxide,..), but most common in biological laboratories is sterilization with hot steam by autoclaving, which will be further discussed here.

Keywords: autoclave, moist, heat, steam, sterilization

####2. Commercial variants
Commercial, high end autoclaves with precise programmable settings (temperature, pressure, humidity) cost a few thousand €, although simple sterilization can be achieved with a simple pressure cooker.

####3. Available DIY resources
Despite many DIY Biologists, which require sterilization of their tools, using [pressure cookers](http://preparednessadvice.com/medical/improvised-autoclave-make-one-sterilize-medical-equip/) as an improvized solution, there are a few DIY construction designs. Two of the more advanced (and also not very cheap) can be found [here](http://www.sciencemadness.org/talk/viewthread.php?tid=14652#pid190003) and [here](https://www.shroomery.org/forums/showflat.php/Number/14182642). Due to its large size, the last one is even more expensive than used small commercial ones. This is, however, largely dependent on the needs one has for sterilization.

####4. Is DIY good enough and reasonable?
While using a simple pressure cooker for sterilization seems to suffice, build a self-regulating system from it should be simple and cheap enough, for the needs of most DIY biologists, enable them to sterilize more sensitive material. The existing DIY devices are promising, however made for specific purposes and not generally required.

####5. Requirements and plans
An autoclave should have the capabilities of preadjusted Temperature and pressure regulation, which is controlled by a feedback loop and a little electronics.

---


###Laminar flow hood / clean bench <a id="lam-flow"></a>
![uv-ontsmetting_laminaire-vloeikast](https://cloud.githubusercontent.com/assets/17159617/14281112/74c3409a-fb37-11e5-8bd4-d3fbc6a06871.JPG)

Source: By No machine-readable author provided. Own work assumed (based on copyright claims)., Public Domain, https://commons.wikimedia.org/w/index.php?curid=609576

####1. Background
In contrast to fume hoods, laminar flow hoods and clean benches are designed to protect samples, rather than the experimenter (though this is not mutually exclusive). Before air enters the chamber, it is filtered with a HEPA filter (highly efficient particle filter, which removes almost 100% of particles >0.3µm). Then it is directed in a laminar fashion through the interior of the chamber and outward. The exhaust is either in the front (where the eperimenter works), which is potentially dangerous, or travells through a porous mesh (working surface) and leaves the chamber on the same side, as it enters.

Keywords: laminar, flow, hood, cabinet, clean, bench

####2. Commercial variants
The prices of commercial laminar flow hoods vary, depending on their size, protection standard, etc. and can range from around 1000, to several 1000€.

####3. Available DIY resources
With increasing marihuana and especially fungi cultivation in the last years, the DIY equipment for sterile work seems to have developed quite a lot. Laminar flow hoods are a good example of this. Currently many DIY designs are available, using different airflow directions (horizontal: from back to front - the majority of DIY designs, or vertical: from top to bottom). Most designs are fairly simple. A few examples are: [a portable laminar flow hood](http://www.instructables.com/id/Portable-Laminar-Flow-Hood/), or this [somewhat more advanced design](http://fradnai.free.fr/docs/doc23.pdf) with a prefilter, both horizontal flow designs. Vertical flow designs include the simple [fresh cap DIY laminar flow hood](http://www.freshcapmushrooms.com/learn/keeping-it-clean-how-to-design-and-build-a-laminar-flow-hood) and the [design from the London Biohackspace](https://biohackspace.org/building-a-diy-flow-hood/). There is also a guide on calculating and determining the appropriate chamber size in regard to the blower and filter sizes, which can be found [here](https://mycotek.org/index.php?threads/evilmushroom666s-flowhood-build.49/).

####4. Is DIY good enough and reasonable?
Reducing the laminar flow hood to its parts (which really aren't so many) and assembling one by oneself, seems to drastically reduce costs and the example from the London Biohackspace seems to achieve aseptic conditions. Thus we can assume that the DIY systems are both good enough and reasonable.

####5. Requirements and plans
Laminar flow hoods are meant to protect the samples inside from particulate impurities, bacteria and fungi, which is accomplished by filtering the air, that enters the chamber. Since the chamber is also open on the side of the experimenter, any major turbulences in airflow could lead to the impurities entering from there. Therefore the airflow should be relatively slow (~0.5 m/s) and as laminar as possible. It is also beneficial to make the chamber from materials which are easy to clean and less likely to harbor growth of micro organisms.

---


###Incubator <a id="incubator"></a>
![inkubator](https://cloud.githubusercontent.com/assets/17159617/14281219/0cb8cbb8-fb38-11e5-9fc5-d4ff040c35c7.jpeg)

Source: http://www.thermoscientific.com/en/community/growth-passage.html

####1. Background
The function of an incubator seems very straightforward. It typically consists of a chamber used for the incubation of things, in molecular and cell biology mostly for cells, tissues and microorganisms. Many of these are very sensitive about their environmental conditions, which include chemical properties of their growth medium, but also temperature and ambient gas composition. The latter two can be adjusted in an incubator.

Keywords: incubator, incubation, chamber, cultivation

####2. Commercial variants
Incubators come in different froms and sizes and as a consequence - in different prices as well. They range from small egg (bird or reptile) warmers, to professional laboratory devices with an almost sterile environment, precise temperature and gas (CO₂) control etc. The latter kind is usually very expensive, costing several thousand €. Smaller, simple devices are available for a few hundred, or even below 100€ (hobby/terrarist grade).

####3. Available DIY resources
Typically, DIY incubators consist of a styrofoam chamber (with a door), heat source, temperature sensor and a regulation circuit, as shown in [this video](https://www.youtube.com/watch?v=X8hNb7m8tuw). A similar build was made by [Biodesign](http://biodesign.cc/2013/12/25/diy-incubator/), where also a compact temperature controller was developed - [Fermento](https://github.com/BioDesignRealWorld/Fermento). Both of these designs only include a temperature control. A more advanced device was devised at the Pelling Lab, where a [DIY CO₂ incubator](http://www.pellinglab.net/diy/diyco2incubator/) was developed, suitable for Mammalian cells.

####4. Is DIY good enough and reasonable?
Whether it is worthwhile to build a DIY incubator, very much depends on the characteristics you require. For simple nonsterile incubation at a constant temperature, cheap commercial devices seem a better choice. For sensitive eucaryotic cell line incubation, this is another matter completely! For such research, a DIY design is feasible, if you can achieve the neccessary conditions, e.g. as it was done in the Pelling lab.

####5. Requirements and plans
An incubator suitable for eucaryotic cell cultivation requires a chamber that is easily cleanable, with an airtightly sealable door/opening, precise temperature control, that can be adjusted and held constant and CO₂ regulation circuit that can sustain a 5% concentration.

---
