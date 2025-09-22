# lama-cleaner

```
docker run -p 8080:8080 \
  -v /c/Users/PC/.cache/torch:/root/.cache/torch \
  -v /c/Users/PC/.cache/huggingface:/root/.cache/huggingface \
  --rm cwq1913/lama-cleaner:cpu-0.26.1 \
  lama-cleaner --device=cpu --port=8080 --host=0.0.0.0
```

http://localhost:8080
