# Dolphin Species Classification

During my Postdoc and PhD, my labs worked with a lot of pictures of Australian dolphins. There are three mains species
+ Bottlenose dolphins (like flipper)
+ Snubfins (like weirdo belugas)
+ Humpback dolphins

![snub](https://raw.githubusercontent.com/faraway1nspace/DataChallenges/master/FastAi_Challenges/Dolphin_Classifier/data/dolphins/train/snubfin/snubfin.11.jpg)
![tursiops](https://raw.githubusercontent.com/faraway1nspace/DataChallenges/master/FastAi_Challenges/Dolphin_Classifier/data/dolphins/train/humpbac/humpbac.17.jpg)


Our main research tool was photo-ID: taking lots of pictures of individuals and tracking them in time by their unique markings. I wondered whether I could assist this process by at least segmenting out which pictures identifying which species. I downloaded a few images from Google images, and ran a pre-trained RESNET model (inspired by the FastAI course).

The RESNET model has learned low-level image features which are useful to learn higher-level objects (much like our own neurons attached to our eyes). Could this winning model transfer to help us learn to identify different species? YES! This is cool, because dolphins just kinda look like dolphins.

See the jupyter notebook file.

## Conclusions
+ there is high confusion between bottlenose and humpbacks
+ snubies are well defined
+ some of the confused images are due to idiosyncratic corruptions to the images (watermarks, dead animal)
+ for this dataset, the pretrain deep features seemed better than learning deep features on a small dataset.

Enjoy!