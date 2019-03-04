Tạo images: docker build -t reactapp .
Chạy project: docker run -d -p 4000:80 reactapp
Stop run project: docker container stop [name containner]
List containner: docker container ls