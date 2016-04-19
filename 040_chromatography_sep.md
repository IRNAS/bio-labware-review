##Chromatography (separation) <a id="chrom-sep"></a>

###Table of contents
- [Overview](000_bio-labware_overview.md)
- [General/wet preparation equipment](010_general_preparation.md)
- [Microscopy](020_microscopy.md)
- [Spectroscopy](030_spectroscopy.md)
- [Chromatography (separation)](#chrom-sep)
  * [High performace liquid chromatography (HPLC)](#HPLC)
  * [Gas chromatography (GC)](#GC)
  * [Gel electrophoresis](#Gel-electrophoresis)
- [Chromatography (detection)](050_chromatography_det.md)
- [Molecular Biology](060_molecular_biology.md)
- [Cell culture](070_cell_culture.md)
- [Electrophysiology](080_electrophysiology.md)
- [3D Bioprinting](090_3d_bioprint.md)
- [Various methods](100_various.md)

Chromatography is in general referred to as the set of techniques, used for the separation of different substances, based on their physical and chemical properties, such as size, polarity, charge, etc. Typically, this is achieved by placing a sample on a stationary solid phase, which is then rinsed by a mobile fluid phase, which the samples "ingredients" then follow. The flow rate of each component (and thereby separation) depends on its affinity for either phase and some other factors, such as porosity of the solid phase, flow rate of the liquid phase, etc. There are different techniques, which are categorized in many ways, depending on the form and shape of the solid phase (planar/column chromatography), the physical state of the mobile phase (liquid, gas), the separation mechanism, etc. Afterwards the sample is dried and visualized if neccessary.

A very simple form of chromatography is the so called thin layer chromatography (planar, liquid). A thin layer of solid phase (silicagel, alumina, cellulose,...) is evenly coated on a flat substrate. Then a sample is added and the mobile phase is applied by capillary forces (usually the thin film is placed into a container with mobile phase), which flows from one end of the thin layer, to the opposite one and the sample components follow it.


###High performance liquid chromatography <a id="HPLC"></a>

![chromatogram](https://upload.wikimedia.org/wikipedia/commons/6/69/Hplc-perfume-chromatogram.png)

Source: By Lukke - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=4867478

####1. Background
Liquid chromatography is most diverse and developed form of all, which is not surprising, since it offers a wide range of applicability both in preparation and analysis of chemical compounds. In general, a container (most often a column) is densely packed with stationary phase material, the sample is applied on top and then the mobile phase is added with a constant rate, to flow through the solid phase. Simple columnar liquid chromatography is always a DIY project (also see [flash chromatography](https://www.youtube.com/watch?v=fF1gXUvyGb4)), however, all required parts (phases, columns, fritts,...) are readily available. Such simple techniques however have their limitations and one of the most critical in molecular biology is sample size. Large columns are practically unusable with tiny amounts, since they often become to diluted to detect and are ultimately lost.

A more advanced method, which is capable of separating and detecting even the smallest samples, is the so called High performance liquid chromatography or HPLC. It  uses far more dense and thins columns with a more precisely adjusted stationary phase (premade columns) and forces the mobile phase through with a controlled pumping system at high pressures and adjustable flows. To sustain a reliable flow, the samples, and especially the mobile phase need to be filtered and degassed before application. The 
The pump allows mixing of different liquids and the creation of gradients, to improve separation performance. Many different combinations of columns and liquids are available today, which can be installed into the same device. Usually the system also integrates a detection system (which is also very variable, more in the [following chapter](#crom-det)), which produces typical chromatograms, used for sample identification.
Other methods of automation are also often included, such as a climate chamber for the column, an automatic sampler, or sample collector, etc.

Keywords: liquid, chromatography, high, performance, HPLC

####2. Commercial variants
Complete HPLC systems, containing a pump/mixer, degasser, autosampler, detector and fraction collector cost several 10k€, even used ones can be this expensive. It is possible to obtain separate parts and put them together manually, but that will still be very expensive. Single columns, which usually have a very narrow field of operation (reversed phase, ion exchange, hilic, etc.) usually also cost 500€ to a few 1000€. 

####3. Available DIY resources
In contrast to large column/flash chromatography, DIY construction of HPLC columns would probably prove very difficult to make, as it requires materials and procedures hard to come by (need very precise internal chemical composition and withstand large pressures). Also, the pumping needs to be very steady (without pulses) and allow mixing of different components. Little has been done on the development of DIY HPLC systems up to date, however, two examples could be found. [Example 1](http://waveandsignal.blogspot.si/) is a very simple, basic system, however, there is also the [portable LC system](http://www.rsc.org/images/loc/2012/pdf/T.4.111.pdf), which seems to be an exceptional piece of equipment. Instead of working with large pumping pressures and flows, it uses a microfluidic setup in combination with an electroosmotic pump and an electrochemical detector (see next chapter). It is very compact, can be powered by a battery and is thus portable, and is capable of effectively separating very similar substaces, such as epinephrine, norepinephrine and dopamine (which differ only in 1 to 2 functional groups.

####4. Is DIY good enough and reasonable?
DIY HPLC systems are indeed seriously lacking at the moment, despite the astronomical prices of commercial devices. Due to technical difficulties in the construction, DIY microfluidics could potentially play an important role in this endeavor. The portable LC system seems like a giant leap in this direction, but still offers room for improvement (exchangable columns for different applications, different detectors, etc.). On the other hand, open source chromatography analysis software, such as the [openchrom](https://www.openchrom.net/about) is readily available.

####5. Requirements and plans
DIY HPLC systems are surely to be developed in the future. The important characteristics, which have to be considered are good separation and sufficient detection, with the performance suitable for small samples (a few μl).


---



###Gas chromatography <a id="GC"></a>

![GC](https://upload.wikimedia.org/wikipedia/commons/c/c6/Gas_chromatograph-vector.svg)

https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Gas_chromatograph-vector.svg/1280px-Gas_chromatograph-vector.svg.png

Source: By Offnfopt - Own work created using File:Gas chromatograph.png as a reference., Public Domain, https://commons.wikimedia.org/w/index.php?curid=39498676

####1. Background
Instead of a liquid, as the name suggests, gas chromatography uses a gas (typically inert gases, such as Helium or Nitrogen) as the mobile phase. It is used for the separation of compounds, which can be nondestructively vaporized, or compounds, which are relatively volatile in general (gases, hydrocarbons, essential oils, alcohols, ethers, etc.). The column is usually a very long and thin tube, with the stationary phase being a film, coated on the inner wall of this tube. Polar coatings are used for the separation of polar substances and nonpolar coatings for nonpolar substances.

Keywords: gas, chromatography, volatile

####2. Commercial variants
GC systems are somewhat cheaper than HPLCs, however, they are still in the few 1k€ to 10k€ range. A system is composed of a carrier gas supply, the column, a sample injector, which allows the application of a sample into a steady gas flow and a detector. Also, the temperature of the whole column needs to be steady and controlable.

####3. Available DIY resources
There are a few online resources on DIY GCs, [example 1](https://experiment.com/projects/chromatogradiy-open-source-chromatography-effort), [example 2](http://www.scientistsolutions.com/forum/analytical-chemistry-chromatography/building-gc-fid) some are also fairly well documented, such as [example 1](http://nerdytoad.blogspot.si/2015/01/diy-gas-chromatograph.html). A great resource on GC optimization in general, can be found [here](http://www.chromatographytoday.com/articles/gc-mdgc-gc-ms/32/peter_morgan_anila_khan_tony_edge/optimisation_ofcolumn_parameters_in_gc/1575/).

####4. Is DIY good enough and reasonable?
How well the current models work is hard to say without building and testing the designs, since hardly any measurements were published together with the reports. In principle GC systems seem to be fairly simple to build and therefore seem reasonable (not including the detectors, which will be covered in a different chapter).

####5. Requirements and plans
The important issues in a GC system are: sustining a steady/controlable flow of the carrier gas and temperature of the column, appropriate column material an injector and an appropriate detector, often a flame ionization detector (FID), Mass spectrometer (MS), etc.


---



###Gel electrophoresis <a id="Gel-electrophoresis"></a>
![gel_electrophoresis](https://upload.wikimedia.org/wikipedia/commons/c/cb/PCR_gel_electrophoresis.jpg)

Source: By Rkalendar (Own work) [CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0)], via Wikimedia Commons

####1. Background
Gel electrophoresis is a separation method for large biomolecules, such as proteins or nucleic acids. An even and flat gel (stationary phase) with sample pockets, is placed into a buffer (mobile phase) and subjected to an electric current, which forces the buffer, allong with the samples through the gel. Different gel materials are used for different purposes. For proteins, usually acrylamide gel is used (in a technique called SDS-PAGE), for nucleic acids, typically agarose gel is used. While not used much anymore, it is also possible to make separation gels from partially hydrolized [starch](http://www.ithanet.eu/ithapedia/index.php/Protocol:Starch_gel_electrophoresis). It doesn't have the resolution power of other gel types, is however cheaper and less toxic for the environment. The exact method may vary for each material, however, in general, the following procedure is used:

Gel preparation and casting: 
The solutions for Acrylamide gels are typically cast inbetween two glass plates, separated by approx. 1mm thick spacers (teflon, silicone,...). This is done in 2 steps (first the separation gel and a stacking gel on top). This is a chemical polymerization process, which offers limited control, therefore the mixing and casting the gel needs to be fast and efficient.
Agarose gels are often cast directly into the electrophoresis chamber, and the sample pockets are created on the side. The polymerization is thermally regulated and the gel is first melted in a microwave, cast and cooled for polymerization.

Sample preparation and application:
The samples often require additional preparation, before they can be separated. Proteins for example, are denaturated and given a negative charge (achieved by sodium dodecylsulphate - SDS). The samples are mixed with a stained sample buffer, to follow the process during the run. The gels are placed (if not there already) into the electrophoresis chamber, which is filled with buffer and carefully, the samples are applied into the pockets. 

Separation and evaluation:
Current, voltage and time are set, then the separation begins and is finished, after the sample buffer has left the gel. To evaluate the separation, the samples are either visualized with light (DNA, using gel documentation), stained (Coomassie's staining for SDS-PAGE gels), or transfered by blotting and further processed.

Keywords: gel, electrophoresis, acrylamide, SDS-PAGE, agarose, starch

####2. Commercial variants
Commercially, different products are available, usually specialized for a single purpose. A gel electrophoresis system always requires a separation chamber (vertical - typicall for SDS-PAGE, or horizontal - for agarose gels) and a power supply, often also casting stand. The chambers alone can cost a few hundred €, the same goes for the power supply and casting stands. The required chemicals will cost a few dozen € as well. Interestingly, "ready to separate" gels in cassettes can be bought commercially, which require the trader's electrophoresis chamber and are more expensive on the long turn.

####3. Available DIY resources
For gel electrophoresis, there are currently several DIY projects available, ranging from [handmade chambers](http://citizensciencequarterly.com/2011/10/cheapass-science-gel-box/), to finished kits or even fully assembled - ready to go systems, with gel visualizations, as offered by [iorodeo](http://iorodeo.com/collections/gel-electrophoresis-and-imaging) and everything in between. A few examples, are [example 1](http://www.instructables.com/id/Gel-electrophoresis-system-mini/), [example 2](http://teach.genetics.utah.edu/content/labs/build_gel_box.pdf), [example 3](http://makezine.com/2013/10/19/make-a-gel-electrophoresis-power-supply/), etc. Interestingly, all of these were made for agarose gels and DNA analysis, none was for SDS-PAGE. However, power supplies are universal for this purpose and the chambers could probably be adapted for such gels with small modifications. Inevitably, one would also have to create a separate gel polymerization cassette acrylamied. This has to be done in a tight chamber, to reduce the ambient oxygen amount.

####4. Is DIY good enough and reasonable?
For agarose gels, the available DIY solutions seem on par with commercial devices, although, improvements are still possible, especially on the power supplies (monitor, precise adjustment of voltage, current and running time). On the other hand, a system for acrylamide or even starch gels is missing and would be a great addition to DIY electrophoresis. Another great improvement, especially for protein separation, would be 2D separation capabilities (size, isoelectric point).

####5. Requirements and plans
The requirements for gel electrophoresis are probably the same, as for any chromatography system: good separation, a broad range of samples which can be compared and control of the number and size of samples, flow rate, etc.
