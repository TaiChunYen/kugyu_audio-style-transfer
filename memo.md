## data prepare
`sudo apt-get install youtube-dl`  
`pip install upgrade youtube-dl`  
`youtube-dl -F [URL]`(list download format)  
<<<<<<< HEAD
`youtube-dl -f [format code] [URL]`(download)

## gd to voice
train.py  
model.py  
utils.py  


=======
`youtube-dl -f [format code] [URL]`(download)  

python3.6 preprocess_training.py --train_A_dir ../jsut_ver1.1/basic1000 --train_B_dir ../kugyu/kugimiya --cache_folder ../kugyu/cache  
python3.6 train.py --logf0s_normalization ../kugyu/cache/logf0s_normalization.npz --mcep_normalization ../kugyu/cache/mcep_normalization.npz --coded_sps_A_norm ../kugyu/cache/coded_sps_A_norm.pickle --coded_sps_B_norm ../kugyu/cache/coded_sps_B_norm.pickle --validation_A_dir ../kugyu/eval/jsut/ --output_A_dir ../kugyu/convert/jsut/ --validation_B_dir ../kugyu/eval/km/ --output_B_dir ../kugyu/convert/kugimiya/ --model_checkpoint ../kugyu/model/  
python3.6 train.py --logf0s_normalization ./cache/logf0s_normalization.npz --mcep_normalization ./cache/mcep_normalization.npz --coded_sps_A_norm ./cache/coded_sps_A_norm.pickle --coded_sps_B_norm ./cache/coded_sps_B_norm.pickle --validation_B_dir ../vcc2016_evaluation_all/evaluation_all/SF1m/ --output_B_dir ./data/convert/SF1/ --validation_A_dir ../vcc2016_evaluation_all/evaluation_all/TM1m/ --output_A_dir ./data/convert/TM1/ --model_checkpoint ./data/check/

