# Mini LLama SQL
## In Progress (Prio 2)

- Fine-tuning the LLama2-13b model on SQL, primarily to test if it can produce correct output with a larger model on a Colab GPU. 28GBs was the max amount of memory used for the notebook.  I used LoRA attention dimension of 32 to produce answers that would contain a correct answer.  In the future, may consider if decreasing this or using Mistral/Zephyr + increasing it will keep or increase answer quality while allowing this to run on a T4/V100.
- See detailed TODOS in nb (mainly on dataset/model choice)
- May consider reducing size to 2GB while retaining as much performance as possible
