# 📚 Ejercicio 3: Inventario de Productos con Map y List

## 📌 Descripción
Este programa permite gestionar un inventario de productos categorizados utilizando la estructura de datos `Map<String, List<String>>`. Permite agregar categorías, productos, listar productos por categoría y mostrar el inventario completo.

## 🚀 Funcionalidades

✅ Solicitar la cantidad de categorías al usuario.
✅ Registrar productos dentro de cada categoría en un `Map<String, List<String>>`.
✅ Mostrar todos los productos de una categoría específica.
✅ Permitir la adición de un nuevo producto a una categoría existente.
✅ Mostrar la lista completa de categorías y sus productos.

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Java  
- **Estructura de datos:** `Map<String, List<String>>`
- **Compilación y gestión de dependencias:** Apache Maven

## 📂 Estructura del Proyecto

```
REFUERZO_JAVA-1
│── src
│   ├── main
│   │   ├── java
│   │   │   ├── com
│   │   │   │   ├── refuerzo
│   │   │   │   │   ├── Ejercicio3.java
│── target 
│── pom.xml (archivo de configuración de Maven)
│── README.md (documentación del proyecto)
```



## 📈 Ejemplo de Uso

**Entrada:**
```
Ingrese la cantidad de categorías: 2
Categoría 1 - Nombre: Electrónica
Producto: Laptop
Producto: Smartphone
Categoría 2 - Nombre: Ropa
Producto: Camisa
Producto: Zapatos
```

**Salida esperada:**
```
Lista de categorías y sus productos:
Electrónica: Laptop, Smartphone
Ropa: Camisa, Zapatos

Ingrese el nombre de la categoría para ver sus productos: Electrónica
Productos en Electrónica: Laptop, Smartphone

Ingrese el nombre de la categoría a la que desea agregar un producto: Ropa
Ingrese el nuevo producto: Bufanda

Lista actualizada de categorías y productos:
Electrónica: Laptop, Smartphone
Ropa: Camisa, Zapatos, Bufanda
```

## 📌 Autor

👤 **Osman Johandry Ortiz Rolon**



