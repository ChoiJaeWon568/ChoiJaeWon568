
# Torch ENV
```
python -c "$(curl -fsSL https://raw.githubusercontent.com/pytorch/pytorch/master/torch/utils/collect_env.py)"
```


# OS
```
cat /etc/os-release
```

# CPU
```
cat /proc/cpuinfo | grep "model name"; cat /proc/cpuinfo | grep "model name" | wc -l
```

# Memory
```
free -th
sudo dmidecode --type 17
```

# Storage
```
df -h | grep dev/sd
```

# CUDA
```
nvidia-smi
```

# NVCC
```
nvcc --version
```

# Mainborad
```
sudo dmidecode -t 2
```
