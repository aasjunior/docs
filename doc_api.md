# Sofia Api

<p align='justify'>Sofia é um Software Orientado por Inteligência Artificial para Auxílio ao Pré-diagnóstico de Crianças de 0 a 4 Anos com Manifestações Comportamentais do Transtorno do Espectro Autista (TEA). O aplicativo mobile <strong>CAD</strong> (computer aided design) é destinado ao auxílio de profissionais da saúde na triagem e identificação de sinais do TEA. <strong>Nosso Objetivo</strong> é promover a acessibilidade ao diagnóstico precoce de TEA!</p>

<p align='justify'>A Sofia API é uma API RESTful desenvolvida com Spring Boot e Java no VS Code. Ela foi projetada para ser utilizada pelo <a href="https://github.com/aasjunior/com.sofia.mobile.git">Sofia Mobile</a> para realização do CRUD com MySQL.</p>


**Versão da API:** <br><br>
**Data de Lançamento:** <br><br>
**Base URL:** &nbsp;[http://localhost:8080](http://localhost:8080/)
<br>
<br>

## 1. Pré-Requisitos

* JDK (Java Development Kit)
* MySQL
* Git
* VS Code (ou outra IDE de sua preferência)
<br>
<br>

## 2. Configuração do Projeto

a)&nbsp;&nbsp;&nbsp;Clone o repositório para sua máquina local usando o seguinte comando
```
git clone https://github.com/aasjunior/com.sofia.restapi.git
```
b)&nbsp;&nbsp;&nbsp;Abra o projeto no VS Code e adicione as seguintes extensões:
* `Extension Pack for Java`
* `Spring Boot Extension Pack`
* `Thunder Client` ou outro cliente REST API para testar as requisições HTTP.
<br>

c)&nbsp;&nbsp;&nbsp;Certifique-se de que o JDK está instalado e configurado corretamente.<br>
d)&nbsp;&nbsp;&nbsp;Certifique-se de que o MySQL está instalado e funcionando corretamente<br>
e)&nbsp;&nbsp;&nbsp;Configure a API Sofia pelo VS Code. A API estará rodando em [http://localhost:8080](http://localhost:8080/)<br>
<br>

## 3. Endereços da API

| Type          | Path            | Obs.                                      |
| ------------- |-----------------|:-----------------------------------------:|
| GET           | /pacientes      | Retorna uma lista de todos os pacientes.  |
| POST          | /pacientes      | Insere um novo paciente.                  |
| GET           | /pacientes/{id} | Retorna um paciente específico pelo ID.   |
| PATCH         | /pacientes/{id} | Atualiza um paciente pelo ID.             |
| DELETE        | /pacientes/{id} | Remove um paciente pelo ID.               |

## 4. Tecnologias 
<p align="center">
   <img src="https://github.com/aasjunior/com.sofia.mobile/assets/85968113/adc364c7-8401-4326-ad56-3807673b85f2" width="600px" alt="Android"/>
   <div align="center"><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"/>
   <img src="https://img.shields.io/badge/Spring_Boot-2B9348?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
   <img src="https://img.shields.io/badge/MySQL-purple?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/></div>
</p>

## 5. Nosso Time AJA 
You can see more about us in our profile:
* [Amanda](https://github.com/mandis-ncs)
* [Junior](https://github.com/aasjunior)
* [Aline](https://github.com/AlineLauriano)

###### Aviso
Esta é uma iniciativa acadêmica, sendo assim, não possui todas as funcionalidades e características de uma aplicação real.