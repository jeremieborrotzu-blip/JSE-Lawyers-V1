
<div align="center">

# OpenClassrooms – JSE-Lawyers  
</div>

<p align="center">  
    <img src="https://img.shields.io/badge/MariaDB-v11.7.2-blue">  
    <img src="https://img.shields.io/badge/WordPress-v6-blue">  
    <img src="https://img.shields.io/badge/docker--build-passing-brightgreen">  
  <br><br><br>  
</p>

# Requirements  
To run this web application, you must have the following tools installed:  
- Docker  

# Installation and startup  
Clone the project to retrieve the files:  
```bash  
git clone https://github.com/OpenClassrooms-Student-Center/JSE-Avocats-V2.git  
cd JSE-Avocats-V2  
```  

To start the project:  
```bash  
docker compose up -d  
```  

# Important  
This application is built with WordPress.  
The final startup may take a few seconds after the containers have launched.  

## To stop the project  
Make sure you are in the root directory of the project  
(where the `docker-compose.yml` file is located):  
```bash  
docker compose down  
```  

## Cleanup after use  
If you don’t plan to return to the project, you may delete Docker files and images to free up space:  
```bash  
docker system prune -a  

=> type Y then press Enter  
```  

This will delete the entire project.
