# FADING_stable

*stable-version about diffusers-library of FADING based on [official FADING repository by MunchkinChen](https://github.com/MunchkinChen/FADING)*

## 🔥 Updates
- 24-04-17 : Add stability about diffusers library version without downgrading
  - Error : is KeyError like `KeyError:'down_cross'` about upper version than diffusers 0.10.0.
  - Mention : was issued in [issue #2](https://github.com/MunchkinChen/FADING/issues/2).
  - Reason : occured in prompt2prompt library mentioned in [issue #57](https://github.com/google/prompt-to-prompt/issues/57#issuecomment-1613729431).
  - Solution : is following [anvilarth comments](https://github.com/google/prompt-to-prompt/issues/57#issuecomment-1613729431).

## 🤗 Run FADING with FFHQ sample:

### 01. Downlaod pre-trained model

Download release weigths from official repository [here](https://github.com/MunchkinChen/FADING#available-pretrained-weights), and unzip the downloaded zip file.

Unzipped folder should be located as:
```
FADING-stable
├───finetune_double_prompt_150_random # this is unzipped pre-trained model folder
...
```

### 02. Run face editing

For test, all the things (input image, target age, gender and so on) is pre-allocated in shell file. You can easily run FADING with prepared code as:

```
sh run_FADING.sh
```

### 03. Outputs

you can see the results in `./output_samples/[FILE_NAME]_[TARGET_AGE].png`


## ETC

For details, please refer the [official repository](https://github.com/MunchkinChen/FADING).