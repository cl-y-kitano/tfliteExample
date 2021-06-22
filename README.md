## SAMPLE arm Linux tflite!

## install package

```
./download.sh
pip install https://dl.google.com/coral/python/tflite_runtime-1.14.0-cp37-cp37m-linux_aarch64.whl
```

## usage

```
python3 main.py \
  --model /tmp/mobilenet_v1_1.0_224_quant_edgetpu.tflite \
  --labels /tmp/labels_mobilenet_quant_v1_224.txt \
  --image {your imageFile}
```

