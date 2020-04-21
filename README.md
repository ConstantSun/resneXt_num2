# PyTorch Implementation of ResNeXt

refer: https://github.com/hysts/pytorch_resnext

Create your own hyper params using these agrs in terminal:
'--depth' 

'--base_channels'

'--cardinality'

'--epochs'

'--batch_size'

'--base_lr'

'--weight_decay'

'--momentum'

'--nesterov'

'--milestones'

'--lr_decay'

running: !python main.py --depth 29 --base_channels 64 --epochs 230 

result on CIFAR10 : test acc = 95.58%.(9 hours on google Colab, model size ~ 17million params)
