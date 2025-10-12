# Our Eyes in the Sky & On the Ground
For more information, refer to [NASA's article about Remote Sensing](https://www.earthdata.nasa.gov/learn/earth-observation-data-basics/remote-sensing).

## Intro to NASA & Remote Sensing

Remote sensing is the acquisition of information from a distance. This is done from airplanes, satellites, or other spacecraft. Both imagery and measurements are collected from the surface of the Earth.

This information can be used across many different research topics, including meteorology, oceanography, terrestrial ecology, geology, geography, and more. 

NASA is very involved with remote sensing since they have an array of space-based platforms in order to record information. They have 25 currently active Earth Observation satellites and dozens more inactive ones that have finished their missions. Their LANDSAT satellite program in partnership with the U.S. Geological Survey has been a pillar of land change data since the 1970s and since this data is open-source, has been used by people all over the world for research, business, and education.

## What do Satellites See? How Do Remote Sensing Satellites Work?

Remote Sensing Satellites observe and gather data from a distance, capturing electromagnetic radiation: ultraviolet, infrared, and visible wavelengths being reflected from Earth. Images will be taken simultaneously in multiple wavelengths using multispectral imaging. 

Multispectral imaging captures image data in specific wavelengths using either filters or instruments that are sensitive to particular wavelengths, drawing out latent information. Using different color filters, features like water, vegetation, soil, etc are distinctly emphasized in order for easier analysis. This distinction is possible because each feature reflects the light of a different wavelength under sunlight. 

![Electromagnetic spectrum](https://science.nasa.gov/wp-content/uploads/2023/04/intro_1-jpg.webp)

Image from [NASA Science](https://science.nasa.gov/ems/01_intro/)

## Typical Spectral Bands
Wavelengths are approximate and in parenthesis
- Blue (450-515nm) is used for atmosphere and deep water imaging, it can reach depths of up to 150 feet in clear water
Green (515/520-590/600nm) is used for imaging vegetation and deep water structures, reaching up to 90 feet in clear water
- Red (600/630-680/690nm) is used for imaging man-made objects, soil, vegetation, and water up to 30 feet.
- Near infrared or NIR (750-900nm) is used for imaging vegetation
- Mid-infrared or MIR (1550-1750nm) is used for imaging vegetation, soil moisture content, and some forest fires
- Far-infrared or FIR (2080-2350nm) is used for soil, moisture, geological features, silicates, clays, and fires.
- Thermal infrared (10,400-12,500nm) uses emitted radiation rather than reflected, it is used for geological structures,fires, night studies, and thermal differences in water currents.

## Spectral Band Usage & False Color

False colors are a group of color rendering methods in order to distinguish parts of the electromagnetic spectrum, both visible and invisible. A false-color image shows a scene in colors different from its original version.

- True-color only uses red,green, and blue channels. These are easy to understand for beginner analysts since they’re plain color photographs. This method is good for analyzing man-made objects.

- Green-red-infrared replaces the blue channel with near infrared, this is often used to detect vegetation.

- Blue-NIR-MIR is when the blue channel uses visible blue, green uses NIR so that vegetation stays green, and MIR is shown as red. This makes it so water depth, vegetation coverage, fire presence, and soil moisture content can be viewed in one image. 

## Resolution
Resolution of images plays a very big role in how data from an instrument can be used. There are four types of resolution to consider in datasets.

**Radiometric resolution** is the amount of information in each pixel, the number of bits representing energy recorded. Each bit records an exponent of base 2, meaning that the higher the radiometric resolution, the more values are available to store, allowing for better discrimination against energy differences (ex. Subtle differences in ocean color)

![Space Archaeology: In the Realm of Resolution](https://eoimages.gsfc.nasa.gov/images/imagerecords/91000/91071/selselah_oli_2017024.png)

[NASA Earth Observatory images by Joshua Stevens](https://www.visibleearth.nasa.gov/images/91071/space-archaeology-in-the-realm-of-resolution/91074w)

**Spatial resolution** is defined by the size of each pixel within a digital image and the area on Earth’s surface represented by that pixel. One pixel represents a specific area on the ground, the finer the resolution (the lower the number), the more detail visible. In the Moderate Resolution Imaging Spectroradiometer (MODIS) each pixel represents a 1km x 1km area with a spatial resolution of 250m or 500m.

![3 Landsat satellite images at 30m, 100m and 300m resolution](https://earthdata.nasa.gov/s3fs-public/styles/hds_large/public/2022-02/spatial_resolution.jpg)

Image from [NASA Earth Observatory](https://earthobservatory.nasa.gov/)

**Spectral resolution** is the ability of an instrument to discern finer wavelengths, having more and narrower bands. The narrower the range of a given band, the finer the spectral resolution. Many instruments are multispectral with 3-10 bands, while others are hyperspectral with thousands. Below, the Airborne Visible/Infrared Imaging Spectrometer (AVIRIS) has 224 spectral channels, distinctions are able to be made between rocks and minerals as well as vegetation types.
![A cube showing hyperspectral data depicting part of San Francisco](https://esto.nasa.gov/wp-content/uploads/2022/05/ImgSPEC_Image2.jpg)

Image from [NASA Jet Propulsion Laboratory](https://esto.nasa.gov/nasa-software-leverages-hyperspectral-data-to-better-understand-climate-change/)

**Temporal resolution** is the time that it takes for a space-based platform to complete an orbit and revisit an observation area depending on the orbit, the instrument’s individual characteristics, and the horizontal distance covering a satellite sensor. Polar orbiting platforms have temporal resolutions that vary from 1 to 16 days, a satellite with a temporal resolution of 16 days would be better for capturing bi-monthly changes rather than daily changes.
