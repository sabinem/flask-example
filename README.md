# simple flask app

## install

```
virtualvenv myvenv
source myvenv/bin/activate
pip install -r requirements.txt
```

## use

```
flask --app hello.py run
```

Website is available at http://127.0.0.1:5000/

## build docker container

```
docker image build --no-cache -t flask_docker .
docker run -d -p 5001:5000 flask_docker 
```

Website is available at http://127.0.0.1:5001/
