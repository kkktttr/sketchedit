# Code for the paper ``SketchEdit: Mask-Free Local Image Manipulation with Partial Sketches"

## Environment

Please use the provided Dockerfile. 

GPU is required. 

The code only has been tested on Ubuntu 20.04.

## Usage

### environment 

install using the provided docker file ```Dockerfile```

```
conda activate editline
```

### Testing

1. model trained on celebahq

```
./test_celeb.sh
```

2. model trained on places

```
./test_places.sh
```

### Interactive demo

1. model trained on celebahq

```
./demo_celeb.sh
```

then open localhost:8000 in the browser

2. model trained on places

```
./demo_places.sh
```

then open localhost:8001 in the browser


You may change the configuration by modifying these bash scripts. 

## Training code and data
Training code and data will be released after the paper is published. 
