<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>



# Ejecutar en desarrollo

1. clonar el repositorio

2. Ejecutar
```bash
yarn install
```

3. Tener Nest CLI instalado
```bash
yarn add -g @nestjs/cli
```

4. Levantar la base de datos
```bash
docker-compose up -d
```

5. Instalar mondodb nest
```bash
yarn add @nestjs/mongoose mongoose
```

6. Crear Moculo
```bash
nest g mo common
```

7. Crear Pipes Personalizados
```bash
nest g pi common/pipes/parseMongoId --no-spec
```

8. Generar un Seed
```bash
nest g res seed --no-spec
```

9. Reconstruir la DB con un seed
```bash
http://localhost:3000/api/v2/seed
```

10. Añadir variables de entorno
```bash
yarn add @nestjs/config
```

11. Joi validations
```bash
yarn add joi
```

12. Clonar el archivo __.env.template__ y renombrar la copia a __.env__

13. Llenar las variables de entorno definidas en el .env

14. Ejecutar la aplicacion de desarrollo en dev con
```bash
yarn run start:dev
```


##  Stack Usado
*MongoDB
*Nest


