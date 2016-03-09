# NP-szeged-msd-model

Binary model files for [Huntag3](https://github.com/ppke-nlpg/HunTag3) for Hungarian Noun Phrase (NP) chunking.

Trained on *Szeged Treebank 2.0* NP annotations (MSD PoS-tags, NE tokens joined together with underscore character). Training data and scripts to re-run training are included.

Created for Huntag3 inside the [GATE Hungarian plugin](https://github.com/dlt-rilmta/hunlp-GATE). The **`"Huntag3 Hungarian NP-chunker [msd] (command-line)"`** processing resource (`hu.nytud.gate.othertaggers.Huntag3NPChunkerCommandLine`) requires this model.

**How to install for the GATE Hungarian plugin**

You will need to install [git-lfs](https://git-lfs.github.com/) to clone this repository. Then change to `{YOUR_GATE_PLUGINS_FOLDER}/Lang_Hungarian/resources/huntag3/models/` and issue the following command:

```git clone https://github.com/dlt-rilmta/NP-szeged-msd-model.git```

*Maintainer*: Márton Miháltz <mmihaltz@gmail.com>
