# pf-ICASSP-2024
The implementation of "Towards Partially Fake Audio Detection". The manuscript is under review.
 
We have uploaded our `score files` for the reviewers to reproduce our results from Table 4 and 5.

The rest of the code is being refined and will be available to the research community.

# USAGE

## Install the necessary libraries and packages
Please modify the `environment.yml` file accordingly (e.g., `file path` and `conda env` dir)

`conda env create -f environment.yml`

## Calculate Equal Error Rate (EER)
```
python calculate_EER.py --score-file score_files/se_resnet34_w2v2_eval_scores.txt \
                        --protocol-file protocol_files/PartialSpoof.LA.cm.eval.trl.txt
```
