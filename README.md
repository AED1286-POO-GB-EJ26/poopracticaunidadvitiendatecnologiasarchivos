[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/i3uWaE8A)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=24011340)
# Unidad V - Practica: Tienda Electronica, Interfaces Excepciones, Genericidad y Persistencia

En esta practica se integran los fundamentos de Programacion Orientada a Objetos para modelar y resolver el caso de una tienda electronica, aplicando encapsulamiento, herencia, polimorfismo, clases abstractas, interfaces, arreglos, genericidad, manejo de excepciones y persistencia


## Uso del proyecto con make

### Default - Compilar + Probar + Ejecutar

```bash
make
```

### Compilar

```bash
make compile
```

### Probar todo

```bash
make test
```

### Ejecutar app

```bash
make run
```

### Limpiar binarios

```bash
make clean
```

## Compilacion manual

```bash
find ./ -type f -name "*.java" > compfiles.txt
javac -encoding utf-8 -d build -cp lib/junit-platform-console-standalone-1.5.2.jar @compfiles.txt
```

## Ejecucion manual de pruebas

```bash
java -jar lib/junit-platform-console-standalone-1.5.2.jar --class-path build --scan-class-path
```

## Ejecucion manual de la aplicacion

```bash
java -cp build miPrincipal.Principal
```
