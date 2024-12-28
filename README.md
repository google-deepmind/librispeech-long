# LibriSpeech-Long

**[Download audio, ground-truth transcripts, and per-file durations for all splits (3GB).](https://storage.googleapis.com/librispeech_long/v0_1.tar.gz)** 

This is a benchmark dataset for evaluating long-form variants of speech processing tasks such as speech continuation, speech recognition, and text-to-speech synthesis. It is derived from the [LibriSpeech](https://www.openslr.org/12) dev and test sets, whose utterances are reprocessed into contiguous examples of up to 4 minutes in length (in the manner of [LibriLight's `cut_by_vad.py` script](https://github.com/facebookresearch/libri-light/blob/main/data_preparation/cut_by_vad.py)).

**For more details:** see "Long-Form Speech Generation with Spoken Language Models" ([paper](https://arxiv.org/abs/2412.18603), [website](https://google.github.io/tacotron/publications/speechssm/)).

*This is part of a preprint that is work-in-progress; dataset may be subject to change.*

## Citation

When using this dataset, please cite the associated [paper](https://arxiv.org/abs/2412.18603):

```
@article{park2024long,
  author       = {Se Jin Park and
                  Julian Salazar and
                  Aren Jansen and
                  Keisuke Kinoshita and
                  Yong Man Ro and
                  R. J. Skerry{-}Ryan},
  title        = {Long-Form Speech Generation with Spoken Language Models},
  journal      = {CoRR},
  volume       = {abs/2412.18603},
  year         = {2024}
}
```

## License and disclaimer

Copyright 2024 DeepMind Technologies Limited

The software and materials, except for the underlying LibriSpeech data, are licensed under the Creative Commons Attribution 4.0 International License (CC-BY). You may obtain a copy of the CC-BY license at: https://creativecommons.org/licenses/by/4.0/legalcode, or in the LICENSE file.

The materials contain adapted material from the LibriSpeech dataset. LibriSpeech is also licensed under the Creative Commons Attribution 4.0 International License (CC-BY). You may obtain a copy of the CC-BY license at: https://creativecommons.org/licenses/by/4.0/legalcode, or in the LICENSE file. LibriSpeech is available at https://www.openslr.org/12 and created by Vassil Panayotov, Guoguo Chen, Daniel Povey and Sanjeev Khudanpur, pursuant to the paper “LibriSpeech: an ASR corpus based on public domain audio books", ICASSP 2015 (https://ieeexplore.ieee.org/document/7178964).

Unless required by applicable law or agreed to in writing, all software and materials distributed here under the CC-BY licenses are distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the licenses for the specific language governing permissions and limitations under those licenses.

This is not an official Google product.
