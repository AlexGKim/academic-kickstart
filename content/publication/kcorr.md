+++
title = "A Generalized K Correction for Type IA Supernovae: Comparing R-band Photometry beyond z=0.2 with B, V, and R-band Nearby Photometry"

# Date first published.
date = "1996-02"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alex Kim", "Ariel Goobar", "Saul Perlmutter"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Publications of the Astronomical Society of the Pacific*. You may use *Markdown* for italics etc."
publication_short = "In *PASP*"

# Abstract and optional shortened version.
abstract = "Photometric measurements show that, as a group, nearby Type Ia supernovae follow similar light curves and reach similar peak magnitudes (Branch & Tammann 1992). Thus, these supernovae may serve as standard candles or calibrated candles at cosmological distances. Magnitudes of local and distant supernovae, both in the same filter band, are compared using a K correction to account for the different spectral regions incident on that filter. A generalized approach compares magnitudes in different bands for the nearby and distant supernovae, bands that are selected to give sensitivity in corresponding regions of the unredshifted and redshifted spectra. Thus, R magnitudes for supernovae at z ~ 0.5 are compared with $B$ magnitudes of local supernovae. We compute these generalized K corrections over a range of redshifts and bandpass pairs and discuss their advantages over the traditional single-band K correction. In particular, errors near maximum light can be kept below 0.05 mag out to at least z = 0.6, whereas the traditional K correction is less accurate and can be difficult to determine beyond z > 0.2."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://iopscience.iop.org/article/10.1086/133709/pdf"
url_preprint = "https://arxiv.org/pdf/astro-ph/9505024.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption 😄"

+++

When comparing the broad-band fluxes of low- and high-redshift objects, we have to account for the fact that observed filters are sensitive to different wavelength regions of the rest-frame emission.  If the redshift difference is large enough, it makes more sense to compare the blue-filter flux of a low-redshift object with the red-filter flux of a high-redshift object, then one also has to account for the different calubrations of the two filters.

# Fun facts

1. Every year for three years after the discovery of the expansion history of the universe, Peter Nugent and I would question whether our K-correction calculation was correct.  The subtlety is that CCD's are photon counters not bolometers, and the ratio of high- to low-redshift photon fluxes is higher than it is for energy fluxes.  This kind of error could make the Unvierse larger that it really is, the signature of an accelerating Universe!  After a week, we would come to the conclusion that we had calculated the K-corrections correctly.  Much later I told Peter that although I frequently questioned our results, I drew some confidence from the fact that the Hi-Z team also measured an accelerating Universe.  Peter says "I gave them and they used our K-corrections."  I guess we didn't independently discover dark energy.
2. After submitting the article, I get an e-mail from Brian Schmidt that the referee asked him to check my calculations but that he was unable to replicate them.  Brian sends me his filter transmission fucntions and in one the transmission efficiency at the central wavelength is set to zero.  Inconsistency resolved.  In Stockholm Brian confirms that he indeed was the referee.

