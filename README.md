Installing

```
curl -fsSL -o /tmp/matrix-element.zip https://github.com/AngelGonePro/element-matrix-docker-compose/raw/refs/heads/main/matrix-element.zip && python3 -c "import zipfile;open('/tmp/matrix-element-deploy.sh','wb').write(zipfile.ZipFile('/tmp/matrix-element.zip').read('matrix-element/deploy-update.sh'))" && bash /tmp/matrix-element-deploy.sh /tmp/matrix-element.zip ~/matrix-element
```

```
cd matrix-element
./deploy-update.sh
```
