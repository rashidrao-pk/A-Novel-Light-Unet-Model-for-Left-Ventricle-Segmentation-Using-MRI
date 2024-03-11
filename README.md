# A-Novel-Light-Unet-Model-for-Left-Ventricle-Segmentation-Using-MRI
This repository showcases a collaborative project between a PhD student from Pakistan and i played the role of a co-supervisor aimed at enhancing the Unet model for improved computational efficiency and performance. By simplifying the model's complexity and optimizing its architecture, we developed a Light-Unet model that outperformed traditional models. Additionally, a summary of the paper "<a href='https://www.mdpi.com/2227-7390/11/14/3245'>A Novel Light U-Net Model for Left Ventricle Segmentation Using MRI</a>" is included, highlighting the innovative approach to left ventricle segmentation with MRI images.
you can find Paper PDF on <a href='https://www.mdpi.com/2227-7390/11/14/3245'> MDPI website </a> and https://doi.org/10.3390/math11143245


<img src='figures/Main Model New.jpg'> 

### Authors: 

<!-- 
<ol>
<li>
    Mehreen Irshad<sup>1</sup> 
    [<a href='https://scholar.google.com/scholar?q=Mehreen%20Irshad'>Google Scholar</a>]
     
</li>
<li>
    Mussarat Yasmin <sup>1</sup>
    [<a href='https://scholar.google.com/scholar?q=Mussarat%20Yasmin'>Scholar</a>]
    
</li>
<li>
    Muhammad Imran Sharif <sup>1</sup>
    [<a href='https://orcid.org/0000-0002-4786-6579'> ORCID</a>,<a href='https://scholar.google.com/scholar?q=Muhammad%20Imran%20Sharif'>Scholar</a>,]
</li>
<li>
    Muhammad Rashid <sup>2</sup>
    [<a href='https://orcid.org/0000-0002-2557-6845'> ORCID</a>,<a href='https://scholar.google.com/scholar?q=Muhammad%20Rashid'>Scholar</a>,<a href='https://www.researchgate.net/profile/Muhammad-Rashid-65'> ResearchGate</a>]
</li>

<li>
Muhammad Irfan Sharif <sup>3</sup>
 [<a href='https://scholar.google.com/scholar?q=Muhammad%20Irfan%20Sharif'>Scholar</a>]
</li>
<li>
Seifedine Kadry <sup>4,5,6,7,*</sup>
 [<a href='https://scholar.google.com/scholar?q=Seifedine%20Kadry'>Scholar</a>]

</li>
</ol>
-->
| Author      | *Affiliation_ID* | Links     |
| :---        |    :----:   |          ---: |
| Mehreen Irshad <sup>1</sup>      | *1*       | <a href='https://scholar.google.com/scholar?q=Mehreen%20Irshad'>Google Scholar</a>   |
| Mussarat Yasmin <sup>1</sup> |  *1*   | <a href='https://scholar.google.com/scholar?q=Mussarat%20Yasmin'>Google Scholar</a>      |
| Muhammad Imran Sharif <sup>1</sup>   | *1*        | <a href='https://orcid.org/0000-0002-4786-6579'> ORCID</a>,<a href='https://scholar.google.com/scholar?q=Muhammad%20Imran%20Sharif'>Scholar</a>      |
| Muhammad Rashid <sup>2</sup>   | *2*        | <a href='https://orcid.org/0000-0002-2557-6845'> ORCID</a>,<a href='https://scholar.google.com/scholar?q=Muhammad%20Rashid'>Scholar</a>,<a href='https://www.researchgate.net/profile/Muhammad-Rashid-65'> ResearchGate</a>      |
| Muhammad Irfan Sharif <sup>3</sup>   | *3*        | <a href='https://scholar.google.com/scholar?q=Muhammad%20Irfan%20Sharif'>Scholar</a>      |
| Seifedine Kadry    | <sup>*4,5,6,7,** </sup>        | <a href='https://scholar.google.com/scholar?q=Seifedine%20Kadry'>Scholar</a>      |

| *Affiliation_ID*      | Affiliation |
| :---        |    :----:   |
| *1*        |   Department of Computer Science, COMSATS University Islamabad, Wah Campus, Wah Cantt 47010, Pakistan    |
| *2*        |   Department of Computer Science, University of Turin, 10124 Turin, Italy    |
| *3*        |   Department of Information Sciences, University of Education Lahore, Jauharabad Campus, Jauharabad 41200, Pakistan    |
| *4*        |   Department of Applied Data Science, Noroff University College, 4612 Kristiansand, Norway    |
| *5*        |   Artificial Intelligence Research Center (AIRC), Ajman University, Ajman P.O. Box 346, United Arab Emirates    |
| *6*        |   Department of Electrical and Computer Engineering, Lebanese American University, Byblos 13-5053, Lebanon    |
| *7*        |   MEU Research Unit, Middle East University, Amman 11831, Jordan    |

### Netwrok Composition
<img src='figures/Network Composition.jpg'>

### Contributions:
An image normalization method is performed prior to processing. The efficiencies of the proposed algorithm are strongly impacted by the enhancement of image contrast. Improving an image’s contrast is surely a prerequisite for image processing.
Intelligent Contrast Stretching and Histogram Equalization improves an image that has already undergone preprocessing with unsharp masking.
The Encoder path implanted layers with convolutional blocks and reducing the batch layer while in next layer removing the activation layer as well.
Afterward, up-sampling enlarges the feature batch back to its actual size. The significant contribution of the proposed technique is to provide 99% precise results of the epicardium layer.
The test dataset includes LVOT (Left Ventricle Outflow Tract) images of both endocardium and epicardium.
An analytic overview of previous research is depicted in further segments. Then, the novel contribution is introduced as an intelligent image enhancement technique that will not apply to all images from the dataset but only to the low-contrast images, which require preprocessing. Afterward, a novel deep learning model which utilizes the stock U-Net model as the backbone and is optimized to a lightweight model is mentioned along with its results and analytical discussion.

### Data Availability Statement
Publicly available dataset is used for evaluation that can be accessed from the link: https://sourceforge.net/projects/cardiac-mr/files/.

### Cite Us
<a href='mathematics-v11-i14_20240311.bib'>Bibtex for citation </a> <br>
```
@Article{math11143245,
AUTHOR = {Irshad, Mehreen and Yasmin, Mussarat and Sharif, Muhammad Imran and Rashid, Muhammad and Sharif, Muhammad Irfan and Kadry, Seifedine},
TITLE = {A Novel Light U-Net Model for Left Ventricle Segmentation Using MRI},
JOURNAL = {Mathematics},
VOLUME = {11},
YEAR = {2023},
NUMBER = {14},
ARTICLE-NUMBER = {3245},
URL = {https://www.mdpi.com/2227-7390/11/14/3245},
ISSN = {2227-7390},
DOI = {10.3390/math11143245}
}