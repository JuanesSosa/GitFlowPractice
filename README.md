# Nombre del Proyecto

API de Practica Git Flow

## Descripción

Este proyecto es una mini API construida con Express para practicar Git Flow en una actividad guiada.

La API tiene un endpoint de estado que permite comprobar que el servidor esta funcionando correctamente.

## Instalación

Requisitos:

- Node.js 20 o superior.
- npm.

Pasos:

~~~bash
git clone https://github.com/JuanesSosa/GitFlowPractice.git
cd GitFlowPractice
npm install
~~~

## Uso

Levantar el servidor local:

~~~bash
npm start
~~~

Probar el endpoint:

~~~bash
curl http://localhost:3000/api/estado
~~~

Respuesta esperada:

~~~json
{
  "ok": true,
  "mensaje": "API de practica Git Flow funcionando",
  "version": "1.0.0"
}
~~~

## Autores

- Nombre: Juan Esteban Sosa
- Grupo: 1
- Curso: Inge Software II

## Flujo de trabajo Git

Este proyecto usa Git Flow como estrategia de ramas.

- La rama `develop` integra los cambios antes de liberar una versión.
- Las ramas `feature/` se usan para desarrollar nuevas funcionalidades.
- La rama `release/v1.0.0` prepara la versión estable del proyecto.
- La rama `hotfix/readme-typo` corrige errores urgentes desde main.