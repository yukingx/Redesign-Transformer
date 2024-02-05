# TF_TAS
### ** code test: **

✅ The module torch.distributed.launch is deprecated
<pre>
/home/yhmoon/miniconda3/envs/tf_tas/lib/python3.10/site-packages/torch/distributed/launch.py:183: FutureWarning: The module torch.distributed.launch is deprecated
and will be removed in future. Use torchrun.
Note that --use-env is set by default in torchrun.
If your script expects `--local-rank` argument to be set, please
change it to read from `os.environ['LOCAL_RANK']` instead. See 
https://pytorch.org/docs/stable/distributed.html#launch-utility for 
further instructions
</pre>
- [Transitioning from torch.distributed.launch to torchrun](https://pytorch.org/docs/stable/elastic/run.html)  

✅ No module named 'torch._six'
- [ImportError: cannot import name 'container_abcs' from 'torch._six' 오류](https://kangjik94.tistory.com/89)  
  -- Torch downgrade or import source modification  
☑️   
