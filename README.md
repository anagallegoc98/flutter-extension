# mvc_pattern Flutter

Extensión para desarrollo de aplicaciónes flutter con mvc_pattern

Paquetes:
- [mvc_pattern](https://pub.dev/packages/mvc_pattern)
- [responsive_builder](https://pub.dev/packages/responsive_builder)(Si es un proyecto web)
- [provider](https://pub.dev/packages/provider) (para provider Shortcuts)
- [http](https://pub.dev/packages/http) (http service)
- [cloud_firestore](https://pub.dev/packages/cloud_firestore) (firebase service)
- [firebase_auth](https://pub.dev/packages/firebase_auth) (auth service)


## Release Notes

Se añaden wrappers 

### 0.0.6 

* Crear un proyecto base

[Proyecto base demo](https://www.youtube.com/watch?v=nI7Q8Lx5jjA)
[![Alt text for your video](https://img.youtube.com/vi/nI7Q8Lx5jjA/0.jpg)](https://www.youtube.com/watch?v=nI7Q8Lx5jjA&ab_channel=AnaMaria)



* Se agregan snippets:

| Shortcut                       | Description                                                                                   |
| -----------------              | ----------------------------------------------------------------------------------------------|
| `cls`                          | Nueva clase                                                                                   |
| `importe`                      | Insertar tools                                                                                |
| `importm`                      | Insertar import de material                                                                   |
| `args`                         | Se obtienen los argumentos pasados mediante route params y se asignan a una variable dinamica |
| `richText`                     | Inserta un widget tipo RichText                                                               |
| `initstate`                    | Se crea un init state con un future delayed dentro                                            |
| `fdelayed`                     | Inserta un future delayed con duration en zero                                                |
| `createprovider`               | Nueva clase que extiende de ChangeNotifier                                                    |
| `userprovider`                 | Retorna un la instancia de un objeto tipo user desde un user provider                         |
| `providerOf`                   | Obtiene una instancia de un provider                                                          |
| `providerOfFalse`              | Obtiene una instancia de un provider sin listen changes                                       |


[Snippets demo](https://www.youtube.com/watch?v=GqlCnLL_K-M)


* Se agegan wrapers:
Idea obtenida de: [widget-wrap](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap)


| Comando                        | Resultado                                                                                     |
| -----------------              | ----------------------------------------------------------------------------------------------|
| `Alt + C`                      | `Container`                                                                                   |
| `Alt + S`                      | `Stack`                                                                                       |
| `Alt + X`                      | `Column`                                                                                      |
| `Alt + R`                      | `Row`                                                                                         |
| `Alt + P`                      | `Positioned`                                                                                  |
| `Alt + E`                      | `Expanded`                                                                                    |
| `Alt + L`                      | `ListView`                                                                                    |
| `Alt + T`                      | `Text`                                                                                        |
