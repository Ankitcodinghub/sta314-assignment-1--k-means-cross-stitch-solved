# sta314-assignment-1--k-means-cross-stitch-solved
**TO GET THIS SOLUTION VISIT:** [STA314 Assignment 1- k-means cross stitch Solved](https://www.ankitcodinghub.com/product/sta314-assignment-1-k-means-cross-stitch-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96405&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA314 Assignment 1- k-means cross stitch Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol start="0">
<li>Background: Making a cross-stitch pattern
Your task is to write several R functions that will take an image and create a cross-stitch pattern. This will include thread colour. There are a few challenges you need to get past:

<ol>
<li>Most images have too many colours to conveniently cross-stitch. You will need to use clustering to simplify the image.</li>
<li>Not every colour has an associated embroidery floss colour. The dmc package by Sharla Gelfand can be found at (https://github.com/sharlagelfand/dmc)[https://github.com/sharlagelfand/dmc] and will be useful for finding the nearest thread to a given colour. This package is not perfect (it is not vectorized and it throws occasional warnings), but it works.</li>
<li>You will need to help the user select how many threads they will use.</li>
<li>Most images have too many pixels to make a realistic cross-stitch. Use the provided function
change_resolution to change the resolution of an image in (x, y, cluster). The lower resolu- tion image will use the most common colour in the pixels that are being combined to get the aggregate colour. Note: Sometimes this function will drop a small cluster because it is never the most common cluster. That’s not an error.
</li>
<li>You need to make an actual pattern that people can use to do cross-stitch.</li>
<li>Some images have background colours that do not need to be covered in stitches. Your code should
allow for one of the clusters to be “background” and those entries in the pattern should be empty. 1
</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Below is a rough example of a 47 x 47 Liza Minnelli cross-stitch (image from the week 2 tutorial). One is in colour and the other is in black and white. Both use symbols to differentiate colours and grid lines to help read the pattern. The legend has both the name of the colour and the colour number. This is intentionally quite rough and should not be seen as the perfect example of a pattern! In particular, this example does not make use of the backing colour! The clustering that was used to make this pattern had 6 clusters, but after reducting the resolution, one of these clusters did not appear in the final picture.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Tasks

In this assignment, you are limited to using the following packages and base R

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
library(imager) library(tidyverse) library(tidymodels) library(sp) library(scales)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
library(cowplot) #devtools::install_github(“sharlagelfand/dmc”) library(dmc)

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Produce one R file called functions.R that contains the following functions:

<ol>
<li>cluster_info &lt;- process_image(image_file_name, k_list): • Input:
– image_file_name – a PNG or JPEG image.

– out – the number of centres in the clustering • Output:

– cluster_info: A list or tibble of information derived from the k_means that will be sufficient to be the input to any other function you write. This should be the only function that computes a clustering. This should include at least:

∗ the original output of the kclust calls,

∗ the tidied clusters, their associated RGB values and their nearest DMC thread colour

information.
</li>
<li>scree_plot(cluster_info):
• Produces and plots a scree plot.
</li>
<li>colour_strips(cluster_info) or color_strips(cluster_info):
• Produces colour strips with the DMC colour closest to the cluster centre colour.
</li>
<li>make_pattern(cluster_info, k, x_size, black_white = FALSE, background_colour = NULL):
• Plots the pattern. • Input:

<ul>
<li>– &nbsp;cluster_info – The output of process_image</li>
<li>– &nbsp;k – The chosen cluster size</li>
<li>– &nbsp;x_size – The (approximate) total number of possible stitches in the horizontal direction</li>
<li>– &nbsp;black_white – (logical) Print the pattern in black and white (TRUE) or colour (FALSE,
default)
</li>
<li>– &nbsp;background_colour – The colour of the background, which should not be stitched in the
pattern. (Default is to not have a colour) • Output:

– This function should be the only function to use change_resolution(image_df, x_size). It should produce a cross-stitch pattern that can be followed, complete with a legend that has thread colour, and a guide grid.
</li>
</ul>
</li>
</ol>
<ol start="2">
<li>All functions should be correctly documented.</li>
<li>Produce a vignette that demonstrates all the functions you have written. It should step the reader
through the entire process of producing a cross-stitch pattern from an image image you choose (see notes below). It should explain how to use each function, and interpret the output of each function. Special care should be shown to explaining how to use the scree plot and the colour strips to choose the number of clusters. This vignette should be self-contained and your target audience is a third year statistics student who has not done STA314 and is really into cross-stitch. This vignette must compile.
</li>
</ol>
Note on the image in the vignette: Firstly, the image can not be obscene, objectionable, or otherwise problematic.

Beyond that you have two major constraints:

<ul>
<li>The image should not be too high-resolution. The example I used was 1024 x 1024, which was fine. But this is not a great assignment to experiment with high-resolution images.</li>
<li>The image shouldn’t be too exciting or have a very busy background. Not every picture will make a good cross-stitch. You won’t be marked down for choosing a bad picture as long as the picture you choose is sufficient to explain the methods. (So, for an example, a picture that is only one or two colours wouldn’t be good enough.) The picture doesn’t need to be as simple as Liza, but it works best if there is just one main focus of the picture and not too much background.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
