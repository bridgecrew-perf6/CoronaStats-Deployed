# CoronaStats-Deployed
</p>
<p">
    <a href=""><img src="https://img.shields.io/badge/Build%20Status-passing-green?style=for-the-badge" alt="build status"></a>
    <a href=""><img src="https://img.shields.io/badge/Running%3F-Yes-green?style=for-the-badge" alt="running"></a>
    <a href=""><img src="https://img.shields.io/badge/Monitor%20Running%3F-Yes-green?style=for-the-badge" alt="monitor running"></a>
</p>
CoronaStats 2.0 - Deployed Edition!

Deployed @ [http://coronastats-deployed.dev.subalp.xyz/](http://coronastats-deployed.dev.subalp.xyz/)

&nbsp;


**How to build and run container:**

**Build the Image:**
```
docker build -t coronastats .
```

**Run the Image by running the following command:**
```
docker run -p 5000:5000 --rm --name coronastats-deployed coronastats
```

&nbsp;

| Category   | Requirement                                                                    | ✅ |
|------------|--------------------------------------------------------------------------------|---|
| 🐳 Docker     | Repository contains a Dockerfile and a docker-compose.yml file              | ✅ |
| 🐳 Docker     | Dockerfile and docker-compose.yml file build without error                  | ✅ |
| ⚙️ Deployment | Project deployed on CapRover using your own domain                          | ✅ |
| ⚙️ Deployment | Uptime monitored by FreshPing or another health check service               | ✅ |
| ⚙️ CI         | Project includes continuous integration                                     | ✅ |
| 📝 Docs       | README includes badges for image size, build status, and website monitoring | ✅ |
| 📝 Docs       | README includes instructions on how to build and run your container         | ✅ |