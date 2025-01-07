# Stable FADING

* Stable version on [diffusers](https://github.com/huggingface/diffusers) of [FADING](https://github.com/MunchkinChen/FADING).
* Demo on [Kaggle notebook](https://www.kaggle.com/code/mrriandmstique/agetimelapse)

## 📢 Updates
- **2024-04-18**: Add stability about accelerate library
  - **Error**: is unexpected keyword `logging_dir` in `Accelerator`
  - **Reason**: occured in accelerate library mentioned in [issue #1559 in huggingface/accelerate](https://github.com/huggingface/accelerate/issues/1559)
  - **Solution** is following [muellerzr comment](https://github.com/huggingface/accelerate/issues/1559#issuecomment-1581556756)

- **2024-04-17**: Add stability about diffusers library version without downgrading
  - **Error**: is KeyError like `KeyError:'down_cross'` about upper version than diffusers 0.10.0.
  - **Mention**: was issued in [issue #2](https://github.com/MunchkinChen/FADING/issues/2).
  - **Reason**: occured in prompt2prompt library mentioned in [issue #57 in google/prompt-to-prompt](https://github.com/google/prompt-to-prompt/issues/57).
  - **Solution**: is following [anvilarth comments](https://github.com/google/prompt-to-prompt/issues/57#issuecomment-1613729431).

## 📑 Details
- For detailed instructions or training commands, please refer the [official repository](https://github.com/MunchkinChen/FADING).
