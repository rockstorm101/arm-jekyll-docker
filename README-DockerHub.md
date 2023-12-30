# Jekyll on Docker ARM
![Version][b1]

Clone of the [official Jekyll image][1] built for ARM and other
platforms. Sadly, I will not maintain this repository:
 * The Docker image for Jekyll is unmaintained upstream (almost 2 years dead
   now)
 * I prefer an approach where one uses customized Docker images for each
   individual blog/site, which feels much more efficient. See
   https://github.com/rockstorm101/jekyll-docker.

[1]: https://github.com/envygeeks/jekyll-docker

## Supported Tags and Variants

 * **X.Y.Z**: Default image with a standard set of packages. (Corresponding to
    `jekyll/jekyll`)
 * X.Y.Z **-minimal**: Standard image without any extra gems or
    packages. (Corresponding to `jekyll/minimal`)
 * X.Y.Z **-builder**: Packs extra stuff not included in the standard image
    like Git or SSH. (Corresponding to `jekyll/builder`)
 * **pages-vX**: Contains Jekyll configured as used by [GitHub
    Pages][5]. Corresponding Jekyll version and gems are [listed here][6].
	
More information on variant content and usage in the [official image
documentation][10].
  
[5]: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll
[6]: https://pages.github.com/versions/
[10]: https://github.com/envygeeks/jekyll-docker#image-types


[b1]: https://img.shields.io/docker/v/rockstorm/jekyll/latest
