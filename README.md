# spring-boot-itegra-email

```sh
Aqui possui dois projetos
1-listvip
2-enviadorEmail

3-Observação: O projeto eviadoEmail e integrado no projeto listvip (o qual foi adcional através do pom.xml no projeto "listvip")

4-  Exemplo:


       <dependency>
			<groupId>br.com.alura.enviadorEmail</groupId>
			<artifactId>enviadorEmail</artifactId>
			<version>0.0.1-SNAPSHOT</version>
		</dependency>

```
## 1. Requisitos 

Instalar as seguintes ferramentas:

    1. JDK 1.8
    3. Maven

    Obs: esse projeto esta utilizando o banco postgres, porém pode ser realizado alterações na pasta conf/JPAConfiguration.java para o banco desejado

    Opcional: caso você utilize banco de dados não e necessário instalar os itens abaixo.

    4. docker

    Aqui no dbeaver você podera adcionar o banco postgres ou o  banco desejado para visualizar os dados se estiver utilizando o docker-compose
    caso deseja utilizar outro banco no docker e necessario baixar a imagem do banco desejado pois aqui esta a imagem do postgres 9.4

## 2.Não esquecer de mudar as configuraçoes do seu email

1- Pacote: br.com.alura.enviadorEmail.enviadorEmail
2-Classe: 
EmailService

## 3. Requisitos

1.criar um jar do projeto enviadorEmail: 
mvn clean istall

2.criar um jar do projeto listvip: 
mvn clean istall




## 4.Porta padrão

localhost:9000


```
