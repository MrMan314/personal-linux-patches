# To apply patches:
```bash
cd linux
for i in ../patches/*; do patch -Np1 < $i; done
```

# Credits & Sources
* relaxable_rmrr.patch (updated to work with latest linux kernel sources) - [killer129/relax-intel-rmrr](https://github.com/kiler129/relax-intel-rmrr)
* lar_disable.patch - [hehe reversed this "upgrade"](https://patchwork.kernel.org/project/linux-wireless/patch/20191223234721.1513938-7-luca@coelho.fi/)
