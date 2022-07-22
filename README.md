# nnsvs_languages

Some `.hed` and `.table` files I've made for what I personally think is a good middle-ground for the language's coverage. Supported languages for now is English, Tagalog, and Japanese.

# How to Use

These files are made to be used for NNSVS/ENUNU as a file to dictate the language of the voicebank. I haven't actually calculated the needed parameters for these because [my Colab notebook](https://colab.research.google.com/drive/1vo-UxsFvp4PSUssCfkylh1cwwKsyH28Q?usp=sharing) automatically calculates these parameters.

# Language Guides

For now it'll only a be list of the phonemes. `br`, `pau` and `sil` are all present in each.

## Japanese

This phoneme system is based off of SynthV/CeVIO/Sinsy with added unvoiced vowels (the capital version)

**NOTE:** `cl` is considered a glottal stop in this hed file. It probably could still be used normally (in the context of Japanese gemination) but only for the stop consonants. It could probably be used for vocal fry as well.

`a`, `i`, `u`, `e`, `o`, `A`, `I`, `U`, `E`, `O`, `N`, `cl`, `t`, `d`, `s`, `sh`, `j`, `z`, `ts`, `k`, `g`, `h`, `b`, `p`, `f`, `ch`, `ry`, `ky`, `py`, `ny`, `hy`, `my`, `gy`, `by`, `n`, `m`, `r`, `w`, `v`, `y`

## English

This phoneme system is based off of ARPABET completely. `tr` and `dr` is the same as SynthV's.

`cl`, `m`, `n`, `ng`, `p`, `t`, `ch`, `k`, `b`, `d`, `jh`, `g`, `f`, `th`, `s`, `sh`, `hh`, `v`, `dh`, `z`, `zh`, `l`, `r`, `y`, `w`, `dr`, `tr`, `el`, `em`, `en`, `q`, `dx`, `aa`, `ae`, `ah`, `ao`, `aw`, `ax`, `ay`, `eh`, `er`, `ey`, `ih`, `iy`, `ow`, `oy`, `uh`, `uw`

## Tagalog

This phoneme system is based off of Tagalog orthrography. I think most of them makes sense but just in case, there's a phoneme chart at the bottom for the non-obvious ones.

`m`, `n`, `ng`, `p`, `t`, `ty`, `k`, `q`, `b`, `d`, `dy`, `g`, `s`, `sy`, `h`, `l`, `y`, `w`, `r`, `a`, `e`, `i`, `o`, `u`

Phoneme | X-SAMPA | IPA | Example Word (TGL) | Example Word (GenAmE)
 :---: | :---: | :---: | :---: | :---: 
 `ng` | `N` | `ŋ` | a**ng** | si**ng**
 `ty` | `tS` | `t͡ʃ` | ku**ts**ara, ku**ty**a | **ch**in
 `q` | `?` | `ʔ` | pag**-**ibig | uh**-**oh
 `dy` | `dZ` | `d͡ʒ` | **dy**aryo | **j**ob
 `sy` | `S` | `ʃ` | so**sy**al | **sh**are
 `r` | `4` | `ɾ` | pa**r**a | bu**tt**er
