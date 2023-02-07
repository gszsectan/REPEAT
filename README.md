# REPEAT 
The repo of ICSE 2023 paper "Keeping Pace with Ever-Increasing Data: Towards Continual Learning of Code Intelligence Models". We will also refactor our code for readability in a few weeks.

## Data
Our processed data can be downloaded [here](https://figshare.com/s/ae9265cb4aca00a71088)

## Code Summarization

Reproduce the results or our method and each baseline.
```bash
cd sum/CodeBERT or cd sum/CodeT5 
bash run_finetune.sh
bash run_emr.sh
bash run_ewc.sh
bash run_multitask.sh
bash run_ous.sh
```

## Vulnerability Detection

Reproduce the results or our method and each baseline.
```bash
cd svd/CodeBERT or cd svd/CodeT5 
bash run_finetune.sh
bash run_emr.sh
bash run_ewc.sh
bash run_multitask.sh
bash run_ous.sh
```

## Clone Detection

Reproduce the results or our method and each baseline.
```bash
cd clone/CodeBERT or cd clone/CodeT5 
bash run_finetune.sh
bash run_emr.sh
bash run_ewc.sh
bash run_multitask.sh
bash run_ous.sh
```


## Results
Our detailed experimental results and case study can be downloaded [here](https://figshare.com/s/cce5f2d9dced49a36d65)
