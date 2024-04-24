# Consumo de API
Arquitectura MVVM + Clean Arquitecture

# Descripción del ejercicio
Elaborar un proyecto en la arquitectura MVVM de preferencia + Clean Arquitecture

1.-1 Pantalla con 2 botones con los textos personajes y episodios.
2.-El boton de episodios te debe enviar a otra pantalla donde se mostrara el listado de episodios.
3.-GET https://rickandmortyapi.com/api/episode, que pinte en una lista el name, episode y air_date
4.-Tener un buscador por name o episode.

# Estructura del proyecto
Arquitectura MVVM + Clean Arquitecture

# API
https://rickandmortyapi.com/api/episode

# Descarga de la APK
https://drive.google.com/file/d/1Vt7U_8kWp3NXkm7czpGoSMAB7188MeH7/view?usp=sharing

# Video de la Aplicación
https://drive.google.com/file/d/1FbCxuFowYYjcESu1K3w9ZpwWmDNSfM1w/view?usp=sharing

# Codigo en GitHub
https://github.com/jggjosue/ApiBabel/tree/main

Domain
com.magzin.apibabel.domain.core.RetrofitHelper

<img width="269" alt="image" src="https://github.com/jggjosue/ApiBabel/assets/29234812/1dcd4a0f-fa57-439c-925d-440a1269b5fb">


Data
Modelo de Datos
com.magzin.apibabel.data.model.RickMortyModel
com.magzin.apibabel.data.model.ResultsRickMortyModel
com.magzin.apibabel.data.model.RickMortyProvider

Servicios
com.magzin.apibabel.data.network.RickMortyApiClient
com.magzin.apibabel.data.network.RickMortyService

Repositorio
com.magzin.apibabel.data.RickMortyRepository

<img width="304" alt="image" src="https://github.com/jggjosue/ApiBabel/assets/29234812/a0be2a82-4e3a-4eb7-8f2a-2f6054b7b805">


Use Cases
com.magzin.apibabel.usecase.GetRandomRickMortyUseCase
com.magzin.apibabel.usecase.GetRickMortyUseCase

<img width="325" alt="image" src="https://github.com/jggjosue/ApiBabel/assets/29234812/12ec0c4f-ebeb-4753-b2a3-094418c76d86">


Presentation
view
com.magzin.apibabel.ui.view.CustomAdapter
com.magzin.apibabel.ui.view.MainActivity
com.magzin.apibabel.ui.view.SelectActivity

viewmodel
com.magzin.apibabel.ui.viewmodel.RickMortyViewModel

<img width="290" alt="image" src="https://github.com/jggjosue/ApiBabel/assets/29234812/a6d0c532-673a-4741-98f3-f8ef0bc2d06a">


