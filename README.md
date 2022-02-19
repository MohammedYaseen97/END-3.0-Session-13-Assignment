# END-3.0-Session-13-Assignment
Session 13 assignment of END 3.0 course of the School of AI

## Tasks Successfully Accomplished :
1. Created and ran the notebook instance on Sagemaker.
2. Changed the dataset from amazon_polarity to ag_news.
3. Requested for increase in training limit increase of notebook instances, and successfully launched training on another notebook instance.

## Unsolved Errors :
1. Training interrupted in between due to "unknown reason" - no solution on the web - tried a lot of different things like changing hyper-parameter names to call train.py, changing batch sizes, changing datasets. Really hard to debug errors in AWS.
```
UnexpectedStatusException: Error for Training job finetune-distilbert-base-cased-2022-02-19-16-56-02: Failed. Reason: AlgorithmError: ExecuteUserScriptError:
Command "/opt/conda/bin/python3.6 train.py --epochs 3 --model_name distilbert-base-cased --tokenizer_name distilbert-base-cased --train_batch_size 32"
```
2. Since training interrupted in between, couldn't deploy the model.


Video Link : https://youtu.be/vCGOouxXkxs
