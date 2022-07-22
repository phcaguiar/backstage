# ${{ values.name }}

```bash
docker build -t ${{ values.name }} .
```

```bash
docker run -d -p 5000:80 --name ${{ values.name }} ${{ values.name }}
```