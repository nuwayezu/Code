
1 file changed
+1
-1
lines changed

 
‎README.md
+1
-1


Original file line number	Diff line number	Diff line change
@@ -45,7 +45,7 @@ python ./examples/data_preprocess/countdown.py --local_dir {path_to_your_dataset
conda activate zero
```

For the following code, if you see Out-of-vram, try add `critic.model.enable_gradient_checkpointing=True` to the script
For the following code, if you see Out-of-vram, try add `critic.model.enable_gradient_checkpointing=True` to the script, and checkout the discussion [here](https://github.com/Jiayi-Pan/TinyZero/issues/5#issuecomment-2624161643)

**Single GPU**
