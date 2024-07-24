```
git clone https://elichen:$GITHUB@github.com/elichen/karpathyGPT2.git
git config --global user.name "elichen"
git config --global user.email "eli.chen@gmail.com"
```

```
torchrun --standalone --nproc_per_node=$RUNPOD_GPU_COUNT train_gpt2.py
```
