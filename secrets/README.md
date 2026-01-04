# Secrets (git-ignored)

Place local credentials here. This directory is ignored by git (except this README).

## Kaggle
- Put your `kaggle.json` here: `secrets/kaggle.json`
- Use it by setting: `KAGGLE_CONFIG_DIR=secrets`

Example:
- `KAGGLE_CONFIG_DIR=secrets kaggle competitions list`
