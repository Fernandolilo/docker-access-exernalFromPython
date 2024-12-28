"# docker-access-exernalFromPython" 


exemplo de acesso externo com python, framework flask e docker;

endipoint: http://localhost:5000/

comando de build: docker build -t flaskexterna .

comando de geração de container:

docker run -d -p 5000:5000 --name flaskexternacontainer --rm flaskexterna

