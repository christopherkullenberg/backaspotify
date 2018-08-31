# The Political Significance of Spotify - Anonymized data and source code

This repository contains the necessary code for reproducing most figures in Fleischer & Kullenberg (2018) "The Political Significance of Spotify in Sweden - Analysing the #backaspotify Campaign using Twitter Data", *Culture Unbound*, Vol, No.

Even though the Twitter data was retrieved from the public-facing Twitter API, it has been anonymized cryptographically (see Appendix). The usernames and user IDs have been replaced with hashsums and the content data (Twitter messages) have been disconnected into a separate file where it has been re-ordered to prevent the content data to be connected with the meta-data. 

The network visualization from the original article has been left out of this notebook since it requires content data and meta data to be connected. 

This notebook was written by Christopher Kullenberg, University of Gothenburg (christopher.kullenberg@gu.se) and is published using the MIT license (https://opensource.org/licenses/MIT). Feel free to reuse the code, but if you use it for academic publications, please cite the original article and/or this notebook.
