Uses matplotlib to generate xkcd sketch style plots


# Plotting in xkcd Style
Matplotlib offers an xkcd sketch style drawing option.  If you don't know the xkcd web comic, you can check it out here:

https://xkcd.com

Matplotlib also has a gallery of examples here.

https://matplotlib.org/xkcd/gallery.html

Although this functionality has been available for [quite a while](http://jakevdp.github.io/blog/2013/07/10/XKCD-plots-in-matplotlib/), I wanted to experiment with it myself!  Below, I plot how the 800 meter world record has improved over time.

# Setup

Make sure you have "Comic Sans" installed.  If you don't, you will want to install it
```
sudo apt-get update
sudo apt-get install fonts-humor-sans
```
After installing a new font, you will likely need to refresh the font cache.
```
>>> import matplotlib.font_manager                                                   
>>> matplotlib.font_manager._rebuild()
```

# Plots

![](xkcd_theme-men_800m_world_record_progression.png)

![](xkcd_theme-women_800m_world_record_progression.png)

