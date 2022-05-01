# How to build and run docker image

exec docker bulid . -t golang_app_image  
exec docker run --rm -p 8080:8080 -d golang_app_image

# Testing

用postman或瀏覽器連線到
```
http://localhost:8080/ping
```
會看到response，docker用dashboard看log也會有結果
