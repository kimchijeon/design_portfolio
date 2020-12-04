---
Title: Page Speed Report
Description: Report for Kmom05
---
Page Speed Analysis
=======================

This analysis aims to evaluate the page speed of three different websites. The goal is to measure how fast the website is loaded in and whether or not there are aspects which could be improved in terms of page speed and usability.

Sample
-----------------------

For this analysis the websites chosen are the websites of three big art museums. These are [Nationalmuseum](https://www.nationalmuseum.se/), [the Louvre](https://www.louvre.fr/en) and [The National Gallery](https://www.nationalgallery.org.uk/).

The choice to analyze art museums was made partly because of my own professional experience with museums, but more importantly because these museums exhibit art which inevitably generates websites that include a lot of imagery. Since images account for about 60% of the bytes needed on average to load a webpage[^1], I thought this would make for an interesting analysis.

All three museums selected for this analysis are popular and well established art museums. I also decided to choose museums in Europe since they are more familiar to me.

Method
-----------------------
For the sake of uniformity, three similar webpages have been measured per website. These are the homepage, the exhibitions page and the visit information page.

In this analysis the definition of page speed is the **page load time**, i.e. the time needed to display the content on the page[^2].

The measurement of the websites' page speed has been done with both [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) and the Firefox Devtools. 

Using the Google PageSpeed tool, the performance scoring for both mobile and desktop versions have been noted. Measurements were done three times per webpage to get an average. The scoring is based on a maximum of 100. A scoring of 0-49 is low, 50-89 is medium and 90-100 is high.

Using the Devtools the page speed, number of resources loaded and the total transferred size of the webpage have been noted and compiled into [this Google Sheets document](https://docs.google.com/spreadsheets/d/1WuCjuOo9gMf8OpdqvQ16q3sCCQuSFfdCtAhXtDLhOqQ/edit?usp=sharing). The webpage was measured three times and averages have been calculated.

Results
-----------------------

### Nationalmuseum
[![Screenshot of Nationalmuseum Webpage, 2020-12-02](%base_url%/image/nationalmuseum_screenshot_201202.png?w=857){.screenshot}](%base_url%/image/nationalmuseum_screenshot_201202.png "Click for full size")

#### Pages measured
The pages measured on the Nationalmuseum website are [Homepage](https://www.nationalmuseum.se/), [Exhibitions](https://www.nationalmuseum.se/utst%C3%A4llningar) and [Visit](https://www.nationalmuseum.se/bes%C3%B6k-museet).

#### Average Google PageSpeed Insights Scoring
<table>
    <tr>
        <th colspan="2">Homepage</th>
        <th colspan="2">Exhibitions</th>
        <th colspan="2">Visit</th>
    </tr>
    <tr>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
    </tr>
    <tr>
        <td>15,33</td>
        <td>58,33</td>
        <td>26,33</td>
        <td>65</td>
        <td>22</td>
        <td>68,67</td>
    </tr>
</table>

#### Average page speed (seconds)

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>2,47</td>
        <td>2,96</td>
        <td>3,85</td>
    </tr>
</table>

#### Average number of resources loaded

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>56</td>
        <td>56,67</td>
        <td>51</td>
    </tr>
</table>

#### Average total transferred size (MB)
<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>5,88</td>
        <td>5,54</td>
        <td>4,78</td>
    </tr>
</table>

#### Total average of the webpages
<table>
    <tr>
        <th>Performance scoring Mobile</th>
        <th>Performance scoring Desktop</th>
        <th>Page speed (s)</th>
        <th>Resources (n)</th>
        <th>Size (MB)</th>
    </tr>
    <tr>
        <td>21,22</td>
        <td>64</td>
        <td>3,10</td>
        <td>54,56</td>
        <td>5,40</td>
    </tr>
</table>

Nationalmuseum scores on a whole quite low using PageSpeed Insights. There is definitely areas of improvement especially for their mobile version.

It seems like Nationalmuseum loads in relatively few resources and yet has a high total size. This indicates that they should perhaps look over how they could use their resources more efficiently, especially images. This could probably also improve their page speed.

### The Louvre
[![Screenshot of the Louvre Webpage, 2020-12-02](%base_url%/image/louvre_screenshot_201202.png?w=857){.screenshot}](%base_url%/image/louvre_screenshot_201202.png "Click for full size")

#### Pages measured
Here are the pages measured on the Louvre website: [Homepage](https://www.louvre.fr/en), [Exhibitions](https://www.louvre.fr/en/expositions) and [Visit](https://www.louvre.fr/en/hours-admission-directions).

#### Google PageSpeed Insights Scoring
<table>
    <tr>
        <th colspan="2">Homepage</th>
        <th colspan="2">Exhibitions</th>
        <th colspan="2">Visit</th>
    </tr>
    <tr>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
    </tr>
    <tr>
        <td>55,33</td>
        <td>82,67</td>
        <td>60,33</td>
        <td>89,33</td>
        <td>69</td>
        <td>93,33</td>
    </tr>
</table>

#### Average page speed (seconds)

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>2,32</td>
        <td>1,80</td>
        <td>1,82</td>
    </tr>
</table>

#### Average number of resources loaded

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>84,67</td>
        <td>73,33</td>
        <td>75,33</td>
    </tr>
</table>

#### Average total transferred size (MB)
<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>2,58</td>
        <td>1,58</td>
        <td>1,26</td>
    </tr>
</table>

#### Total average of the webpages
<table>
    <tr>
        <th>Performance scoring Mobile</th>
        <th>Performance scoring Desktop</th>
        <th>Page speed (s)</th>
        <th>Resources (n)</th>
        <th>Size (MB)</th>
    </tr>
    <tr>
        <td>61,56</td>
        <td>88,44</td>
        <td>1,98</td>
        <td>77,78</td>
        <td>1,80</td>
    </tr>
</table>

The Louvre's website scores in general above average using PageSpeed Insights. The desktop version especially earns quite high scores. The mobile version gets just about medium which suggests improvements in this aspect, similar to Nationalmuseum but not to the same extent.

The website loads in quite a few resources but still manages to keep the size below 2 MB, which is very impressive. They have managed their resources well to minimise the size and increase page speed, but one could argue whether or not the drop in image quality is worth it (the logo for example is visibly low res).

### The National Gallery
[![Screenshot of The National Gallery Webpage, 2020-12-02](%base_url%/image/nationalgallery_screenshot_201202.png?w=857){.screenshot}](%base_url%/image/nationalgallery_screenshot_201202.png "Click for full size")

#### Pages measured
The pages measured on the National Gallery website are [Homepage](https://www.nationalgallery.org.uk/), [Exhibitions](https://www.nationalgallery.org.uk/exhibitions) and [Visit](https://www.nationalgallery.org.uk/visiting/plan-your-visit).

#### Google PageSpeed Insights Scoring
<table>
    <tr>
        <th colspan="2">Homepage</th>
        <th colspan="2">Exhibitions</th>
        <th colspan="2">Visit</th>
    </tr>
    <tr>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
        <td>Mobile</td>
        <td>Desktop</td>
    </tr>
    <tr>
        <td>57,33</td>
        <td>89,33</td>
        <td>54</td>
        <td>77,33</td>
        <td>61,67</td>
        <td>96</td>
    </tr>
</table>

#### Average page speed (seconds)

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>2,85</td>
        <td>6,03</td>
        <td>2,73</td>
    </tr>
</table>

#### Average number of resources loaded

<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>77</td>
        <td>76,67</td>
        <td>107</td>
    </tr>
</table>

#### Average total transferred size (MB)
<table>
    <tr>
        <th>Homepage</th>
        <th>Exhibitions</th>
        <th>Visit</th>
    </tr>
    <tr>
        <td>2,48</td>
        <td>4,74</td>
        <td>1,87</td>
    </tr>
</table>

#### Total average of the webpages
<table>
    <tr>
        <th>Performance scoring Mobile</th>
        <th>Performance scoring Desktop</th>
        <th>Page speed (s)</th>
        <th>Resources (n)</th>
        <th>Size (MB)</th>
    </tr>
    <tr>
        <td>57,67</td>
        <td>87,56</td>
        <td>3,87</td>
        <td>86,89</td>
        <td>3,03</td>
    </tr>
</table>

The National Gallery's website scores just about the same as the Louvre's by PageSpeed Insights, but not quite as well. Here there is room for improvement for the mobile version in particular too.

Out of the three websites, the National Gallery has the lowest page speed (i.e. highest loading time), but considering that they also have the highest number of resources this can be understandable. What is notable though is that despite the significantly higher number of resources, the National Gallery has a smaller total size than Nationalmuseum, indicating good management and compression of resources.

Analysis
-----------------------

In general, the websites evaluated in this analysis seem to end on a very average ranking, or above average at the most, in terms of page speed. Although Nationalmuseum seems to be in a bigger need of improvement than the Louvre and the National Gallery, who both manage to get high performance scores on their desktop versions, they are all in want of some improvement.

The average page speeds are all above 2 seconds, except for the Louvre who *just* manages to get under it. In general, a good page speed is considered to be 2 seconds or lower, as recommended by Google, where they even aim for *under a half second*[^3]. With this as a benchmark, one can see that the sample websites in this analysis barely make the cut.

Now, the Louvre manages to stay under the 2 second threshold, but at the cost of image quality, while Nationalmuseum and the National Gallery manage to keep their images on a good enough quality, but let the page speed suffer instead. The key is to find a balance between "looking good and being light"[^4], so that neither is lacking.

Improvements suggested by PageSpeed Insights for all three websites is better image management, which isn't strange since these are the websites of three art museums, thus using a lot of imagery. Nationalmuseum need to start using more appropriate sizes, the Louvre could use some lazy loading of images and the National Gallery are suggested to use more modern image formats.

In terms of usability all three websites have a lot to work with considering how their mobile versions are all just average or below average.

### Conclusion
In my opinion, the Louvre has the most efficient website, but lacks in aesthetic appeal. Nationalmuseum makes use of lovely imagery and exceptional color work but has a lot of improvement to do in terms of resource management.

The National Gallery has done very well considering the high number of resources used but low total size. Despite the lower page speed they really manage to make use of their content to create a visually pleasing and captivating website that is still efficient enough. The National Gallery's website is balanced enough for me to declare this the best of the three in this analysis.

Appendix
-----------------------

This analysis report was made by Jenny Phan.

[^1]: LePage, Pete. 2020. Responsive Images. *Google Developers*. [https://developers.google.com/web/fundamentals/design-and-ux/responsive/images](https://developers.google.com/web/fundamentals/design-and-ux/responsive/images). (2020-12-02).

[^2]: Moz. Page Speed. *Moz.com*. [https://moz.com/learn/seo/page-speed](https://moz.com/learn/seo/page-speed). (2020-12-02).

[^3]: Ohye, Maile. 2010. Site Performance For Webmasters. *Official Google Search Central YouTube channel*. [https://www.youtube.com/watch?v=OpMfx_Zie2g&feature=youtu.be&t=567](https://www.youtube.com/watch?v=OpMfx_Zie2g&feature=youtu.be&t=567). (2020-12-02).

[^4]: CSS Tricks. A Guide to the Responsive Images Syntax in HTML. *Css-tricks.com*. [https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/). (2020-12-02).

<a class="arrow-up" href="?"><i class="fas fa-arrow-circle-up"></i></a>