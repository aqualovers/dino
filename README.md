# To use
python -m torch.distributed.launch --nproc_per_node="NUMBER_OF_GPUS" main_dino.py --arch vit_small --data_path ./data --output_dir ./results
