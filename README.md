# **Handy ASR noise dataset**

A handy dataset for noise augmentations for ASR / TTS:
- ~20k noise files;
- ~200 distinct categories;

![](https://pics.spark-in.me/upload/c65cd3ef082bc035da000300e5b83eab.png)

Contact [us](mailto:open_stt@googlegroups.com)!
Open issues, collaborate, submit a PR, contribute, share your datasets!

## **Contribution ideas**

Add much more data from BBC Sound Effects dataset.

# **Download links**

Meta data [file](https://asr-noise.fra1.digitaloceanspaces.com/noises_df.feather) / 2.0M / `73cb528656a484b20e02d6c5fd05f14c`
Noise archive [file](https://asr-noise.fra1.digitaloceanspaces.com/asr_noises.tar.gz) / 4.7G / `5e069c867a0da891f57616905129b6c3`

**Open feather file:**
```
import pandas as pd

df = pd.read_feather(file_path)
```

# **Data preparation**

The dataset is compiled using open domain sources.
All labels resembling loud human speech were removed (but background noise, i.e. street chatter, was not removed).
All of the items are 0 - 60 seconds long.

![](https://pics.spark-in.me/upload/f935c54efed15bd40f1262d29b5dbbad.png)

All files are normalized as follows:
- Converted to mono, if necessary;
- Converted to 16 kHz sampling rate, if necessary;
- Stored as 16-bit integers;

# **Contacts**

Please contact us [here](mailto:open_stt@googlegroups.com) or just create a GitHub issue!

# **License**
cc-by

# **References / citations / licenses**

**Links / license**
- [rnnoise](https://people.xiph.org/~jm/demo/rnnoise/) / [CC0](https://creativecommons.org/publicdomain/zero/1.0/);
- [acoustic events](https://data.vision.ee.ethz.ch/cvl/ae_dataset/) / `if you end up using the dataset, we ask you to cite the following paper`;
- [urban sounds](urbansounddataset.weebly.com/urbansound8k.html) / [cc-by-nc](http://creativecommons.org/licenses/by-nc/3.0/);
- [esc-50](https://github.com/karoldvl/ESC-50) / [license](https://github.com/karoldvl/ESC-50/blob/master/LICENSE) (cc-by-nc);
- [freiburg-106](http://www.csc.kth.se/~jastork/pages/datasets.html) / ?;
- [sound-events](https://www.sciencedirect.com/science/article/abs/pii/S0167865515002925) / ?;
- [BBC Sound Effects](http://bbcsfx.acropolis.org.uk/) (a small part) / [license](https://github.com/bbcarchdev/Remarc/blob/master/doc/2016.09.27_RemArc_Content%20licence_Terms%20of%20Use_final.pdf);
- [nar dataset](https://team.inria.fr/perception/nard/) / `the data are freely accessible for scientific research purposes and for non-commercial applications`

**Paper citations:**
-  Naoya Takahashi, Michael Gygli, Beat Pfister and Luc Van Gool,"Deep Convolutional Neural Networks and Data Augmentation for Acoustic Event Recognition", Proc. Interspeech 2016, San Fransisco;
- J. Salamon, C. Jacoby and J. P. Bello, "A Dataset and Taxonomy for Urban Sound Research", 22nd ACM International Conference on Multimedia, Orlando USA, Nov. 2014;


# **Donations**

[Donate](https://buymeacoff.ee/8oneCIN) (each coffee pays for several full downloads) / use our DO referral [link](https://sohabr.net/habr/post/357748/) to help.

