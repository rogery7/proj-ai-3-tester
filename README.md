This project accomplishes 2 things:

1. Fine tunes a Hugging Face BERT model with a Cypress E2E dataset
2. Uses the fine tuned model to generate Cypress tests (though it current hallucinates)

Fine tuned model: https://huggingface.co/rogery7/bert-cypress

Fine tune results:

```
TrainOutput(
    global_step=375,
    training_loss=0.03491429901123047,
    metrics={
        'train_runtime': 226.9359,
        'train_samples_per_second': 13.22,
        'train_steps_per_second': 1.652,
        'total_flos': 789354427392000.0,
        'train_loss': 0.03491429901123047,
        'epoch': 3.0
    }
)
```
