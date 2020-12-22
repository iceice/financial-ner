Download the Bert pretrained model

mkdir bert-base-chinese
cd bert-base-chinese

wget -c https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese-pytorch_model.bin -O pytorch_model.bin

Download the Bert config file 
wget -c https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese-config.json -O config.json

Download the Bert vocab file 
wget -c https://s3.amazonaws.com/models.huggingface.co/bert/bert-base-chinese-vocab.txt -O vocab.txt


ps: https://huggingface.co/bert-base-chinese/tree/main