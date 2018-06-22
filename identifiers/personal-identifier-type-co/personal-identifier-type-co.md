# Tipo de Identificación de Personas - Colombia

* **System URL:** [Recurso FHIR / formato XML](https://github.com/interoperar/fhir-local-terminologies-valuesets/blob/master/identifiers/personal-identifier-type-co.xml)
* **Identifier:** personal-identifier-type-co
* **Version:** 1.0
* **Name:** Tipo Identificación Personas - Colombia
* **Status:** Active
* **Date:** 2018-01-01
* **Publisher:** Ministerio de Salud y Protección Social
* **Contact:** <https://www.minsalud.gov.co/>
* **Jurisdiction:** Colombia
* **Copyright:** GNU LESSER GENERAL PUBLIC LICENSE Version 3, 29 June 2007 - Creative Commons Attribution-ShareAlike 4.0 International Public License
* **Case Sensitive:** True
* **Content:** Complete

## Descripción.
Tipo de identificación de la persona (usuario del sistema de salud).  

Corresponde al documento de la Registraduría Nacional con el cual se identifican las personas ante el Sistema de Salud Colombiano, con excepción de las personas que no se han registrado. 
 
### Reglas de uso.
* Para los adultos, mayores de 18 años de nacionalidad colombiana, el documento con el cual se deben identificar es la **cédula de ciudadanía**.  
* Para los extranjeros que se encuentran de paso en el país se identifican con el **pasaporte**, y para los residentes o con permiso de permanencia, es decir, no turisrtas, se deben identificar con la **cédula de extranjería**.
* Los niños entre 7 y 17 años, deben identificarse con la **tarjeta de identidad**.
* Para niños menores de 7 años, el tipo documento será el **registro civil**.
* **MS**: Solo se debe utilizar para el Recién Nacido vivo sin identificar (hasta los 30 días de nacido), y se registra: Número de documento de la madre si existe o el número de documento del cabeza de familia y un consecutivo iniciando en uno (1).
* Si el menor ya está registrado el documento será el **Registro Civíl** (RC).
* **MS y AS** en poblaciones especiales, el registro se debe ceñir al lo contenido en el anexo técnico de la Resolución 890/2007.

## Tabla de codificación.

|Code      |Display	                               |
|:---------|:--------------------------------------|
|**CC**    |Cédula de Ciudadanía                   |
|**CE**    |Cédula de Extranjería                  |
|**PA**    |Pasaporte                              |
|**RC**    |Registro Civil                         |
|**TI**    |Tarjeta de Identidad                   |
|**NUI**   |Número Único de Identificación Personal|
|**CD**    |Carné Diplomático                      |
|**PE**    |Permiso Especial                       |
|**AS**    |Adulto sin identificación              |
|**MS**    |Menor sin identificación               |
|**NN**    |Sin Nombre                             |