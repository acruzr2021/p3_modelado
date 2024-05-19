# Práctica 3 Modelado y Simulación de Robots.

## Índice

- [Gráficas](#gráficas)
  - [Floor world](#floor-world)
  - [Sand world](#sand-world)
- [Comparación](#comparación)
- [Fase A](#fase-a)
  

## Gráficas

### Floor world 

Velocidad final

![floor_plot](https://github.com/acruzr2021/p3_modelado/assets/92941137/57eb5b50-a880-454c-8072-72e94e16a772)

La línea azul muestra un aumento constante desde el origen hasta aproximadamente 3 en el eje Y, donde ocurren dos caídas notables antes de continuar ascendiendo, las cuales, se corresponden con dos colisiones con los cubos. Después de las colisiones, el robot recupera la velocidad y continua aumentando su velocidad hasta llegar a velocidad 5.

Velocidad publicada para las ruedas

![floor_wheels](https://github.com/acruzr2021/p3_modelado/assets/92941137/c5083418-d769-4745-a54b-704fe3cd06e1)

De la misma forma que la anterior, encontramos un aumento desde el origen hasta llegar a velocidad 15. En esta subida encontramos dos caidas de velocidad correspondientes a las dos colisiones que se pueden ver en el vídeo.

Gráfica IMU:

![floor_imu](https://github.com/acruzr2021/p3_modelado/assets/92941137/f779f878-9537-4ab4-8628-3d2adec25bd9)

La línea rosa oscila alrededor de la marca cero en el eje Y, lo que indica que el sensor está en un estado de equilibrio la mayor parte del tiempo, con algunas variaciones notables pero no extremas. Encontramos una bajada cuando se eleva por la colisión, una subida cuando las ruedas vuelven a tocar el suelo y otra pequeña bajada cuando las ruedas de atrás golpean el cubo. El sensor imu queda estable al salir del mapa.

Vídeo ejecución:

https://github.com/acruzr2021/p3_modelado/assets/92941137/fb07cf13-15d9-4764-baee-359426ef0a5a

Enlace rosbag:

[Rosbag]([https://drive.google.com/drive/folders/1SDk8P6YyzuxjOCf1vkAhIb2vB1f1G-jZ?usp=drive_link](https://drive.google.com/drive/folders/1SDk8P6YyzuxjOCf1vkAhIb2vB1f1G-jZ?usp=sharing))

### Sand world

Velocidad final

![sand_plot](https://github.com/acruzr2021/p3_modelado/assets/92941137/ee399306-158f-494f-864c-b731f05871a3)

La línea azul muestra un aumento constante desde el origen hasta aproximadamente 4 en el eje Y, donde ocurren una caída notable antes de continuar ascendiendo, la cuale, se corresponden con una colisión con un cubo. Después, el robot recupera la velocidad y continua aumentando su velocidad hasta llegar a velocidad 5.

Velocidad publicada para las ruedas

![sand_wheels](https://github.com/acruzr2021/p3_modelado/assets/92941137/1fbf283f-a7ac-46ef-953e-4dc0e62c430a)

De manera similar al escenario anterior, podemos ver un incremento de velocidad hasta estabilizarla sobre unos 17. Hay una caida de velocidad en la parte de incremento por la colisión.

Gráfica IMU:

![sand_imu](https://github.com/acruzr2021/p3_modelado/assets/92941137/7bae0c93-979f-473c-9195-23475043f1ba)

Como en el caso anterior, oscila alrededor de la marca cero en el eje Y, lo que indica que el sensor está en un estado de equilibrio la mayor parte del tiempo, con algunas variaciones, algo más elevadas que en el anterior. Encontramos una bajada cuando se eleva por la colisión y una subida cuando las ruedas vuelven a tocar el suelo. El sensor imu queda estable al salir del mapa.

Vídeo ejecución:

https://github.com/acruzr2021/p3_modelado/assets/92941137/bda47e68-6b69-4a3d-827d-0d45b727e022

Enlace rosbag:

[Rosbag](https://drive.google.com/drive/folders/19ltdUlZhe13wtP1IQmvR35gh_axI9uMn?usp=drive_link)

## Comparación

Podemos ver que en la arena, la gráfica del sensor IMU oscila algo más. Para la velocidad de las ruedas, vemos que, para alcanzar velocidad 5, en el escenario de la arena, es algo más alta por el tipo de terreno.

## Fase A 

[Vídeo](https://youtu.be/lUqWeLrpTyA)
