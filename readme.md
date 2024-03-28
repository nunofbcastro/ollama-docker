<h1 align="center">OLLAMA Docker</h1>

<img src="/.github/assets/home.png?raw=true"/>

<h2>How to run</h2>

```
docker compose up -d
```

<h2>How to run if you have Nvidea GPU</h2>

```
docker compose -f docker-compose.nvidea.yml up -d
```

<h2>How to run if you have AMD GPU</h2>

```
docker compose -f docker-compose.amd.yml up -d
```

<h2>How add model</h2>

```
docker exec -it ollama-server ollama run llama2
```

or

<img src="/.github/assets/add_model.png?raw=true"/>
