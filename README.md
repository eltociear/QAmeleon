QAmeleon introduces synthetic multilingual QA data contaning in 8 langauges using PaLM-540B, a large language model. This dataset was generated by prompt tuning PaLM with only five examples per language. We use the synthetic data to finetune downstream QA models leading to improved accuracy in comparison to English-only and translation-based baselines. 

Data available at https://storage.googleapis.com/qameleon/qamelon_pt_accepted.csv 


More details can be found in the [paper](https://arxiv.org/abs/2211.08264) which can be cited as follows:
```
@misc{agrawal2022qameleon,
      title={QAmeleon: Multilingual QA with Only 5 Examples}, 
      author={Priyanka Agrawal and Chris Alberti and Fantine Huot and Joshua Maynez and Ji Ma and Sebastian Ruder and Kuzman Ganchev and Dipanjan Das and Mirella Lapata},
      year={2022},
      eprint={2211.08264},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
This dataset contains a total of 47173 Question Answer instances across 8 langauges, following is the count per language. 

|Language | Count |
|---------|------:|
|ar       |6966   |
|bn       |6084   |
|fi    |5028 |
|id    |6797 |
|ko    |6471 |
|ru    |5557 |
|sw    |5597 |
|te    |4673 |
|**Total** |**47173**|

The QAmeleon dataset is released under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.
