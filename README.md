
# Deep Learning Detection and Classification of Wheat Heads to Estimate Yield

Please find notebooks for data EDA and for both models on my kaggle page: https://www.kaggle.com/ottiliemitchell/notebooks




## Background
Wheat is a core cereal that is relied on around the world in our diet. In the 1920s wheat breeding was introduced to increase yields and to build immunity against disease (David et al., 2020).

Wheat's popularity as a staple food product, has meant that farmers globally have had to grow different varieties to suit their growing conditions. This is vital for food security to ensure successful harvests. Breeding has significantly increased yields, however, this rate of increase has plateaued since the early 1990s (Brisson et al., 2010). Farmers now need to look at other ways to increase and estimate wheat yields.

Demand for high yielding wheat has initiated wide research, with the creation of a large database, including a set of images which will be studied in this investigation. The images are made up of "wheat heads" which are the spikes at the top of the plant's stem. The wheat head holds the plant's nutrition and is harvested and processed into cereal for food consumption. It would be of benefit to farmers if they were able to estimate the density and size of the wheat heads to predict wheat yields.

With the advance in GPU performance, deep learning has become more accessable to individuals as well as institutions to perform object detection on large datasets (Alom et al., 2019). Although deep learning can be an accurate way to look at large datasets, it can come with limitations. As the images are taken of wheat fields outside, images are often distorted or blury, with movement in the wind. Also, different varieties, at different growth stages and the orientation of wheat heads can appear differently. This can make it more challenging to identify single wheat heads.

The Global Wheat Head data is led by 9 research institutions from across the world, with the joint ambition of accurately detecting wheat heads. These institutions include The University of Tokyo, Institut National de Researche pour L'Agriculture, L'Alimentation et L'Environment, Arvalis, ETHZ, University of Saskatchewan, University of Queensland, Nanjing Agricultural University and Rothamsted Research.

## Problem outline
The accurate classification and detection of wheat heads would give farmers an invaluable tool in the prediction of wheat yields. Using the Global Wheat Head data, this study will attempt to successfully identify the location of wheat heads within provided images.
