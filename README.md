# Suspicion Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4

The implementation of "[Suspicion Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4]".

## Method

![figure](figures/counterfactual.png)
![figure](figures/SuspicionAgent.png)

![figure](figures/tom.png)



## Instruction

Install required packages with below command (python >= 3.8.5):

```
pip install -r requirements.txt
```

Set up the OpenAI key following [OPENAI_KEY](https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety)

Train and evaluate agents:

```
python main_vs_baseline.py --user --verbose_print  --rule_model [cfr/ nfsp / dqn / dmc]
```

## Sample Output

![figure](figures/Sample_second.png)
![figure](figures/Sample_Second_fold.png)
## Reference

```

```
Note: this code is based on the [SkyAGI](https://github.com/litanlitudan/skyagi). Many thanks to [the authors](https://github.com/litanlitudan/skyagi).
