# Code

Zifan's personal coding space.

## Trash

Long time non used repo will be moved to Trash dir. 

Non necessary build dir and dependency dir will be removed before moved to Trash dir.

Repos in Trash dir will be archived. Using tar

```bash
tar -cvzf Trash.tar.gz Trash
split -b 32M Trash.tar.gz Trash.tar.gz_ # split to 32M for simple update
```

To restore an archive

```bash
cat Trash.tar.gz_* > Trash.tar.gz
tar -xvf Trash.tar.gz
```

## Servers

Servers information is stored in apple key chain.

## 2fa

2fa keys and recovery code is auto backup from ~/.local/Share/2fa
# Alex222222222222
