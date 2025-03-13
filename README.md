# Jenkins Lab

## Ejecutar Docker Compose

Para ejecutar Docker Compose, asegúrate de que tengas Docker Compose instalado en tu sistema. Luego, sigue estos pasos:

1. Navega a la ubicación donde se encuentra tu archivo `docker-compose.yml`.

2. Ejecuta el siguiente comando en tu terminal para iniciar los contenedores definidos en el archivo `docker-compose.yml`:

```bash
docker-compose up -d
```

3. Extraer passwords

```bash
docker logs id_container
```

```bash
docker exec id_container cat /var/jenkins_home/secrets/initialAdminPassword
```

Se extare la password 
![image](https://github.com/user-attachments/assets/462193fc-7fe7-434c-ab43-11720bded6a8)


![image](https://github.com/user-attachments/assets/2f8740ce-a323-4046-be1a-abc5fd482349)

![image](https://github.com/user-attachments/assets/43030017-b84a-4194-bd50-13259d668b4a)

![image](https://github.com/user-attachments/assets/dbe60c77-242f-4efb-accc-ae87bc0c3580)

![image](https://github.com/user-attachments/assets/210acca9-6e9e-4a31-a3ba-cc857877d01e)

![image](https://github.com/user-attachments/assets/99443038-6abd-452d-acee-ddabcba3aaed)

![image](https://github.com/user-attachments/assets/43ab3b6e-584f-4d4a-ac29-0793ff1e4627)
![image](https://github.com/user-attachments/assets/969ae8e1-6154-4f32-b16f-c498621cff77)

![image](https://github.com/user-attachments/assets/dfd0783b-488c-4de8-8f15-f26a3658df0f)

![image](https://github.com/user-attachments/assets/388e2b7d-7f4a-4ff1-984b-0ee719322f4a)

![image](https://github.com/user-attachments/assets/f3395558-6359-4886-86c1-89263e67e8d4)








