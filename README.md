# Docker Project for ReactJS

## A. Build

``` format
docker build -t <Image_Name> .
```

example :

``` shell
docker build -t reactjs/temperature-convert:1.0.0 .
```

## B. Run

``` format
docker run -d -p <PORT_IN>:<PORT_OUT> --name <Container_Name> <Image_Name>
```

example :

``` shell
docker run -d -p 3000:3000 --name react-dev reactjs/temperature-convert:1.0.0
```

---

Notes:
ganti nama file <code>.env.example</code> menjadi <code>.env</code> saja (tanpa .example)
