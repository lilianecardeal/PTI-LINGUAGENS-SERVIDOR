# 🏋️‍♂️ Cálculo de IMC em PHP

Este projeto é um simples calculador de IMC (Índice de Massa Corporal) desenvolvido em **PHP**, utilizando **XAMPP** como servidor local.

## 📌 Objetivo

O programa recebe um valor de IMC e retorna a classificação correspondente de acordo com a tabela do **IMC**.

## 🛠️ Tecnologias Utilizadas

- 🐘 PHP
- 🏗️ XAMPP (Apache + MySQL + PHP + Perl)
- 🖥️ Navegador Web

## 🚀 Como Executar

### 1️⃣ Instalar o XAMPP

Caso ainda não tenha o XAMPP instalado, baixe e instale através do site oficial:
🔗 [https://www.apachefriends.org/](https://www.apachefriends.org/)

### 2️⃣ Mover o Arquivo para o Servidor

Copie o arquivo `calculoimc.php` para a pasta do servidor local:

```bash
sudo mv /home/liliane/Downloads/calculoimc.php /opt/lampp/htdocs/

3️⃣ Iniciar o XAMPP
Execute o XAMPP e inicie o servidor Apache:

sudo /opt/lampp/lampp start

4️⃣ Acessar pelo Navegador
Abra o navegador e digite:

http://localhost/calculoimc.php


Atenção, seu IMC é 19.5, e você está classificado como Saudável ✅

📌 Classificação do IMC

## 📌 Tabela de Classificação

| IMC (kg/m²)        | Classificação          |
|--------------------|----------------------|
| Até 18.5          | Magreza              |
| 18.51 a 24.9      | Saudável             |
| 25.0 a 29.9       | Sobrepeso            |
| 30.0 a 34.9       | Obesidade Grau I     |
| 35.0 a 39.9       | Obesidade Grau II    |
| Acima de 39.9     | Obesidade Grau III   |


Feito com ❤️ por Liliane Cardeal 😊
