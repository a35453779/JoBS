# JoBS

1. Unzip JoBS.zip to current directory.
2. `pip3 install -r requirements.txt`
3. Go to `commands_BO_full_SL_predictor.sh` - and adjust `tasks=("commonsense_qa")` to your desired evaluation task.
4. Run `bash commands_BO_full_SL_predictor.sh` to run JoBS to optimization both data and model configurations.
5. Results will be printed and stored in the result directory.
