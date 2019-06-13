## post process the image.manifest

```bash
sed -i.bak 's/\(:\).*\(=\)/\1\2/' $1
sed -i.bak 's/=//' $1
```
