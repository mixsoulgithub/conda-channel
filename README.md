# conda-channel

`metro-tui` 的 conda 频道(静态托管在 GitHub Pages 上,不依赖 anaconda.org)。

```bash
conda install -c https://mixsoulgithub.github.io/conda-channel metro-tui
# micromamba install -c https://mixsoulgithub.github.io/conda-channel metro-tui
```

包内容与 GitHub Release 里的静态 musl 二进制完全一致(sha256 可对照);
recipe 在同仓库源码的 `packaging/conda/meta.yaml`。
