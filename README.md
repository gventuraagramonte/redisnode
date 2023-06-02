# REDISNODE

## Este ejemplo es para integrar redis con nodejs y hacer las consultas mas rapidas

### Se debe ejecutar el siguiente código antes de levantar el index

```bash
docker run -p 6379:6379 --name some-redis -d redis
```

### Si queremos ver la bd redis, debemos instalar el servidor web local con el siguiente comando
```bash
npm install -g redis-commander
```

### Luego corremos el siguiente comando
```bash
redis-commander
```