# PSC SLURM, SBATCH commands

`interact -p GPU-shared --gres=gpu:v100-32:1 -t 30:00`

`sbatch -p GPU-shared --gres=gpu:v100-32:1 -t 48:00:00 -e error.txt -o output.txt job.sh`

# CLI args

```bash
# Decode
python decode.py --exp_dir exp/train_run1 --ckpt_name epoch22.pth --decode_tag zero
```