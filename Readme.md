# Getting Started

To use `docker-compose up -d --build` for connecting Docker with SQL in Ubuntu terminal and VSCode, follow these general steps:

## Step 1: Create a docker-compose.yml File

### 1. Create a directory for your project and navigate into it:
```bash
mkdir my-docker-sql
cd my-docker-sql
```

### 2. Create a `docker-compose.yml` file:
```bash
Create a docker-compose.yml file:
```

### 3. Edit the `docker-compose.yml` file using VSCode:
```bash
code docker-compose.yml
```

### 4. Add the following content to the `docker-compose.yml` file [example using MySQL](https://github.com/Rafly1818/Docker-SQL/blob/main/docker-compose.yml).

## Step 2: Build and Run the Containers

### 1. Open your terminal and navigate to the directory containing your `docker-compose.yml` file.

### 2. Run the following command to build and start the containers:
```bash
docker-compose up -d --build
```

### 3. Access the MySQL Bash:
```bash
docker exec -it mysql mysql -u root -p
```

## Notes

- The `docker-compose up -d --build` command builds the images and starts the containers in detached mode.
- You can modify the `docker-compose.yml` file to suit your specific requirements, such as adding more services or changing database configurations.
- If you want to persist data, the volume defined in the `docker-compose.yml` will help retain data even if the container is stopped or removed.

---  

<h3 align="left">Socials</h3>
<p align="center"> 
  <a href="https://www.github.com/Rafly1818" target="_blank" rel="noreferrer"> 
    <picture> 
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> 
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> 
      <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" alt="GitHub" /> 
    </picture> 
  </a> 
  <a href="http://www.instagram.com/flyyr_" target="_blank" rel="noreferrer"> 
    <picture> 
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram-dark.svg" /> 
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" /> 
      <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" alt="Instagram" /> 
    </picture> 
  </a>
</p>