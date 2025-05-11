```shell
pip install pip3-autoremove
pip uninstall torch torchvision torchaudio xformers
pip-autoremove torch torchvision torchaudio -y
pip install torch torchvision torchaudio xformers --index-url https://download.pytorch.org/whl/cu121
pip install --upgrade --no-cache-dir --no-deps git+https://github.com/unslothai/unsloth.git
```