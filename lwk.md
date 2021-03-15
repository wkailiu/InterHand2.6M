pip install pycocotools

cd demo
python demo.py --gpu 0 --test_epoch 20

python test.py --gpu 0 --test_epoch 20 --test_set val --annot_subset all