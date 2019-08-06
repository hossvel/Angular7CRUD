# AngularProductApp

# generar compilado de angular8
    ng build --prod

# generar una imagen mode stage
docker build -t webapp:latest --build-arg configuration="staging" .

# generar una imagen mode prod
docker build -t webapp:latest .

# run imagen

