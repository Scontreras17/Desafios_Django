La primera path('',	views.saludo), devuelve un saludo al ingresar a la pagina http://127.0.0.1:8000
La segunda path('saludo/<str:nombre>/',views.saludar_usuario), da un saludo personalizado segun el nombre del usuario http://127.0.0.1:8000/saludo/juan
La tercera path('edad/<int:edad>/', views.mostrar_edad), muestra la edad que se ingrese http://127.0.0.1:8000/edad/5/
