# config文件的产生过程
## STEP1 预配置
进入工作目录

```bash
make riotboard_defconfig
```

## STEP2 修改配置
```bash
make menuconfig
```

进入`Environment`

1. 修改`Environment offset`的值为`0xC0000`
2. 修改`mmc device number`的值为`3`

## STEP3 完成
此时工作目录下的`.config`文件即可使用
