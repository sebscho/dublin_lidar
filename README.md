# CUSP Hack Day: 12/2/17
* Name
* Name
* Name
* Name

# How might we automate identifying vegetation growth in Dublin? 

In the past six years, the UK has lost nearly 55,000 acres of green space due mostly to housing development. Green space is a keystone feature for undetstanding urban health and livibility. In addition to providing space for physical activity and social interaction, green space is a key feature in understanding climate change and city growth. In Dublin, new housing developments are also threatening urban vegetation. 

In 2015, NYU's Professor Laefer's research team released the largest lidar dataset ever, which covers a 1.5km square region of Dublin’s city center at 300 points per square meter. Using lidar technology, we have the ability to document how vegetation changes over time. LiDar helps us visualize not only the parks that have been eclipsed by new housing stock, but also how general open spaces and trees have grown. With this information, we can have an objective measure of green decline to point to in climate change discussions.   


### The data - Professor Debra Leafer’s data:
* [CUSPhack/Hack1-2017-8](https://github.com/CUSPhack/Hack1-2017-8)
* https://drive.google.com/a/nyu.edu/file/d/14wPI3dqB7Q_HEDN3DWeJQ90B1JvbwCh2/view?usp=sharing 

#### Lit review and resoursee
* [Statistic-based rapid change detection for remote sensing data 1](https://drive.google.com/a/nyu.edu/file/d/16ySD2MffZkYu-7BtpzeR49TXuiBuVZdE/view?usp=sharing) 
* [Statistic-based rapid change detection for remote sensing data 2](https://drive.google.com/a/nyu.edu/file/d/1kpEeU0qmeMCUfWG83WwwY6zxDiAHWuXQ/view?usp=sharing)
* [Characterization and Classification of Vegetation Canopy Structure and Distribution within the Great Smoky Mountains National Park Using LiDAR](http://ieeexplore.ieee.org/document/7395844/)

### The process
#### Install appropriate las packages to work with LAS data
* [libLAS documentation](https://pypi.python.org/pypi/libLAS)
#### Interpolation
* [RegularGridInterpolator](https://docs.scipy.org/doc/scipy-0.16.1/reference/generated/scipy.interpolate.RegularGridInterpolator.html)
#### Remove noise
* Smooth numpy arrays
#### Remove areas of no change
* 

#### Define threshold
* 

#### Visualize
* Look at our tree!


![LIDAR](LIDAR.png)
