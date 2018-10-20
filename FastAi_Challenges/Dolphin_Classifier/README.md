# Dolphin Species Classification

During my Postdoc and PhD, my labs worked with a lot of pictures of Australian dolphins. There are three mains species
+ Bottlenose dolphins (like flipper)
+ Snubfins (like weirdo belugas)
+ Humpback dolphins

Our main research tool was photo-ID: taking lots of pictures of individuals and tracking them in time by their unique markings. I wondered whether I could assist this process by at least segmenting out which pictures identifying which species. I downloaded a few images from Google images, and ran a pre-trained RESNET model (inspired by the FastAI course).

The RESNET model has learned low-level image features which are useful to learn higher-level objects (much like our own neurons attached to our eyes). Could this winning model transfer to help us learn to identify different species? YES! This is cool, because dolphins just kinda look like dolphins.

See the jupyter notebook file.

Enjoy!